# Terraform_code

After exploring many of the AWS services, here's my terraform code to build and run IaC.

I tried my best to understand load balancing, autoscaling groups,IAM users.

Concepts like creating multiple instances,using lopps , creating multiple IAM users etc are implemented in the above terraform files.

## Terraform hierarchy

I tried to understand the hierarchy in terraform files, I created files with:
-main.tf
-terraform.tfvars
-variables.tf
-output.tf
Containing specific codes , I experimented with several conventions and understood how these work in a workspace.

## Terraform commands

Few commands used to plan and run terraform:

```
$terraform init
$terraform plan
$terraform apply
$terraform destroy
```

## End result

Infrastructure is built according to the code written in terraform files. This can be verified by cross checking with AWS console.
