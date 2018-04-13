# pipelines-lambda-node

This repository provides a docker image to replicate the available node runtimes on AWS Lambda, along with `zip` and the AWS CLI for deployment purposes.

## Usage

Node v8.10    
`FROM theleague/pipelines-lambda-node:8`

Node v6.10.3    
`FROM theleague/pipelines-lambda-node:6`

Node v4.3.2   
`FROM theleague/pipelines-lambda-node:4`
