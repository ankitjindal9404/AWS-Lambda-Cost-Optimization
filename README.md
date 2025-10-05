# AWS Cloud Cost Optimization - Identify and Delete Unused EBS Snapshots

I created AWS Lambda function identifies EBS snapshots that are no longer associated with any EBS volume and deletes them to help save on storage costs.

Before using this Lambda function, ensure that:

## Prerequisites

- You have an active AWS account.
- AWS Lambda permissions to manage EBS snapshots and EC2 instances are granted.
- An IAM role is created for Lambda with permissions to delete snapshots and describe EC2 instances and EBS volumes.
