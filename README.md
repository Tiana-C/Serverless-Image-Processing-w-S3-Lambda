# Serverless-Image-Processing-w-S3-Lambda *Project in progress 

## Overview
This project demonstrates how to build a **serverless image processing pipeline** on AWS.  
When an image is uploaded to an S3 bucket, a **Lambda function** is triggered automatically to resize it and convert it to grayscale. The processed image is then stored in a second S3 bucket.

## Services Used
- **Amazon S3** – Storage buckets for original and processed images  
- **AWS Lambda** – Serverless function to process images  
- **IAM** – Role with S3 access for Lambda  
- **CloudWatch Logs** – To monitor Lambda execution

## Create S3 buckets
- Create two S3 buckets
  - image-upload-tiana
  - image-processed-tiana
- Ensure both buckets are in the same region
