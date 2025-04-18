# AWS-Automation
This repo has a documentation about AWS automation using AWS services such as AWS CLI, AWS CFT, AWS API, and Python Module Boto3

https://docs.aws.amazon.com/cli/latest/userguide/cli-services-ec2-instances.html
https://aws.amazon.com/cli/

Link to repos and information : 
create EC2 instance using AWS cli :- aws ec2 run-instances \
  --image-id ami-0069aa073aac75299 \
  --count 2 \
  --instance-type t2.micro \
  --key-name my-keys \
  --security-group-ids sg-0370989af055636f0 \
  --region us-east-1 \
  --tag-specifications 'ResourceType=instance,Tags=[{Key=Name,Value=ubuntu-20-04}]'
🔑 Required Parameters:

Parameter	Description
--image-id	The AMI ID to use (e.g., Amazon Linux 2, Ubuntu, etc.)
--count	Number of instances to launch
--instance-type	EC2 type (e.g., t2.micro for free tier)
--key-name	The name of your existing key pair (for SSH access)
--security-groups	A security group with proper rules (allow SSH etc.)
--region	AWS region to deploy to



https://cloud-images.ubuntu.com/locator/

AWS CFT :- https://github.com/aws-cloudformation/aws-cloudformation-templates
Boto3 :- https://gist.github.com/mda590/679aba60ca03699d5b12a32314debdc0
