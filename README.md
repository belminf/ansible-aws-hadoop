Creates an EC2 deployment of hadoop. Requires [AWS CLI](https://aws.amazon.com/cli/).

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
    AWS_KEY_NAME="my_ssh_key"
    AWS_DEFAULT_AZ="us-east-1a"

# Creating the AWS deployment
    $  ansible-playbook playbooks/create_aws_env.yaml
