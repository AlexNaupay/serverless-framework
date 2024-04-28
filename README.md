# serverless-framework

```bash
wget http://dynamodb-local.s3-website-us-west-2.amazonaws.com/dynamodb_local_latest.tar.gz
mkdir .dynamodb
tar zxvf dynamodb_local_latest.tar.gz -C .dynamodb

npm install -g serverless
serverless|sls dynamodb install
sls offline start
```

### Install AWS-Cli before
```bash
aws configure
```


### Env vars
```bash
sls deploy --stage prod
```

