<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/firewall_logging/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

#  Firewall Rule

This example configures a single firewall rule with firewall logging enabled.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project\_id | The project ID to host the network in | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| name | The name of the firewall rule being created |
| network\_name | The name of the VPC network where the firewall rule will be applied |
| project\_id | Google Cloud project ID |
| rule\_self\_link | The URI of the firewall rule  being created |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
