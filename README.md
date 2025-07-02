# 🚀 Deployment of a Basic Web Application in a Customised AWS VPC

This project demonstrates how to deploy a static website on an Amazon EC2 instance within a **custom VPC**, using **Apache Web Server (httpd)** on Amazon Linux.

## 📘 Project Overview

This was my **first hands-on AWS deployment**, where I manually configured infrastructure and deployed a website using the Linux terminal.

## 🛠️ Technologies Used
- Amazon VPC (Virtual Private Cloud)
- Amazon EC2 (Elastic Compute Cloud)
- Apache HTTP Server
- SSH Client
- Linux CLI
- Security Groups

## 🧾 Project Steps

1. ✅ Created a **custom VPC** with subnet configuration
2. ✅ Launched an **EC2 instance** with public IP in that VPC
3. ✅ Connected to EC2 via **SSH** using key pair
4. ✅ Installed Apache server using `yum install httpd -y`
5. ✅ Deployed a static HTML template (from [Tooplate.com](https://www.tooplate.com/))
6. ✅ Moved files to `/var/www/html`
7. ✅ Allowed port 80 in EC2's security group
8. ✅ Accessed the app via public IP

## 🖼️ Screenshots

All screenshots of the deployment process can be found in the [`/screenshots`](./screenshots) folder.

## 💻 Linux Commands Used

Refer to the [`linux-commands.txt`](./linux-commands.txt) file for all shell commands executed during the deployment.

## 📎 Useful Links

- [Tooplate Templates](https://www.tooplate.com/)
- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Apache HTTP Server](https://httpd.apache.org/)

## 🙌 Outcome

This project helped me gain hands-on experience in:
- Networking (VPC, Subnets, SGs)
- EC2 Instance Management
- Linux Commands and Permissions
- Static Web Hosting on AWS

#️⃣ Tags: `#AWS` `#EC2` `#VPC` `#CloudProject` `#Apache` `#Linux` `#WebDeployment`
