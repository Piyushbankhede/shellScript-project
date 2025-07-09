
# 🔍 AWS Resource Lister - Shell Script

## 📜 Description

This shell script automates the process of listing AWS resources across various services using the AWS CLI. It's a handy tool for DevOps engineers, cloud administrators, and AWS learners to quickly inspect their cloud environment from the terminal.

Supported AWS services include:
- EC2
- RDS
- S3
- CloudFront
- VPC
- IAM
- Route53
- CloudWatch
- CloudFormation
- Lambda
- SNS
- SQS
- DynamoDB
- EBS

## ✍️ Author

**Piyush Bankhede**  
Version: `v0.0.1`

---

## 🧰 Prerequisites

- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) must be installed.
- AWS CLI must be configured (`aws configure`).
- Bash shell (Linux/macOS/WSL).

---

## 🚀 Usage

```bash
./aws_resource_list.sh <aws_region> <aws_service>
