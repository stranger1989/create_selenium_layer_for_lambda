# Create Selenium Layer for AWS

This layer will be invoked lambda functions. 

## Environment
python3.6

## Serverless framework install via npm
```buildoutcfg
npm i -g serverless
```

## Layer deploy
```
sls deploy -v --aws-profile { aws_profile_name }
```

## Layer remove

```
sls remove -v --aws-profile { aws_profile_name }
```