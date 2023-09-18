# Description:  
This template deploys a VPC, with a three public and private subnets (if selected), spread
  across three Availability Zones. It deploys an internet gateway, with a default
  route on the public subnets. If selected, it deploys a pair of NAT gateways (one in each AZ),
  and default routes for them in the private subnets. It also creates and instance and its associated
  security group in one of the public subnets.
