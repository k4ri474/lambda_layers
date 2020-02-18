# Overview
[Lambda Layers](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html) for personal application.

---

**Documentation**: https://k4ri474.github.io/lambda_layers/

**Source Code**: https://github.com/k4ri474/lambda_layers

---

## My Layers
- **[fastapi-layer](https://github.com/k4ri474/lambda_layers/tree/master/fastapi)**: for api system using [FastAPI](https://fastapi.tiangolo.com/)

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
