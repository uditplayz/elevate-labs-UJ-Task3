Made a new VPC called my-first-vpc in AWS for Task 3 @ Elevate labs
<br />
Set the VPC CIDR to 10.0.0.0/16. <br />
Made two subnets:
<br /><br />
Public subnet: 10.0.1.0/24 <br />
Private subnet: 10.0.2.0/24
<br />
Turned on automatic public IP for public subnet (so it gets internet).<br />
Kept auto-assign off for private subnet (no internet).<br />
Set up two route tables:<br />

Public route table: Links public subnet to internet (has a route for 0.0.0.0/0 to IGW). <br />
<br />
Private route table: Only does local VPC traffic (no internet route).

### Info
Region: eu-north-1

Total subnets: 2

Internet access: Only public subnet

### Screenshots
VPC Dashboard:
<img width="1920" height="1080" alt="vpc-dash" src="https://github.com/user-attachments/assets/3134c2f2-73ab-454f-9951-9ed59f2625cc" />

VPC Details:
<img width="1920" height="1080" alt="vpc cidr" src="https://github.com/user-attachments/assets/81d153c4-ddb3-4a38-bd0f-a14e0716cb6b" />

All Route Tables:
<img width="1920" height="1080" alt="route-tables" src="https://github.com/user-attachments/assets/78204eed-f2be-4701-9dd8-a0d669bdc6ff" />

Public Route Table:
<img width="1920" height="1080" alt="public-route" src="https://github.com/user-attachments/assets/639a30d1-0004-4714-81ad-7cbd8c357ee2" />

Private Route Table:
<img width="1920" height="1080" alt="private-route" src="https://github.com/user-attachments/assets/4d2a6eae-9bf3-445b-a027-a58f1b05698a" />

Internet Gateways:
<img width="1920" height="1080" alt="internet-gate" src="https://github.com/user-attachments/assets/a9210e1f-c3cf-4d62-bc65-53a2f288122e" />

Subnets List:
<img width="1920" height="1080" alt="subnets" src="https://github.com/user-attachments/assets/dcda4f15-e3dd-4f8b-b008-6e630132437d" />
