Site-to-Site VPN (AWS managed VPN)
![image](https://github.com/user-attachments/assets/604b5851-22ec-489e-a6b0-c4e1f550523a)
- on-premise -> VPC private subnet
- on-premise
  - software/hardware VPN appliance to your on-premise network
  - VPN should be accessible using a public IP
- AWS-side
  - Virtual Private Gateway (VPG) on VPC
  - Customer Gateway to point the on-premise VPN appliance

AWS VPN CloudHub
- can connect up to 10 Customer Gateway for each VGW
- secure connection
- can be a failover connection between your on-premise locations
