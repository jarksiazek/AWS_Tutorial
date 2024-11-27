PrivateLink(VPC Enpoint Service)
- most secure and scable way to expose a service to 1000s of VPC (own or other accounts)
- does not require VPC peering, IG, NAT, route table
- VPC(A) -> ENI(A) -> PrivateLink -> Network LoadBalancer (Service VPC B)
- NLB is in multi AZ, the ENI is in multi AZ, fault tolerant solution

PrivateLink for S3 with DX
- on-premise -> DX -> Private VIF -> PrivateLink -> Interface VPC Endpoint -> S3

PrivateLink VPC Peering
- VPC(A) -> VPC Peering -> VPC(B) -> Endpoint interface -> S3
