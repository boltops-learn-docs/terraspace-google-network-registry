<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/private_service_connect_google_apis/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Simple shared VPC Project

This example:

* Enables shared VPC on a host project
* Attaches a service project
* Reserves an internal IP address in a subnet of a Shared VPC network
* Creates a VM instance

The IP address configuration object is created in the service
project. Its value can come from the range of available addresses in
the chosen shared subnet, or you can specify an address.


<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project | The Google Cloud project ID | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| forwarding\_rule | Name of the forwarding rule |
| ip\_address | The internal IP address |
| ip\_address\_name | The name of the internal IP address |
| network | Name of the VPC network |
| project | Google Cloud project ID |
| subnet\_ip\_range | Subnet IP range |
| subnetwork | Name of the subnetwork |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
