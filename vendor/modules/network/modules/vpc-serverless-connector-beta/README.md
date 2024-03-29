<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-network-registry/blob/master/vendor/modules/network/modules/vpc-serverless-connector-beta/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraform VPC Serverless Connector Beta

This submodule is part of the the `terraform-google-network` module. It creates the vpc serverless connector using the beta components available.

It supports creating:

- serverless connector
- serverless vpc access connector

## Usage

Basic usage of this submodule is as follows:

```hcl
module "serverless-connector" {
  source     = "terraform-google-modules/network/google//modules/vpc-serverless-connector-beta"
  project_id = <PROJECT ID>
  vpc_connectors = [{
    name            = "central-serverless"
    region          = "us-central1"
    subnet_name     = "<SUBNET NAME>"
    host_project_id = "<HOST PROJECT ID>"
    machine_type    = "e2-standard-4"
    min_instances   = 2
    max_instances   = 3
    max_throughput  = 300
  }]
}
```

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project\_id | Project in which the vpc connector will be deployed. | `string` | n/a | yes |
| vpc\_connectors | List of VPC serverless connectors. | `list(map(string))` | `[]` | no |

## Outputs

| Name | Description |
|------|-------------|
| connector\_ids | VPC serverless connector ID. |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
