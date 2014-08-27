git-hooks-AWSCLI-S3
===================

Series of functional hooks to integrate GIT with AWS S3 via the AWS CLI and the AWS S3 CLI.

## Requirements

* **AWS S3 Instance** - A fully configured, Amazon Web Services Simple Storage System (S3) [instance](http://aws.amazon.com/documentation/s3/). More commonly, we would be using an AWS S3 instance that has been configured to host a static website with GIT based deployments. [Static Hosting Guide](http://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html)
* **AWS Command Line Interface** – The Amazon Web Services command line interface (CLI) available [here](https://github.com/aws/aws-cli)
* **AWS IAM Role** - A properly configured and permissioned IAM user account and role with access to secret/private keys. This can also be achieved with environmental variables and configuration settings, but AWS' IAM is the best practice for communicating across the AWSCLI. [AWS IAM] (http://aws.amazon.com/iam/)
* **GIT** – If you're reading this, there's really no point in explaining this dependency. GIT is awesome. We love GIT.
* **UNIX/Bash Compatible Environment** – 

## Installation
