# Secure Hybrid Access to Amazon S3

A bilingual Hugo workshop for configuring private Amazon S3 access from an Amazon VPC and a simulated on-premises environment using Gateway and Interface VPC Endpoints.

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
