# VPC
    aws cloudformation create-stack --stack-name parker-vpc-stack --template-body file://vpn.yaml --parameters ParameterKey=EnvironmentName,ParameterValue=pneff_
    aws cloudformation delete-stack --stack-name parker-vpc-stack 