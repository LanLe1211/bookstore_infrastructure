# bookstore_infrastructure

In terminal, navigate to infrastructure's project directory
cd /Users/thuylanle/git/bookstore_infrastructure
aws configure. Then enter access key in IAM Security credential
secret access key must be saved during manual creation in AWS IAM Users

Create yam file in infrastructure repo then run command to deploy to AWS

Run command:

cd to the bookstore_infra


`aws cloudformation deploy --template-file template.yml --stack-name bookstore-infra --parameter-overrides GithubConnectionArn=arn:aws:codeconnections:us-east-2:659898573182:connection/9ad4cc53-6992-417d-b3f0-036ecb02cb0a --capabilities CAPABILITY_IAM` 

