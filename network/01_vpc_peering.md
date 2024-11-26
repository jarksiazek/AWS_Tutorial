VPC Peering

![image](https://github.com/user-attachments/assets/1a56893a-b488-4bb8-a11a-02aef72d2617)

- helps to connect VPCs
- must not have overlapping CIDR
- is not transitive (each VPC connection needs to communicate with seperate VPC peering)
- each VPC route table need to be know where to go

- inter-region, cross-account
- SG (works with cross-account)

- longest prefix match
- VPC invalid configuration
  - overlapping
  - no transitive VPC Peering
  
