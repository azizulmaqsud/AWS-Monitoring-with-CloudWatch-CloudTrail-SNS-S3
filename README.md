# Monitor-AWS-with-CloudWatch-CloudTrail-SNS-S3
- How you can generate a customized alarm and that alarm can be notified using an email along with using the AWS SNS Service?
- How the automated email is sent to a particular user or a particular subscriber when there is a particular event that happens in the AWS?
- And, how those events have been tracked in conjunction with using Amazon Cloud trail and Amazon CloudWatch?
  
# Email Notification of CloudWatch alarms using CloudTrail CloudWatch log groups
- Set up Amazon CloudTrail first, and that cloud trail will have the log groups to push to CloudWatch logs.
- On top of the Cloudwatch log groups, create a metric filter to filter a particular event from the Cloudwatch logs
- Third, to protect the collection container which collects a set of logs or watch log groups, configure a metal filter under the CloudWatch log group. It will filter out the event that you care about. And that will be used by another feature underneath of your watch called an alarm
- Configure SNS. SNS has the flexibility that you can opt-in that is subscribe or unsubscribe 
- Whenever there is an alarm generated, that will be sent to the email address.
- Metric filter occurs for a particular period of time and a particular number of files
- Then the notifications sent an email
- email services provided by SNS

# Monitoring Overview
 - Metrics gives you a complete picture
 - CloudTrail Dashboard collects the trails
 - S3 bucket stores two objects: CloudTrail & CloudTrail-Digest

# AWS-Monitoring-with-CloudWatch-CloudTrail-SNS-S3
