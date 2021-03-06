<!--
title: Hello World Node.js Example
menuText: Hello World Node.js Example
description: Create a Node.js Hello World Lambda function
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/aws/examples/hello-world/node/)
<!-- DOCS-SITE-LINK:END -->

# Hello World Node.js Example

Make sure `serverless` is installed. [See installation guide](../../../guide/installation.md).

## 1. Deploy

`serverless deploy` or `sls deploy`. `sls` is shorthand for the Serverless CLI command

## 2. Invoke deployed function

`serverless invoke --function helloWorld` or `serverless invoke -f helloWorld`

`-f` is shorthand for `--function`

In your terminal window you should see the response from AWS Lambda

```bash
{
  "message": "Hello World",
  "event": {}
}
```

Congrats you have just deployed and ran your Hello World function!
