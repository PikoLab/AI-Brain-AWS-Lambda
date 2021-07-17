# AWS Lambda 
Adding feature by AWS Lambda function and Serverless service

1. Install Serverless and connect to AWS
```
$ npm install -g serverless
$ sls create -t aws-nodejs
$ sls config credentials --provider aws --key "PUT YOUR KEY" --secret "PUT YOUR SECRET"
```

2. Create Lambda function "Rank" based on usage(entries) of the app  

3. Deploy and GET AWS Lambda http endpoint

```
$ sls deploy
```

4. Fetch AWS Lambda http endpoint and creat front-end feature `./components/Rank/Rank.js`
