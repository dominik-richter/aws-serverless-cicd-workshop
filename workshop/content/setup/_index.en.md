+++
title = "Setup"
date = 2019-10-02T10:19:58-07:00
weight = 5
chapter = true
pre = "<b>0. </b>"
+++

# Setup

### AWS Account

In order to complete this workshop, you’ll need access to an AWS account. Your access needs to have sufficient permissions to create resources in IAM, CloudFormation, API Gateway, CodeCommit, CodePipeline, CodeBuild, CodeDeploy and S3. If you currently don't have an AWS account, you can create one here: [https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account).

---

### Setup using AWS Cloud9 (Recommended)

[AWS Cloud9](https://aws.amazon.com/cloud9/) is a cloud-based integrated development environment (IDE) that lets you write, run, and debug code from any machine with just a browser. We recommend using it to run this workshop because it already comes with the necessary set of tools pre-installed, but the workshop is not dependent on it, so you are free to run it from your local computer as well.

If you want to use Cloud9, follow these instructions: [Create a Cloud9 Workspace](/javascript/setup/cloud9.html).

---

### Setup using my own computer, not using Cloud9

If you prefer to run the workshop from your local computer without using Cloud9, make sure you install the following tools which are available for Linux, MacOS and Windows.

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
  - Required to simulate the Lambda runtime locally.
- [SAM CLI v1.35.0+](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)
  - To run functions locally, create a pipeline and package/deploy SAM apps manually.
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
  - To create resources in your AWS account.
- [Git Client](https://git-scm.com/downloads)
  - To interact with the CodeCommit repository by pushing code changes.
- [NodeJS and npm](https://www.npmjs.com/get-npm)
  - The sample app you will create is NodeJs-based.

Once you have installed all requirements, you can start the workshop here: [Start workshop](/sam.html).
