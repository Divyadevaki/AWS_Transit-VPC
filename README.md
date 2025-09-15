# AWS_Transit-VPC
Documentation for Creating Transit VPC Setup

📝Transit Gateway
•	Implementing Three-Tier design that separates Web-Tier, App-Tier and DB-Tier using EC2, ALB.

•	Transit Gateway in AWS is used to connect multiple VPC connections together

• It acts like a central hub to connect multiple VPC.

• Transit Gateway simplifies the network management for large-scale environments by centralizing connectivity.

• TGW routes traffic between all attached VPCs and on-premises networks automatically.

• Instead of creating peering connections between every VPC (which becomes more complex when number VPC increased), TGW is best option for large-scale environment.
