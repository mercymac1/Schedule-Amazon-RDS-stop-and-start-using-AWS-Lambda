# Schedule-Amazon-RDS-stop-and-start-using-AWS-Lambda
In a typical development environment, dev and test databases are mostly utilised for 8 hours a day and often sit idle afterwards. Yet, you're still paying for compute and storage during this downtime. This solution uses AWS Lambda function to stop and start the idle databases with specific tags to save on compute costs.

# Steps to do this
- Create Lambda Function With Nodejs 18 version
- Use AWS-SDK package as a layers features to support this lambda function code
- Configure Lambda Environment Varialbes for DB_CLUSTER_IDENTIFIER = your rds identifier name
