# Adesayoariyo_smartshop_ lita project
Creating and deploying a reliable scalable EC2 instance for smartshop, a mid-sized retail company. It also documents the process of deploying an Apache web server on it.
The mid-sized retail launching an online store helps the company grow and also makes shopping easier for customers. Below are the sample images and videos that shows online shopping.
![WhatsApp Image 2024-12-12 at 20 33 30_2fdfe572](https://github.com/user-attachments/assets/55ccf2de-298f-44c5-9fbc-7734cf87652d)
![WhatsApp Image 2024-12-12 at 20 33 30_6a01857a](https://github.com/user-attachments/assets/569214e2-4732-4b74-bb77-b03ecaa8ec4c)


https://github.com/user-attachments/assets/10ce159a-094f-4a49-9e3e-b6d86d876024

## Configuring NACL for smartshop
The NACL were attached to the created public and private subnets. Inbound and Outbound rules were also defined. Allowing  HTTP(80) and SSH (22)

### setting up Nacl Inbound rules
![Nacl inbound rules](https://github.com/user-attachments/assets/ab3094ab-2ad7-4bc3-b9ec-5218ebd6622c)


### setting up Nacl outbound rules
The Nacls were attached to 
![Nacl outbound rule](https://github.com/user-attachments/assets/186d8362-d510-44ee-aaac-db477a0d937d)

### creation of security group
Security groups enables controlling of traffic based on IP address and port number. It also enables you to define inbound and outbound rules to specify whioch traffic is allowed to flow in and out of your resources.The security group created for smartshopis to control inbound and outbound traffic to their ec2 instances. It allows and restrict the following commands.
Allowing HTTP(Port80) and HTTPS (Port 443) traffic from the internet
Restricting SSH(Port 22) access to smartshop IP adresss only.
Below is the screenshot of the security group created for smartshop


![Security Group](https://github.com/user-attachments/assets/1985e7a6-e0db-49e7-802c-40692e883cb6)



### creating ec2 instance for smart shop with already existing vpc and subnets
 Below is the screenshot of the EC2 instance created for smartshop
 ![ec2 instance 1](https://github.com/user-attachments/assets/0a601212-0713-47ab-bc39-39e4ad382d9b)

 ![ec2 instance 2](https://github.com/user-attachments/assets/382dff62-3b74-4c58-976b-8c8afe3d1029)
 ![ec2 instance 3](https://github.com/user-attachments/assets/f03c7324-e5ee-4263-85e9-9f700dcc3eac)

 

 
 ### SSH into Apache web server
 The Apache helps to host the EC2 instance
Below is the screenshot of the completed Apache web server

![Apache](https://github.com/user-attachments/assets/84c9e75d-cf71-496e-af6a-cff86c9b3b8d)


