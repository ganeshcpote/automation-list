# Automation List

List of automation, POC and their respective code repositories. Please do write any feedback or suggestions to ganesh.c.pote@gmail.com

## Cloud Automation (Provisioning and Decommissioning) 
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Terraform Multicloud (AWS, Azure & GCP) Deployment using Jenkins Pipeline with email notification | Show how to use terraform for multi-cloud (AWS, Azure & GCP) deployments using Jenkins pipeline and integration with postgres as state management. It also send the email notification to the end users with cloud resources | [terraform-multicloud-example](https://github.com/ganeshcpote/terraform-multicloud-example) | Jenkins, Python, Terraform |

## Cloud Security, Compliance and Audit
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | AWS Cloud Trail dashboard for live compliance, risk and audit monitoring | Shows how to use Grafana as live AWS CloudTrail monitoring dashboard to monitor the activities from AWS account and generate the alerts. This is something out-of-box solution using open source tools | [aws-cloudtrail-grafana-dashboard](https://github.com/ganeshcpote/aws-cloudtrail-grafana-dashboard) | AWS CloudTrail, Lambda, Grafana, ElasticSearch, Python |
| 2 | AWS System Manage Agent Patching and compliance dashboard with historical trend | Show how to fetch AWS System Manage Agent Patching details using Lambda and display periodic trend using Grafana and elasticsearch. This will also help to check how keep eye on our patching compliance regularly | [aws-ssm-patching-status-grafana-dashboard](https://github.com/ganeshcpote/aws-ssm-patching-status-grafana-dashboard) | AWS SSM, Lambda, Grafana, ElasticSearch, Python |
| 3 | Golden image with vulnerabilities and security assessment scanning using AWS Inspector and Packer | Show how to use the AWS Inspector to scan security assessment and find the vulnerabilities in the base image and create the new golden image out of it using package using Jenkins pipeline for CI/CD | [packer-awsinspector-jenkins-awsami](https://github.com/ganeshcpote/packer-awsinspector-jenkins-awsami) | Jenkins Python, Shell |
| 4 | AWS KMS Encryption | Show how to use Lambda functions (python) to encrypt the S3 bucket, Elastic search service, EC2 EBS volumes and AWS RDS (Aurora and non-Aurora) databases using AWS KMS | [aws-kms-encryption](https://github.com/ganeshcpote/aws-kms-encryption) | AWS KMS, Lambda, Python |
| 5 | IAM AWS Key Rotation using Lambda and SMTP | Show how to use simple workflow to automate IAM AWS Key Rotation using Lambda and send SMTP notification to AWS IAM users when their AWS keys are rotated | [aws-iamkeyrotation-lambda](https://github.com/ganeshcpote/aws-iamkeyrotation-lambda) | Lambda, Python |

## Cloud DevOps
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | CI/CD : DevSecOps Docker Deployment Pipeline for Java Projects | Shows how to use the DevSecOps feature in Jenkins pipeline for Java spring boot projects. This will help to perform code quality,  code vulnerabilities,  code dependencies and Docker vulnerabilities checks regularly with CI/CD pipeline to generate the quality code and Docker image | [java-devsecops-pipeline](https://github.com/ganeshcpote/java-devsecops-pipeline) | Jenkins, Python |

## ChatBot
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Cloud OpsBot Using Amazon Lex and Slack for Provision of Cloud Resources | Shows how we can use the Amazon Lex Service to build your own Cloud Operations Bot using Slack to perform the daily cloud operational activities like provisioning of resources, adding capacity etc. with Jenkins as backend orchestration | [opsbot-awslex-slack](https://github.com/ganeshcpote/opsbot-awslex-slack) | AWS Lex, Lambda, Slack, Jenkins Python, Terraform |

## Application Monitoring and Performance
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Website Performance Monitoring using Sitespeed.io and Jenkins | Show how to use the sitespeed.io an open source website performance tool to measure the performance of your website. It has various in-built features like web crawler, recording, synthetic monitoring, and performance execution using chrome user experience, google page speed insight, google lighthouse to get performance score of your website | [webperformance-sitespeed](https://github.com/ganeshcpote/webperformance-sitespeed) | Jenkins Python, Sitespeed.io |

## Cleanup Operations
| # | Automation / POC Name | Short Description | Repository | Technologies |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Clean Lambda Old Versions | Show how to use simple lambda function which help to clean-up the old version of AWS lambda functions and also can schedule using CloudWatch event to run daily | [clean-aws-lambda-old-versions](https://github.com/ganeshcpote/clean-aws-lambda-old-versions) | Lambda, Python |

