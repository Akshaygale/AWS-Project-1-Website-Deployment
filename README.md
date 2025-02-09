# AWS-Project-1-Website-Deployment

Here in this project we are using varios AWS services like VPC (SUBNET, ROUTE TABLE, INTEERNET GATEWAY, NAT GATWAY,); LAUNCH TEMPLATE (can use AWS AMI); LOAD BALANCER; TARGET GROUP; ASG; VPC FLOW LOGS; S3; SNS; CLOUDFRONT; ROUTE 53.

STEP 1:

Create VPC, then create Subnet (public & private), then Internet Gatway and attach it with the VPC, then create Route Table (public) and associate with subnet(public) and edit the Route with Internet Gateway.

Create NAT gateway- select private subnet, allocate elastic Ip. after that create Route Table (private) and associate with subnet(private) and edit the Route with NAT Gateway.

STEP 2:
Crate SG 
then create launch template
traget group,
load balancer, 
ASG

SNS create topic and add subscription

**VPC**                                                                                                                                                                                                              
**SG - HTTP ANYWHRE**

**SNS**

**ASG - AZ-PUBLIC ONY && TARGET UTLIZAION**

**CLODFRONT - ORIGIN(LOAD BAANCER)  HTTP ONLY  VIEWER PROTOCAL- PRDIRECT HTTP TO HTTPS  CACHE POLICY- CACHING OPTIMIZED; ALL VIEWERS WAF-NO; CSTOME DOMAIN- rgclass.site**

**ROUTE 53 - CREATED HOSTED;   CREATE RECORD- SIMPLE ROTING; SIMPLE RECORD- A-ROUTE TRAFFIC TO IPV4;  RECORD TYPE- ALIAS TO CLOD FRONT DISTRUBTION/LOAD BALANCER**

**CLODWATCH - ROUTE 53 MATRICS**


























