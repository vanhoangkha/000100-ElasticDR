---
title : "Thực hiện cấu hình DRS"
date: 2024-01-01
weight : 4
chapter : false
pre : " <b> 4. </b> "
---
#### Thực hiện cấu hình DRS

Trong phần này, chúng ta sẽ thực hiện cấu hình  **AWS Elastic Disaster Recovery (DRS)**. 

1. Truy cập vào **AWS Management Console**
   - Tìm **DRS**
   - Chọn **AWS Elastic Disaster Recovery**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0001.png?featherlight=false&width=90pc)

2. Bước đầu tiên, chúng ta sẽ chọn **Set default replication settings**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0002.png?featherlight=false&width=90pc)

3. Trong giao diện **Edit default replication settings**

   - Chọn **CloudEndure Staging** đối với **Staging area subnet**
   - Đối với **Replication server instance type**, chọn **t3.small**.


![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0003.png?featherlight=false&width=90pc)

4. Đối với **Security group**

   - Ta sẽ để giá trị mặc định.

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0004.png?featherlight=false&width=90pc)

5. Kiểm tra lại và chọn **Save changes**

![AWS Elastic Disaster Recovery Workshop](/images/3-edr/0005.png?featherlight=false&width=90pc)