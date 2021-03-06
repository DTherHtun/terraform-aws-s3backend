# S3 Backend Module
This module will deploy an S3 remote backend for Terraform

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| terraform | ~> 0.12 |
| aws | ~> 2.19 |
| random | ~> 2.1 |

## Providers

| Name | Version |
|------|---------|
| aws | ~> 2.19 |
| random | ~> 2.1 |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| force\_destroy\_state | Force destroy the s3 bucket containing state files? | `bool` | `true` | no |
| namespace | The project namespace to use for unique resource naming | `string` | `"s3backend"` | no |
| principal\_arn | AWS principal arn allowed to assume the IAM role | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| config | n/a |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
