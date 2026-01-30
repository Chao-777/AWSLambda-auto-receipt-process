# AWSLambda-auto-receipt-process
This project implements a serverless receipt processing system on AWS. When a receipt image is uploaded to Amazon S3, an AWS Lambda function is triggered to extract receipt data using Amazon Textract. The extracted information is stored in Amazon DynamoDB, and a formatted email notification is sent via Amazon SES.
