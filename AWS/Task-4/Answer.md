## Launch EC2 Instance:

1. Select Ubuntu 20.04 AMI.
2. Instance type: t2.micro (Free Tier).
3. Select MyVPC → Public Subnet.
4. Security Group Configuration:

  Allow SSH (22) from My IP.
  Allow HTTP (80) from Anywhere.

## SSH into the instance:

```ssh -i my-key.pem ubuntu@ec2-public-ip```

## Install Apache:
```bash
sudo apt update
sudo apt install apache2 -y
echo "<h1>Hello AWS</h1>" > /var/www/html/index.html