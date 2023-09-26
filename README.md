# Getting Started With Cloudzap

## Terraform Install with Arkade
```
curl -sLS https://get.arkade.dev | sudo sh
arkade get terraform
export PATH=$PATH:$HOME/.arkade/bin/
```

## Deploying Infrastructure from Terraform
Note: Must have environment variables set up for 
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY

```
terraform init
terraform apply
```
