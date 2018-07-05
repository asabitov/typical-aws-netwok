# A typical AWS network infrastructure

This CloudFormation template helps to create a typical AWS network infrastructure, which can be used as a base for easy deployment of various projects. 

Run it in AWS CLI as follows:
```
# aws cloudformation create-stack --stack-name MyVPC --template-body file://typical-aws-network.json --parameters ParameterKey=VPCName,ParameterValue="MyVPC"
```
