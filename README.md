# Cloud Resume (backend)
[devinstormharris.io](https://devinstormharris.io)

## About the Project
This project is the backend for an entirely serverless application that runs on AWS. It utilizes CloudFormation for IaC. It builds a DynamoDB table that holds the count of how many visitors have visited the webpage, a Lambda function which returns the data inside the DynamoDB table and then updates that table, and also builds an API Gateway so the [frontend](https://github.com/DevinStormHarris/frontend_cloud_resume) can communicate with the backend. It uses CodeBuild to build and deploy the application. 

### Built With
- Python
- AWS SAM
- DynamoDB
- Lambda
- API Gateway
- CodeBuild
