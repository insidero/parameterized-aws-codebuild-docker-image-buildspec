# parameterized-aws-codebuild-docker-image-buildspec
A parameterized Buildspec file for AWS CodeBuild that builds docker images and pushes them to ECR. At the end the updated image version is updated in the k8s yaml file of the service to adopt GitOps
