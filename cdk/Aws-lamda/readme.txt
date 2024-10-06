mkdir infra
mkdir services
cd infra
cdk init app --language typescript
https://docs.aws.amazon.com/cdk/api/v2/docs/aws-cdk-lib.aws_lambda.Function.html

npm run build
cdk bootstrap --> onetime
cdk synth
cdk deploy
cdk destroy