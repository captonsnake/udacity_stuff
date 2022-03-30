# README for Udagram Project

This folder contains the starter yaml and params file to setup networking and instances for the Udagram project


URL will be displated in outputs of cloudformation.

## My Running Example:

`http://udagr-webap-q1cwuryqz554-141123213.us-east-1.elb.amazonaws.com/`

## Creating:
```bash
aws cloudformation create-stack --stack-name Udagram-project --template-body file://final-project-starter.yml --parameters file://final-project-params.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1
```

## Deleting:
```bash
aws cloudformation delete-stack --stack-name Udagram-project
```