Direct Connect
- a dedicated private connection from a remote network to a VPC
- connection between on-premise and AWS
- more expensive than running a VPN solution
- private access to AWS services though VIF
- bypass ISP, reduce network cost, increase bandwidth and stability
- not redundant by default (must set up a failover DX or VPN)

- VPC -> Virtual Private Gateway -> AWS Direct Connect Location -> Customer Network

Virtual Interface (VIF)
- public VIF - connect to public AWS Endpoint (S3, EC2, anything AWS)
- private VIF - connect to resources in your VPC (EC2 instanes, ALB) - VPC interface endpoints can be accessed though Private VIF
- Transit Virtual Interface - connect to reosources in a VPC using a Transit Gateway
  
