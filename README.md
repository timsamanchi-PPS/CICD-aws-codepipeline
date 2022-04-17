# CICD aws-codepipeline project
detailed walk through on creation of CICD aws-codepipeline to maintain and update AWS infrastructure using terraform

## requirements
  * source code repository    
  * terraform.tfstate file s3 bucket    
  * codebuild artifacts s3 bucket  
  * dynamoDB lockID  
  * terraform docker image  
  * aws codestar connector
  * infrastructure DEV environment