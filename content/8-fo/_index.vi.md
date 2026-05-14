---
title : "Failing Over"
date: 2024-01-01
weight : 8
chapter : false
pre : " <b> 8. </b> "
---

#### Failing Over

1. Truy cập vào trang **DRS**

   - Chúng ta sẽ thấy có 2 **Hostname**
   - Chọn 1 **hostname**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0001.png?featherlight=false&width=90pc)

2. Tiếp theo

   - Chọn **Initiate recovery job**
   - Chọn **Initiate drill**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0002.png?featherlight=false&width=90pc)

3. Đối với **Points in time** chọn **Use most recent data**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0003.png?featherlight=false&width=90pc)

4. Chọn **Initiate drill**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0004.png?featherlight=false&width=90pc)

5. Vào giao diện **DRS**, chọn **Recovery job history**

   - Xem **Job log** của **Hostname** web

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0005.png?featherlight=false&width=90pc)

6. Xem **Job log** của **Hostname** database.

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0006.png?featherlight=false&width=90pc)'

7. Vào giao diện **EC2**, bạn sẽ thấy có 2 instance về **wordpress-db-onpremsim.env** và **wordpress-db.onpremsim.env**

![AWS Elastic Disaster Recovery Workshop](/images/7-fo/0007.png?featherlight=false&width=90pc)

