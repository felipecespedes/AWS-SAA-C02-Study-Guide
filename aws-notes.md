## VPC Endpoints

When using endpoints in a region different than default (us-east-1) then the `aws cli` should be configured with the right region.
- [AWS CLI Configuration basics](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)
- [AWS regions](https://docs.aws.amazon.com/general/latest/gr/rande.html)
- [VPC endpoints - S3 troubleshoot](https://aws.amazon.com/premiumsupport/knowledge-center/connect-s3-vpc-endpoint/)

```bash
# Configure aws cli
aws configure
```

```bash
# Set region in each "aws" call
aws s3 ls --region us-east-2
```

