---
title : "Failing Over"
date : "`r Sys.Date()`"
weight : 8
chapter : false
pre : " <b> 8. </b> "
---

#### Failing Over

1. Go to the **DRS** page

   - We will see there are 2 **Hostname**
   - Choose 1 **hostname**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0001.png?featherlight=false&width=90pc)

2. Next

   - Select **Initiate recovery job**
   - Select **Initiate drill**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0002.png?featherlight=false&width=90pc)

3. For **Points in time** select **Use most recent data**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0003.png?featherlight=false&width=90pc)

4. Select **Initiate drill**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0004.png?featherlight=false&width=90pc)

5. Go to **DRS** interface, select **Recovery job history**

   - View **Job log** of **Hostname** web

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0005.png?featherlight=false&width=90pc)

6. View **Job log** of **Hostname** database.

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0006.png?featherlight=false&width=90pc)'

7. Go to the **EC2** interface. You will see there are two instances of **wordpress-db-onpremsim.env** and **wordpress-db.onpremsim.env**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0007.png?featherlight=false&width=90pc)