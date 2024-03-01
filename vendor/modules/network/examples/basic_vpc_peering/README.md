<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/basic_vpc_peering/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# VPC network peering

This example configures VPC network peering.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| local\_network | Self link to the local network. | `string` | n/a | yes |
| peer\_network | Self link to the peer network. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| local\_network | The local network peering information |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
