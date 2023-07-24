# serverless-web-application
I had done this project in serverless web application on aws
Project Name: Serverless Web Application on AWS
Project Description:
In this project, I will build a serverless web application using AWS Lambda, DynamoDB, S3, CloudFront and Route 53. The registration form will allow user to submit the personal details and login the email id and password.Then count login data will be stored in DynamoDB table.

 
Steps to build the project:
1)	Create a S3 bucket and to store the static web host application files (HTML, CSS, JAVA SCRIPTS)
2)	Create a CloudFront distribution to serve the S3-hosted static files with low latency.
3)	Create a Hosted zone using route 53 and attach the name server with domain.
4)	Create a DynamoDB table to store the items
5)	Create an AWS Lambda function to handle the CRUD operation on the DynamoDB table.
6)	Test the project.
