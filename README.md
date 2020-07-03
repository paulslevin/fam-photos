# Fam-Photos

Application with Go backend hosted on AWS Elastic Beanstalk and React frontent hosted on Amazon S3.

## How to deploy backend

Navigate to local git repo and run the following command:

```
eb deploy
```

## How to deploy backend

Navigate to local git repo and run the following commands:

```
npm run build
aws s3 sync build s3://paulslev.in
```
