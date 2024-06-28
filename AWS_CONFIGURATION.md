# AWS Configuration

To get AWS configuration keys, you can use the AWS CLI (Command Line Interface). Here’s how you can retrieve your AWS configuration details, including your access key, secret key, and region:

### Configure AWS CLI: 

If you haven't configured AWS CLI yet, you can do so using the aws configure command. This will prompt you to enter your AWS access key ID, secret access key, region, and output format.
    
    aws configure

    
### Retrieve Configuration Keys: 
  
To view your current AWS configuration, you can use the aws configure list command:

    aws configure list

### View Specific Configuration Files: 

You can also directly view your AWS configuration files located in ~/.aws/config and ~/.aws/credentials.

    cat ~/.aws/config
    cat ~/.aws/credentials
