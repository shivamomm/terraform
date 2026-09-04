# Terraform — Local + AWS

Minimal Terraform project to provision a local file and an AWS S3 bucket.

## Stack

* Terraform
* AWS Provider
* Local Provider
* Amazon S3

## Usage

```bash
terraform init
terraform validate
terraform plan
terraform apply
```

Destroy:

```bash
terraform destroy
```

## Resources

```text
local_file → local filesystem
aws_s3_bucket → Amazon S3
```

> AWS credentials are resolved via the AWS CLI environment/config. No secrets are committed.
