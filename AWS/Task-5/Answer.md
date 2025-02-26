## Create an ALB

Target Group → Register EC2 instances.
Configure Listeners to forward HTTP traffic.

## Set Up Auto Scaling Group

Minimum: 1 instance, Maximum: 3.
Configure Scaling Policy (CPU > 60%).

## Attach CloudWatch Alarm

Trigger Auto Scaling when CPU exceeds threshold.