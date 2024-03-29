<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/examples/multi_vpc/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Multiple Networks

This example configures a host network project with two separate networks.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| network\_01\_name | The name of the first VPC network being created | `any` | n/a | yes |
| network\_02\_name | The name of the second VPC network being created | `any` | n/a | yes |
| project\_id | The project ID to host the network in | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| network\_01\_name | The name of the VPC network-01 |
| network\_01\_routes | The routes associated with network-01 |
| network\_01\_self\_link | The URI of the VPC network-01 |
| network\_01\_subnets | The names of the subnets being created on network-01 |
| network\_01\_subnets\_flow\_logs | Whether the subnets will have VPC flow logs enabled |
| network\_01\_subnets\_ips | The IP and cidrs of the subnets being created on network-01 |
| network\_01\_subnets\_private\_access | Whether the subnets will have access to Google API's without a public IP on network-01 |
| network\_01\_subnets\_regions | The region where the subnets will be created on network-01 |
| network\_01\_subnets\_secondary\_ranges | The secondary ranges associated with these subnets on network-01 |
| network\_02\_name | The name of the VPC network-02 |
| network\_02\_routes | The routes associated with network-02 |
| network\_02\_self\_link | The URI of the VPC network-02 |
| network\_02\_subnets | The names of the subnets being created on network-02 |
| network\_02\_subnets\_flow\_logs | Whether the subnets will have VPC flow logs enabled |
| network\_02\_subnets\_ips | The IP and cidrs of the subnets being created on network-02 |
| network\_02\_subnets\_private\_access | Whether the subnets will have access to Google API's without a public IP on network-02 |
| network\_02\_subnets\_regions | The region where the subnets will be created on network-02 |
| network\_02\_subnets\_secondary\_ranges | The secondary ranges associated with these subnets on network-02 |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
