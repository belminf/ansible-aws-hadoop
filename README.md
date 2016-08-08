Creates an EC2 deployment of Hadoop.

# Requirements
Requires [AWS CLI](https://aws.amazon.com/cli/) along with some Python libraries and environment variables.

## Python
    $ pip install -r requirements.txt

## Environment
Configuration for AWS CLI:

    AWS_ACCESS_KEY_ID="KEY_ID_HERE"
    AWS_SECRET_ACCESS_KEY="ACCES_KEY_HERE"

Required for the AWS playbook:

    AWS_DEFAULT_REGION="us-east-1"
    AWS_DEFAULT_AZ="us-east-1a"
    AWS_KEY_NAME="my_ssh_key"

# Creating the AWS deployment
    $  ansible-playbook playbooks/aws_deploy.yaml
