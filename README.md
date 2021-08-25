# code-20210825-ShubhamAggarwal


CloudFormation template that deploys a lamda function which listens
to SQS Queue which further subscribe to SNS Topic and it recieves the
messages comming from that and sends the message to S3 bucket with
proper access policy and roles.
Also the verisoning and lifecycle of s3 bucket is maintained in the 
template as well.





