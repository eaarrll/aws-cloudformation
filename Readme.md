# Project Title

mm-project

## Getting Started

This template deploys a VPC, with a pair of public and private subnets spread across two ( Zone A, Zone B)  Availabilty Zones. It deploys an Internet Gateway,with a default route on the public subnets. It deploys NAT Gateway (in 2 public AZ), and default routes for them in the private subnets. Creates 2 ec2 instances in Private subnets within a autoscaling group. Creates 2 RDS in Private subnets.


### Usage

Steps on how to load this Cloudformation template:

```
Login to AWS Console
```
```
Go to Cloudformation
```
```
Click "Create Stack"
```
```
Select "Upload a template file"
```
```
Click "Choose file" then select the template from your local
```
```
Click Next
```
```
Enter Stack name and parameters for the DB then click Next
```
```
Click Next
```
```
Lastly, click "Create Stack"
```

