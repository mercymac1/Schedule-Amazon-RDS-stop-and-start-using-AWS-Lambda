# Schedule-Amazon-RDS-stop-and-start-using-AWS-Lambda
In a typical development environment, dev and test databases are mostly utilised for 8 hours a day and often sit idle afterwards. Yet, you're still paying for compute and storage during this downtime. This solution uses AWS Lambda function to stop and start the idle databases with specific tags to save on compute costs.

# How to Set Up a Lambda Function with Node.js 18
1. Create a Lambda function using Node.js 18.
2. Add AWS-SDK package as a layer to support your Lambda code.
3. Set environment variables in Lambda:
   DB_CLUSTER_IDENTIFIER = your RDS identifier name.
