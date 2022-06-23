# parameterized-aws-codebuild-docker-image-buildspec
A parameterized Buildspec file for AWS CodeBuild that builds docker images and pushes them to ECR. At the end the updated image version is updated in the k8s yaml file of the service to adopt GitOps. After the yaml is update you can have a CD tool like ArgoCD or Flux to synchronize the changes on the k8s(EKS/GKE) cluster. 

All the parameters are configured in the 'Environment Variables' section of the CodeBuild project. 
