# terraform
IaC Terraform Scripts

1) Create s3 bucket go to s3 > terraform init > terraform plan > terrafrom apply.

2) To cretae EC2 instance go to EC2  > terraform init > terraform plan > terrafrom apply.

3) For creting a lambda function go to Lambda > terraform init > terraform plan > terrafrom apply.

To distroy the resources you have created 

1) terraform plan -destroy -out="dest.plan"

2) terraform apply dest.plan

Thank You..!
