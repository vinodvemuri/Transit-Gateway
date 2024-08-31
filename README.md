TRANSIT GATEWAY AND VPC PEERING: 
Transit Gateway is a network transit hub that interconnects attachments to (vpcs and Vpns) with the same AWs acccount or accors AWS Accounts.
-
Step1: Go to the vpcs and create the two vpcs 
  -> name: VPC1
  -> IPv4 CIDR :10.0.0.0/16
  Same one more create: 
  -> Name: VPC2
  -> IPV4: 20.0.0.0/16
  NOTE: Automatically Attached to route tables.
  
Step2:create the subnets two
   -> Name: Vpc1sub
   -> Subnet CIDR: 10.0.0.0/28
And one more Subnet create:
   -> Name: Vpc2sub
   -> Subnet CIDR:  20.0.0.0/27

   
