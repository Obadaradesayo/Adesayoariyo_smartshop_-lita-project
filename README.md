# Adesayoariyo_smartshop_ lita project
creating and deploying a reliable scalable ec2 instance for smartshop, a mid-sized retail company. It also documents the process of deploying an Apache web server on it.
### setting up Nacl Inbound rules
![Nacl inbound rules](https://github.com/user-attachments/assets/ab3094ab-2ad7-4bc3-b9ec-5218ebd6622c)


### setting up Nacl outbound rules
The Nacls were attached to 
![Nacl outbound rule](https://github.com/user-attachments/assets/186d8362-d510-44ee-aaac-db477a0d937d)

### creation of security group
security groups enables controlling of traffic based on IP address and port number. It also enables you to define inbound and outbound rules to specify whioch traffic is allowed to flow in and out of your resources.The security group created for smartshopis to control inbound and outbound traffic to their ec2 instances. It allows and restrict the following commands.
Allowing HTTP(Port80) and HTTPS (Port 443) traffic from the internet
Restricting SSH(Port 22) access to smartshop IP adresss only.
Below is the screenshot of the security group created for smartshop
!{security group detail}(/Security Group.png)




### creating ec2 instance for smart shop with already existing vpc and subnets
 Below is the screenshot of the ec2 instance created for smartshop
 !{ec2 instance}(/ec2 instance 1.jpg)
 !{ec2 instance](/ec2 instance 2.jpg)
 !{ec2 instance}(/ec2 instance 3.jpg) 
 ### SSH into Apache web server
 The Apache helps to host the ec2 instance
Below is the screenshot of the completed Apache web server
!{Apache}(Apache.jpg)

