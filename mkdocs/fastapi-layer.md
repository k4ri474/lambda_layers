# fastapi-layer
[Lambda Layer](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html) for application using [FastAPI](https://fastapi.tiangolo.com/)

## packages
```python
boto3==1.11.11    # for connecting dynamodb
botocore==1.14.11 # for connecting dynamodb
fastapi           # FastAPI
uvicorn           # ASGI Server for local environment
requests          # dependency
pytest            # for testing app
pytest-cov        # pytest plugin for codecov
black             # syntax checker/autofixer
mangum            # handler for API-GW -> Lambda -> FastAPI
```

## usage
1. Change directory to `lambda_layers/fastapi`.
2. Deploy Lambda Layer by Serverless Framework.
```
sls deploy
```
