# AWS CloudWatch Monitoring and Alerts Setup

## Dashboard
Created a CloudWatch dashboard with `CallCount` metric to visualize usage.

## Alarm
Configured an alarm named `UsageTooHighAlarm`:
- Metric: CallCount
- Threshold: > 3 within 5 minutes
- Notifications: Sent via SNS to email

## Screenshots
Included screenshots:
- Dashboard view
- Alarm configuration
