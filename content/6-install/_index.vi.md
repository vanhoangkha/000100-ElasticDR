---
title : "Cài đặt Agent "
date :  "`r Sys.Date()`" 
weight : 6
chapter : false
pre : " <b> 6. </b> "
---

#### Cài đặt Agent

1. Trong giao diện **Bastion Host**

   - Chọn **Putty**
   - Chọn **wordpress-web**
   - Chọn **Open**

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0001.png?featherlight=false&width=90pc)

2. Chúng ta sẽ thực hiện đăng nhập với password như phần kết nối 

```
Bastion Host
user = Administrator
password = Adm1nP@s

Linux Hosts
password = SshPass1
```

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0002.png?featherlight=false&width=90pc)

3. Đăng nhập thành công.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0003.png?featherlight=false&width=90pc)

4. Sau khi đăng nhập thành công, chúng ta sẽ thực hiện cài đặt **Agent**

```
wget -O ./aws-replication-installer-init.py https://aws-elastic-disaster-recovery-us-west-2.s3.amazonaws.com/latest/linux/aws-replication-installer-init.py
```

   - Sau đó, chúng ta sẽ thực hiện lệnh 

```
sudo python3 aws-replication-installer-init.py
```

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0004.png?featherlight=false&width=90pc)

5. Thực hiện cấu hình 

   - AWS Region Name
   - AWS Access Key ID
   - AWS Secret Access Key
   - Đối với **Choose the disks you want to replicate**, chọn **Enter**


![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0005.png?featherlight=false&width=90pc)

6. Chúng ta sẽ thực hiện các bước tương tự đối với phần **database** server.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0006.png?featherlight=false&width=90pc)

7. Trở lại trang **DRS source server** xem quá trình **initial sync**


![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0007.png?featherlight=false&width=90pc)

8. Cả 2 **DRS source server**

   - Create security groups
   - Launch replication server
   - Boot replication server
   - Authenticate with service
   - Download replication software
   - Create staging disks
   - Attach staging disks
   - Pair replication server with Agent
   - Connect agent with replication server
   - Start data transfer

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0008.png?featherlight=false&width=90pc)

9. Chúng ta sẽ chọn 1 **DRS source server** để xem chi tiết.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0009.png?featherlight=false&width=90pc)

10. Bạn sẽ phải đợi khoảng 10 phút, khi hoàn thành **100%**

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/00010.png?featherlight=false&width=90pc)

11. Sau đó khoảng 1 phút, bạn sẽ quan sát thấy trạng thái **Reaady for recovery** là **Ready** và **Data replicatio status** là **Healthy**

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/00011.png?featherlight=false&width=90pc)


