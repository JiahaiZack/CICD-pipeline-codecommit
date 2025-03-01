# CI/CD pipeline
This project is to implement a CI/CD pipeline. 

Once you make any changes to this repo, a new Docker image is created and pushed to ECR then deployed to ECS Fargate.

Tools that involved in this project: ECR, ECS, EC2, CodeBuild, CodeDeploy, CodePipeline

http://cicd-pipeline-1056952345.us-east-1.elb.amazonaws.com/

This web has been deployed...I guess...

Next step: Creating a serverless email reminder application. This application will load from S3 bucket, communicate with Lambda and Step Function via API Gateway Endpoint to send emails to users.