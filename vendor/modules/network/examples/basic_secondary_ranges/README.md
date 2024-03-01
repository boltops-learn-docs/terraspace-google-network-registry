<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/basic_secondary_ranges/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Subnet with secondary range

This example configures a VPC network and a subnet with a secondary range.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project\_id | The project ID to host the network in | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| primary\_cidr | Primary CIDR range |
| project\_id | Google Cloud project ID |
| region | Google Cloud region |
| secondary\_cidr | Secondary CIDR range |
| secondary\_cidr\_name | Name of the secondary CIDR range |
| subnetwork\_name | The name of the subnetwork |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
