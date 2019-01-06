# terraform-aws-ecr

A terraform module to create a container registry (ECR - Elastic Container Registry) in AWS

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| name | The name of the registry | string | - | yes |
| region | The region to create your registry in. | string | - | yes |

## Outputs

| Name | Description |
|------|-------------|
| ecr_arn |  |
| ecr_host |  |
| ecr_repo_name |  |
| ecr_repository_url |  |
�