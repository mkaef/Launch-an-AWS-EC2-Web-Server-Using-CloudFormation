
# Use CloudFormation to Launch an Amazon EC2 Web Server.

The purpose of this project is to create a Base Template that contains necessary resources to launch an AWS EC2 instance.

## What is CloudFormation ?

CloudFormation is essentially infrastructure as a code which allows us to automate the creattion of AWS Resources within a singular template. The reason we want to this is because we want to create multiple resources at different times, we don't have to go into the console over and over again to create the same thing. We can create one base template and modify that template which we can deploy multiple times.









## First we will create a template where we will list our resources.

1. Security Group with resource type:AWS::EC2::SecurityGroup
2. EC2 Instance with resource type: AWS::EC2::Instance
## Next create stack using your pre-defined template.
## Next observe resource creation.
## Next check for the  instance EC2 instance creation.
## Finally browse your HTML Web Page using the public IP address.
## Resource:
reference Template: https://github.com/azeezsalu/how-to-host-a-html-website-on-aws-with-cloudformation

security group: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-securitygroup.html

ec2 instance: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-instance.html