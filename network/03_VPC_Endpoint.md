VPC Endpoint
- allows to connect to AWS Services using a private network
- scales horizontally and is redundant
- VPC Endpoint Gateway (Only for S3 and DynamoDB)
- VPC Endpoint Interface - ENI (elastic network interface) (all except DynamoDB)
VPC Enpoint Gateway
- only S3 and DynamoDB
- one Gateway per VPC
- update route table entries
- DNS resolution must be enabled in the VPC
- the same public hostname for S3
- cannot be extended out of a VPC (VPN, DX, TGW, peering)
VPC Endpoint Interface
- ENI must be provisioned (a private endpoint interface hostname)
- ENI can leverage SG for security
- private DNS (setting when you create the endpoint) (enable DNS hostnames, enable DNS support)
- interface can be accessed from Direct Connect and Site-to-Site VPN
  
