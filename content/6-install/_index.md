---
title : "Installing the Agent"
date: 2024-01-01
weight : 6
chapter : false
pre : " <b> 6. </b> "
---

#### Install Agent

1. In the **Bastion Host** interface

   - Select **Putty**
   - Select **wordpress-web**
   - Select **Open**

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0001.png?featherlight=false&width=90pc)

2. We will perform login with password as the connection part

```
Bastion Host
user = Administrator
password = Adm1nP@s

Linux Hosts
password=SshPass1
```

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0002.png?featherlight=false&width=90pc)

3. Login successfully.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0003.png?featherlight=false&width=90pc)

4. After successful login, we will install **Agent**

```
wget -O ./aws-replication-installer-init.py https://aws-elastic-disaster-recovery-us-west-2.s3.amazonaws.com/latest/linux/aws-replication-installer-init. py
```

   - Then, we will execute the command

```
sudo python3 aws-replication-installer-init.py
```

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0004.png?featherlight=false&width=90pc)

5. Make configuration

   - AWS Region Name
   - AWS Access Key ID
   - AWS Secret Access Key
   - For **Choose the disks you want to replicate**, select **Enter**


![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0005.png?featherlight=false&width=90pc)

6. We will follow the same steps for the **database** server part.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0006.png?featherlight=false&width=90pc)

7. Back to **DRS source server** page see **initial sync** process


![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0007.png?featherlight=false&width=90pc)

8. Both **DRS source servers**

   - Create security groups
   - Launch replication server
   - Boot replication server
   - Authenticate with service
   - Download replication software
   - Create staging disks
   - Attach staging disks
   - Pair replication server with Agent
   - Connect Agent with replication server
   - Start data transfer

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0008.png?featherlight=false&width=90pc)

9. We will select 1 **DRS source server** to see the details.

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/0009.png?featherlight=false&width=90pc)

10. You will have to wait about 10 minutes when **100%** done

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/00010.png?featherlight=false&width=90pc)

11. After about 1 minute, you will see **Ready for recovery** status as **Ready** and **Data replication status** as **Healthy**

![AWS Elastic Disaster Recovery Workshop](/images/5-agent/00011.png?featherlight=false&width=90pc)