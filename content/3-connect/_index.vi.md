---
title : "Kết nối đến Bastion Host"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Kết nối đến Bastion Host

- Để kết nối đến Windows Remote Desktop server, chúng ta có thể sử dụng một số công cụ, phần mềm hỗ trợ kết nối.

![AWS Elastic Disaster Recovery Workshop](/images/1/0005.png?featherlight=false&width=60pc)

+ Đối với **Windows**:  sử dụng **Remote Desktop Connection**
+ Đối với **MacOS**: sử dụng **[Remote Desktop 10](https://apps.apple.com/us/app/microsoft-remote-desktop-10/id1295203466?mt=12)**
+ Đối với **Linux**: sử dụng **[Remmina](https://remmina.org/)**

Đối với phần **Credentials**, chúng ta sẽ sử dụng:

```
Bastion Host
user = Administrator
password = Adm1nP@s

Linux Hosts
password = SshPass1

```

1. Chúng ta truy cập vào giao diện **EC2**

   - Chọn **MID-Bastion** instance
   - Chọn **Connect**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0001.png?featherlight=false&width=90pc)

2. Để kết nối, chúng ta sẽ chọn **RDP client**

   - Chọn *Connection type** là **Connect using RDP client**
   - Chọn **Download remote desktop file**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0002.png?featherlight=false&width=90pc)

3. Sau khi tải về máy, bạn chọn **Remote Desktop Connection**

   - Chọn **Connect**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0003.png?featherlight=false&width=90pc)

4. Thực hiện điền **password**

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0004.png?featherlight=false&width=90pc)

5. Chọn **Yes** để kết nối

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0005.png?featherlight=false&width=90pc)

6. Hoàn thành kết nối.

![AWS Elastic Disaster Recovery Workshop](/images/2-connect/0006.png?featherlight=false&width=90pc)