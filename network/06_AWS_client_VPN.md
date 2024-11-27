AWS Client VPN
- connect from your computer using OpenVPN to your private network in AWS and on-premise
- this connection allows:
  - connection to private subnet using private IP
  - Client VPN -> private VPC(A) -> peering (Transit Gateway) -> private VPC(B)
  - Client VPN -> private VPC(A) -> S2S VPN -> on-premise
  - Client VPN -> public Subnet -> IGW -> Internet
  - Client VPN -> private Subnet -> public Subnet -> IGW -> Internet
