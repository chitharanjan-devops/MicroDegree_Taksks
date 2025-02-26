## Create IAM User:

1. Go to IAM → Users → Add User.

2. Enter "developer_user".

3. Select Access Key - Programmatic access.

4. Click Next.

5. Assign EC2 Read-Only Permissions:

6. Attach the "AmazonEC2ReadOnlyAccess" policy.

7. Click Create User.

## Store Access Keys Securely:

1. Download .csv file.

2. Store it in AWS Secrets Manager or a secure location.

## Verification:

1. Login as developer_user.

2. Try running aws ec2 start-instances --instance-ids i-1234567890abcdef0 (this should fail).

3. Try listing instances: aws ec2 describe-instances (this should work).
