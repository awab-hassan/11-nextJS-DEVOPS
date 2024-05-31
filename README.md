# Project #11 - NextJS Application Deployment on ECS Cluster

Project Type: NextJS Application Deployment on ECS Cluster with Task Definition and Services.

Project Description: Client asked me to deploy any NextJS docker image on ECS cluster and GitHub Actions pipeline that will automatically deploy a new version whenever changes are pushed to the repository.

Solution:
- I configured security group for my NextJS application.
- I configured security group for LoadBalancer.
- I deployed an ECS cluster.
- I deployed a Task definiton according to my Application needs.
- I deployed my task in service.
- I attached some extra permisions in ecsTaskExecution Role.
- I deployed a Github Actions Pipeline, whenever changes are pushed to code the pipeline will Build, Tag, Push the image to ECR repository and then run a new task .
- I provided the demo to the client of applicaiton.

![acd8731ab4e64397ba9baa9881b3b858](https://github.com/awab-hassan/11-nextJS-DEVOPS/assets/90965012/a17d34c2-a8c4-4e83-ab0e-c2a309c4f6e0)
