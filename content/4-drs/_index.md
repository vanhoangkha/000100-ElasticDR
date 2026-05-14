---
title : "Configure DRS Settings"
date: 2024-01-01
weight : 4
chapter : false
pre : " <b> 4. </b> "
---
#### Perform DRS configuration

This section will perform **AWS Elastic Disaster Recovery (DRS)** configuration.

1. Go to **AWS Management Console**
   - Find **DRS**
   - Select **AWS Elastic Disaster Recovery**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0001.png?featherlight=false&width=90pc)

2. The First step, we will choose **Set default replication settings**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0002.png?featherlight=false&width=90pc)

3. In the **Edit default replication settings** interface

   - Select **CloudEndure Staging** for **Staging area subnet**
   - For **Replication server instance type**, select **t3.small**.


![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0003.png?featherlight=false&width=90pc)

4. For **Security group**

   - We will leave the default value.

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0004.png?featherlight=false&width=90pc)

5. Check again and select **Save changes**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0005.png?featherlight=false&width=90pc)