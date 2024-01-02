# Udagram

Instagram-like application where you can register, login and upload/post images with captions.

## Overview

- Angular
- NodeJs

CICD
- CircleCI

Platform
- S3
- ElasticBeanstalk
- RDS

## Run Locally

### Install, build, test, run frontend

- `npm run frontend:install` will install dependencies
- `npm run frontend:build` will build locally
- `npm run frontend:test` will test locally
- `npm run frontend:run` will run the frontend

### Install, build, run backend

- `npm run api:install` will install dependencies
- `npm run api:build` will build locally
- `npm run api:run` will run the backend

## Environment variables

```bash
export POSTGRES_USERNAME= # DB USERNAME 
export POSTGRES_PASSWORD= # DB PASSWORD
export POSTGRES_HOST= # DB HOST FROM AWS
export POSTGRES_DB= # DB NAME
export AWS_BUCKET= # BUCKET FROM AWS
export AWS_REGION= # REGION ON AWS
export AWS_PROFILE= # this can be: default
export JWT_SECRET= # ANY
export URL= # For this project: http://localhost:8100
```

## Screenshots

Running deployed project (it can be accessed using below URL)

![Screenshot 2023-12-28 at 17 45 50](https://github.com/AhmedBSF/udagram/assets/101567711/3f18d828-09a1-4f0c-833d-12619d7ddd4d)

![Screenshot 2023-12-28 at 17 45 25](https://github.com/AhmedBSF/udagram/assets/101567711/5097f3b5-9bb9-414a-9924-6da93ebc5673)

![Screenshot 2023-12-28 at 17 49 18](https://github.com/AhmedBSF/udagram/assets/101567711/6f4de140-40d2-4d41-b1de-ebc4b90528c7)


## Link
http://udagrambucket.s3-website-us-east-1.amazonaws.com/
