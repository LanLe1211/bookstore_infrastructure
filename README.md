# bookstore_infrastructure

Run command:
`aws cloudformation deploy --template-file template.yml --stack-name bookstore-infra --parameter-overrides GithubConnectionArn=arn:aws:codeconnections:us-east-1:654654293002:connection/8f44d31e-2762-4281-83a5-4cb29b35ef1e --capabilities CAPABILITY_IAM`