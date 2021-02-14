# Project 2

## Objectives

- Explore Elastic Cloud Computing & Virtual Private Clouds in AWS
- Play with regulating ports and firewall traffic

## AWS Play Time

- Create a VPC on AWS.
   A VPC , is a Virtual Private Cloud tat AWS provides to manage our instances in a private network.
   To create a VPC on AWS , after logging to AWS educate I have gone to the VPC section and navigated to Start VPC wizard under Your VPC.
   I have initialized the VPC with a single subnet (10.0.0.0/16).
   Attached below is screenshot of the  created VPC.


- Create an 2 EC2 instances.  Utilize an Linux AMI, use only free tier resources.
  An EC2 instance stands for Elastic Compute Cloud instance .It is a web service which provides with a compute server.
  Creating an EC2 instance is usually done in 6 major steps .
  1) Choose an AMI : have selected a free tier Linux Amazon Machine Image x84 64bit (AMI)

  2) Choose Instance type :I have chosen a t2.micro type instance type with 1 vCPU ang 1GB of RAM.

  3) Configure the instance : Made 2 instances(after taking screenshot), selected the above made VPC , assigned a public and private IP. Checked termination protection

  4) Add Storage : 8 GB SSD(GP2)

  5) Add Tags : added tags (key value pair).

  6) Configure Security Group : Used Security group created in VPC (see below section). Uses the required outbound and inbound rules .

  7) Review : Review the created instances


- Utilize Security Groups to lock down inbound cloud traffic
    - Allowed all traffic on all ports within the VPC subnet (10.0.0.0/16)

    - Allowed all traffic on ports 80 AND port 443 from the world (HTTP and HTTPS )

    - Configured All SSH traffic only from MY IP.
