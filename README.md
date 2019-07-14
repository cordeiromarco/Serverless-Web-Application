# Serverless-Web-Application
Build a Serverless Web Application with AWS Lambda, Amazon API Gateway, Amazon S3, Amazon DynamoDB, and Amazon Cognito


 http://wildrydes-cordeirom.s3-website-us-west-2.amazonaws.com
 
 S3 Police
 
 {
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::wildrydes-cordeirom/*"
        }
    ]
}
