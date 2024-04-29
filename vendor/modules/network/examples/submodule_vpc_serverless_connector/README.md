<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/submodule_vpc_serverless_connector/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# VPC Serverless Connector Beta

This example deploys a single vpc serverless connector in the us-central1 region.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project\_id | Project in which the vpc connector will be deployed. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| connector\_ids | ID of the VPC serverless connector that was deployed. |
| project\_id | The ID of the Google Cloud project being used |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
