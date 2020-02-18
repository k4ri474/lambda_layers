# Overview
[Lambda Layers](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html) for personal application.

## My Layers
- **[fastapi-layer](fastapi-layer.md)**: for api system using [FastAPI](https://fastapi.tiangolo.com/)

## Requirements
[serverless framework](https://serverless.com/) is required to deploy Lambda Layer.
```
npm i -g serverless
```

## Global Setup
Before deploying each layer, install `serverless-python-requirements` by package.json.
```
npm install
```
The package compresses the library described in requirements.txt.
