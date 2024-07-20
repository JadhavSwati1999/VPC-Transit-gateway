# VPC-Transit-gateway
Virtual-private-cloud-transit-gateway

### **What is a transit gateway?**

## A *transit gateway* is a network transit hub that you can use to interconnect your virtual private clouds (VPCs) and on-premises networks.

## Get Started:

1. Create three VPCs assign them names as (VPC1, VPC2, VPC3 )


 

Create IGW 

- Create three IGW  for each VPC to provide a direct internet connection to the VPC.
- One IGW is attached to only one VPC.


- Create three subnets each in different VPCs



- Create three route tables for each VPC as (RT-vpc1,RT-vpc2, RT-vpc3)


- Create three instances in different VPCs as (vpc1, vpc2, vpc3)


- Create a transit gateway from the VPC dashboard
- Click on Create Transit Gateway.



- Assigned a name to the transit gateway as (tg-vpc1-vpc2-vpc3)



Edit routes tables by assigning the CIDR range of the VPC.

- In RT-vpc1 you need to edit the route and add the CIDR of the other two VPCs (VPC2, VPC3)
- In RT-vpc2 you need to edit  the route and add the CIDR of the other two VPCs (VPC1, VPC3)
- In RT-vpc3 you need to edit the route and add the CIDR of the other two VPCs (VPC1, VPC2)


- Try connecting the instances that are created in the different VPC. ()


### Summary:

You can successfully create and configure a transit gateway in AWS to simplify and manage your network architecture effectively.