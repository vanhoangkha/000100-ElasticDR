---
title : "Connect to the Bastion Host"
date: 2024-01-01
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Connect to Bastion Host

- To connect to the Windows Remote Desktop server, we can use many tools and software to support the connection.

![AWS Elastic Disaster Recovery Workshop](/images/1/0005.png?featherlight=false&width=60pc)

+ For **Windows**: use **Remote Desktop Connection**
+ For **MacOS**: use **[Remote Desktop 10](https://apps.apple.com/us/app/microsoft-remote-desktop-10/id1295203466?mt=12)**
+ For **Linux**: use **[Remmina](https://remmina.org/)**

For the **Credentials** part, we will use:

```
Bastion Host
user = Administrator
password = Adm1nP@s

Linux Hosts
password=SshPass1

```

1. We access the **EC2** interface

   - Select **MID-Bastion** instance
   - Select **Connect**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0001.png?featherlight=false&width=90pc)

2. To connect, we will choose **RDP client**

   - Select *Connection type** as **Connect using RDP client**
   - Select **Download remote desktop file**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0002.png?featherlight=false&width=90pc)

3. After downloading, select **Remote Desktop Connection**

   - Select **Connect**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0003.png?featherlight=false&width=90pc)

4. Fill in **Password**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0004.png?featherlight=false&width=90pc)

5. Select **Yes** to connect

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0005.png?featherlight=false&width=90pc)

6. Complete the connection.

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0006.png?featherlight=false&width=90pc)