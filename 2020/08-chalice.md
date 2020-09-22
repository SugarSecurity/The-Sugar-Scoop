# Serverless Python APIs with AWS Chalice

Get started in 4 steps:
1. Get an AWS Account
2. Set up API Keys for your AWS Account
3. Configure the AWS CLI
4. Install Chalice and say "Hello World!"

## Get an AWS Account
> https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/

If you've signed up for *any* website before, you can sign up for AWS. It will ask for a credit card, but you can do a lot of crazy stuff with it [for free](https://aws.amazon.com/free/)

## Set up API Keys for your AWS Account
> https://youtu.be/665RYobRJDY

When choosing permissions for the keys, you get to weigh the risk vs. the amount of research you need to do. It's easiest up front to add the user to the Admins group. 

## Configure the AWS CLI

### Windows
Download and run the MSI installer from https://awscli.amazonaws.com/AWSCLIV2.msi

### Linux
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" 
unzip awscliv2.zip 
sudo ./aws/install 
```

### Testing your Installation
```
aws --version
```

### Configuring with your API Keys
> https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-config

## Install Chalice
> https://aws.github.io/chalice/quickstart.html
