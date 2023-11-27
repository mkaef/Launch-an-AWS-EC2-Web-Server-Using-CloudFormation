
# Use CloudFormation to Launch an Amazon EC2 Web Server.

The purpose of this project is to create a Base Template that contains necessary resources to launch an AWS EC2 instance.

## What is CloudFormation ?

CloudFormation is essentially infrastructure as a code which allows us to automate the creattion of AWS Resources within a singular template. The reason we want to this is because we want to create multiple resources at different times, we don't have to go into the console over and over again to create the same thing. We can create one base template and modify that template which we can deploy multiple times.









## First we will create a template where we will list our resources.

1. Security Group with resource type:AWS::EC2::SecurityGroup
2. EC2 Instance with resource type: AWS::EC2::Instance
   ![CF-template](https://github.com/mkaef/Launch-an-AWS-EC2-Web-Server-Using-CloudFormation/assets/20161437/7c8dca2f-a187-4c1a-b837-59098af9d398)

## Next create stack using your pre-defined template.
![uploadedfile](https://github.com/mkaef/Launch-an-AWS-EC2-Web-Server-Using-CloudFormation/assets/20161437/32e42d7c-da7a-4ab7-b2da-12291e3dbcc6)
## Next observe resource creation.
![creation-complete](https://github.com/mkaef/Launch-an-AWS-EC2-Web-Server-Using-CloudFormation/assets/20161437/7afb6c0c-fe65-4760-8d1f-f1a2fe5d998d)
## Next check for the  instance EC2 instance creation.
![EC2-Instance-created](https://github.com/mkaef/Launch-an-AWS-EC2-Web-Server-Using-CloudFormation/assets/20161437/588e441d-3fd5-4cfb-834e-0c4377cb189e)
## Finally browse your HTML Web Page using the public IP address.
## Resource:
reference Template: https://github.com/azeezsalu/how-to-host-a-html-website-on-aws-with-cloudformation

security group: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-securitygroup.html

ec2 instance: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-instance.html
