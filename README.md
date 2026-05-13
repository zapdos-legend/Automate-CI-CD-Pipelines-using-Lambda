# Automate-CI-CD-Pipelines-using-Lambda
Automated CI/CD deployments using AWS Lambda and CodePipeline to trigger application updates automatically.

## 🎯 Purpose

The purpose of this project is to automate CI/CD pipeline execution using AWS Lambda functions.

This project demonstrates how Lambda can automatically trigger deployment workflows whenever specific events occur, enabling faster and fully automated software delivery.

This automation helps in:

* Automatically triggering deployments
* Reducing manual intervention
* Improving deployment speed
* Enabling serverless CI/CD automation
* Enhancing continuous integration and deployment workflows

## 🧰 AWS Services Used

* **AWS Lambda** – Used for automatically triggering deployment workflows and automation tasks.
* **AWS CodePipeline** – Used for managing and automating the CI/CD deployment pipeline.

## 📸 Project Screenshots

### 1. Lambda Function
This shows the Lambda function configuration.
![Lambda](Lambda%20Function%20Create.png)

### 2. Lambda Event Code
This shows the Lambda trigger event code.
![Event](Lambda%20Function%20Event%20code.png)

### 3. CodePipeline
This shows the CI/CD pipeline workflow.
![Pipeline](CodePiline%20Create.png)

### 4. S3 Bucket 1
This shows the first S3 bucket used in the pipeline.
![S3-1](S3%20Bucket1.png)

### 5. S3 Bucket 2
This shows the second S3 bucket used in the pipeline.
![S3-2](S3%20Bucket2.png)

## 📂 Project Files

### Build Specification
[View buildspec.yml](buildspec.yml)

### Frontend File
[View index.html](index.html)

### Create Buckets Script
[View create_buckets_VsCode.py](create_buckets_VsCode.py)

### Create CodeBuild Role Script
[View create_code_build_role_VsCode.py](create_code_build_role_VsCode.py)

### Create CodeBuild Script
[View create_codebuild_VsCode.py](create_codebuild_VsCode.py)

### Create Pipeline Script
[View create_pipeline_VsCode.py](create_pipeline_VsCode.py)

### Create Roles Script
[View create_roles_VsCode.py](create_roles_VsCode.py)

### Lambda Trigger Pipeline Script
[View lambda_trigger_pipeline_VSCODE.py](lambda_trigger_pipeline_VSCODE.py)
