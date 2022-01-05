# Test 3: Terraform with AWS

Your company need to host a marketing website with static files that is accessible from the internet. When the website content need to be updated, Alice and Bob, your company's marketing managers will do it. Alice and Bob will use a software that will help them update the website content via AWS API, and they are responsible to manage their own AWS credentials, including access key and secret key. Using Terraform, your task is to provision these AWS resources:

- S3 bucket to host the website.
- IAM users for Alice and Bob, with sufficient permissions.

Your company hire a consultancy firm, CharlieCo, to analyse the website content. CharlieCo also use AWS and they will send you their AWS account ID later. Your task is to provision these AWS resources:

- S3 bucket for CharlieCo to upload their analysis.
- IAM role for CharlieCo staff with sufficient permissions.

Hint: in order to test this scenario, you can create sub accounts in your main AWS account using [AWS Organizations](https://aws.amazon.com/organizations/).
