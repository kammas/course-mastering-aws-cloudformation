
```shell
PROFILE=cloudguru
REGION=us-east-1
CourseBucketParam=acg-deploy-bucket-pkammas
aws s3api create-bucket \
  --bucket $CourseBucketParam \
  --region $REGION \
  --profile $PROFILE
```
