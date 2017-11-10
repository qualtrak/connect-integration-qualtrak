# connect-integration-qualtrak

## Amazon Connect Integration -- Evaluate for Amazon Connect

**Evaluate for Amazon Connect** is a Agent Evaluation product that has been integration with **Amazon Connect**. For a fuller explanation of our **Evaluate** please click [here](http://www.qualtrak.com). This GitHub OSS repository contains two templates that must both be deployed together.  We have also included supporting materials whcih can be found near the end of this file.  The order of deployment is import.  This is covered shortly.  Deploying both templates will stand up everything required for your customers using **Amazon Connect** to have a Quality Monitoring product.

The use-cases that deployment templates deal with, fits this configuration:

- Your customer is new to AWS and wants to use a Cloud Contact Center and a QM product
- Your customer has already set up both **Amazon Connect** and Kinesis Stream that streams the CTRs to either RedShift, S3 or other.

Your customer's organisation must be using Active Directory, either in AWS (e.g. SimpleAD) or on premise with **Direct Connect**

## Deployments

- Deploy for a new VPC - `evaluate-json-master.template`
- Deploy for an existing VPC with Data Streaming - `evaluate-datastreaming-json-master.template`
- Deploy for an existing VPC without Data Streaming - `evaluate-json.template`

![Architecture](http://s3.amazonaws.com/Qualtrak/Quick%20Start%20Architecture%20Diagram.JPG)
