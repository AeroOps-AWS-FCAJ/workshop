# DocuFlow AI Workshop

A bilingual Hugo workshop for building a serverless invoice and document processing platform on AWS. It covers Amazon S3, DynamoDB, Lambda, SQS, EventBridge, Step Functions, Textract, API Gateway, Cognito, observability, governance, and end-to-end testing.


## Run locally

Requirements: Hugo Extended 0.134.3 or later.

```powershell
hugo server -D
```

Open `http://localhost:1313/workshop/`.

## Build

```powershell
hugo --minify
```

The generated site is written to `public/`. Pushes to `main` are deployed to the `gh-pages` branch by GitHub Actions.


# AeroOps Team