# Alerts-to-Microsoft-Teams-using-AWS-SNS
Automating EC2 State Change Alerts to Microsoft Teams using AWS SNS + Lambda


EC2 instance changes state
        ↓
EventBridge rule detects it
        ↓
EventBridge sends event to SNS topic
        ↓
SNS triggers Lambda
        ↓
Lambda formats message and posts to Teams


