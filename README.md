To set up the infrastructure , used AWS CloudFormation template. 

The stack included : A VPC and the associated networking resources, including a subnet, a security group, 
an internet gateway,  and a route table. An Amazon EC2 instance that's launched into the subnet in the VPC. An Amazon SNS topic. Two AWS Lambda functions, these functions 
received messages that are published to the Amazon SNS topic, and they logged events in CloudWatch Logs. Amazon CloudWatch metrics and logs. An IAM role that allows 
the Amazon EC2 instance to use Amazon SNS, and an IAM role that allows the Lambda functions to write to CloudWatch logs. 

Created an Amazon VPC Endpoint for Amazon SNS,to connect the VPC to Amazon SNS.

![image](https://user-images.githubusercontent.com/110668073/230710262-d5f831b2-8bd5-499b-ac9c-dbc7832a1955.png)


![image](https://user-images.githubusercontent.com/110668073/230710232-f12d99d1-72f3-48ae-9658-4ca7bdb68237.png)

![image](https://user-images.githubusercontent.com/110668073/230710248-c9baa378-966f-42dd-b72f-2a94a6cc94cc.png)
