# Terraflops Terraform Module
 
### Module name

Creates a Sumologic (Hosted) Collector.

#### Example usage

```hcl-terraform
module "collector" {
  source = "git::https://github.com/TerraFlops/sumo-logic-collector?ref=v1.0"
  
  name = "sumologic-collector"
  description = "A collector for sumologic"
}

```

