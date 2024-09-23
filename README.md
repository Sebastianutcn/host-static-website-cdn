# host-static-website
This repository contains Terraform code to provision infrastructure for hosting a static website on AWS, using Amazon S3 for static content storage.

**Files:**
1. [`main.tf`](https://github.com/Sebastianutcn/host-static-website-s3/blob/main/main.tf) 
2. [`./src/index.html`](https://github.com/Sebastianutcn/host-static-website-s3/blob/main/src/index.html) is a simple HTML file.
3. [`./src/error.html`](https://github.com/Sebastianutcn/host-static-website-s3/blob/main/src/index.html) is a custom HTML page displayed when an error is encountered.

## Installation
- Terraform command to initialize the project
```
terraform init
```
* Terraform command to plan the changes and to check again the resources that were added, changed or deleted
```
terraform plan -out plan.out
```
- Terraform command to apply the changes
```
terraform apply plan.out --auto-approve
```
