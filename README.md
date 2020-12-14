# terraform 
###  This module is used to create ASG +  ELB. 
####  Please Use below code to create ASG

```
module "webapp" {
  source           = "shamal112mn/asg/aws"
  region           = "us-east-1"
  max_size         = "1"
  min_size         = "1"
  desired_capacity = "1"
  image_owner      = "137112412989"
  instance_type    = "c5.large"
}

```
