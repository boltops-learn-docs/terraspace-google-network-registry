<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/packet_mirroring/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

#  Packet Mirroring

This example configures a packet mirroring policy.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| network | The network's self-link | `string` | n/a | yes |
| project\_id | The Google Cloud project ID | `string` | n/a | yes |
| subnet | The subnet's self-link | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| collector\_ilb | The internal load balancer |
| instance | The VM instance |
| packet\_mirror | The name of the packet mirroring policy |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
