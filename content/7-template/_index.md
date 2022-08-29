---
title : "Configure Launch Settings"
date : "`r Sys.Date()`"
weight : 7
chapter : false
pre : " <b> 7. </b> "
---

#### Configure EC2 Launch Template

1. In the **DRS** interface

   - Select **Source Servers**
   - Choose a source

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0001.png?featherlight=false&width=90pc)

2. In the **source server** interface

   - Select **Launch settings**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0002.png?featherlight=false&width=90pc)

3. For **Launch Setting**, select **None**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0003.png?featherlight=false&width=90pc)

4. Check again, we will see **Instance type right sizing** is **Off**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0004.png?featherlight=false&width=90pc)

5. Configure **EC2 Launch template**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0005.png?featherlight=false&width=90pc)

6. For **Template version description** enter **WorkshopTemplate**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0006.png?featherlight=false&width=90pc)

7. For **Instance type**, select **t3.small**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0007.png?featherlight=false&width=90pc)

8. For **Network Settings**, select **Target Private** for **Subnet**

   - For **existing security group**, select **TargetSecurityGroup**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0008.png?featherlight=false&width=90pc)

9. About the configuration **Configure Storage**

   - Select **Volume type** as **gp3**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0009.png?featherlight=false&width=90pc)

10. Select **Create template version**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00010.png?featherlight=false&width=90pc)

11. Create a **template version** successfully.

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00011.png?featherlight=false&width=90pc)

12. Details of templates.

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00012.png?featherlight=false&width=90pc)