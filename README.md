# serverless-framework-sample

```shell
npm install -g serverless
npm install --save-dev serverless-step-functions
serverless create --template aws-python3 --name hello --path ./
serverless deploy
serverless invoke -f hello

Running "serverless" from node_modules
{
    "statusCode": 200,
    "body": "{\"message\": \"Go Serverless v1.0! Your function executed successfully!\", \"input\": {}}"
}
```