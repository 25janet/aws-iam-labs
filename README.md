# aws-iam-labs
# AWS IAM Lab – User & Group Permissions

This project is part of my AWS Academy Cloud Foundations course.  
The lab demonstrates how to manage **IAM users and groups**, and test their permissions across AWS services.

## Lab Objectives
- Add users to IAM groups with different access policies
- Test permissions for S3 and EC2
- Apply the principle of least privilege

## Groups & Policies
- **S3-Support** → AmazonS3ReadOnlyAccess  
- **EC2-Support** → AmazonEC2ReadOnlyAccess  
- **EC2-Admin** → Custom EC2-Admin-Policy  

## Verification
- **user-1**: Can view S3 buckets, but cannot access EC2  
- **user-2**: Can view EC2 instances (read-only), but cannot access S3  
- **user-3**: Full EC2 admin rights, able to stop/start instances  

## Key Learnings
- IAM groups simplify permission management  
- Testing user access ensures least privilege is enforced  
- Security best practice: always give the minimum required permissions
