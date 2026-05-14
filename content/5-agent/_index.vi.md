---
title : "Cấu hình DRS Agent"
date: 2024-01-01
weight : 5
chapter : false
pre : " <b> 5. </b> "
---

#### Thực hiện cấu hình DRS Agent IAM User

Để thực hiện phần này, chúng ta sẽ tạo một **IAM User**

1. Truy cập vào giao diện **AWS Management Console**

   - Tìm **IAM**
   - Chọn **IAM**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **AWS IAM**


- Chọn **User**
- Chọn **Add user**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0002.png?featherlight=false&width=90pc)

3. Thực hiện tạo **user** với tên **drs-agent-user**

   - Sau đó, chọn **Next:Permission**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0003.png?featherlight=false&width=90pc)

4. Đối với **Set Permissions**

   - Chọn **Attach existing policies directly**
   - Tìm và chọn **AWSElasticDisasterRecoveryAgentInstallationPolicy**
   - Chọn **Next:Tags**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0004.png?featherlight=false&width=90pc)

5. Chọn **Next:Review**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0005.png?featherlight=false&width=90pc)

6. Chọn **Create user**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0006.png?featherlight=false&width=90pc)

7. Chúng ta sẽ tải **Download.csv** để thực hiện lưu thông tin **Access Key** cho các bước tiếp theo.

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0007.png?featherlight=false&width=90pc)

