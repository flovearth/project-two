This project will create an infrastructure on AWS with use of Terraform.

Requirements:
- an EC2 (Windows 2019 Base server)
- a Lambda fucntion which will turn on the server
- a Lambda fucntion which will shut down the server
- an Alarm which will shut down the servert after 1 hour inactivity
- an Elastic IP which will be associated to server
- required iam roles,Function security groups
- outputs: Elastic IP, instance id, The URL of the Lambda Function to shutdown and run
- a SNS topic which will will email when the server stopped automaticall
