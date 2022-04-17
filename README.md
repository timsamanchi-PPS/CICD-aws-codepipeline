# CICD aws-codepipeline project
detailed walk through on creation of CICD aws-codepipeline to maintain and update AWS infrastructure using dockerHub terraform image

## requirements
  * source code repository   
  * dockerHub terraform image 
  * terraform.tfstate file s3 bucket    
  * aws secerts arn for dockerHub creds
  * codebuild artifacts s3 bucket  
  * dynamoDB lockID  
  * terraform docker image  
  * aws codestar connector
  * infrastructure DEV environment

### secrets arn
arn:aws:secretsmanager:eu-west-2:673011710804:secret:codebuild/dockerHub-THFnGV

### codestar arn
arn:aws:codestar-connections:eu-west-2:673011710804:connection/221036b2-235c-4939-9ed0-7a327607a252

### github apps id and connection names
id: 25018306
codepipeline connection name: github-aws-codepipeline