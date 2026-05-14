---
title : "Chuẩn bị hạ tầng"
date: 2024-01-01
weight : 1 
chapter : false
pre : " <b> 2.1 </b> "
---

#### Chuẩn bị hạ tầng

- Trong bài này chúng ta sẽ thực hiện bài lab trong Region **US West (Oregon) us-west-2**

- Trong phần này, chúng ta sẽ chuẩn bị các tài nguyên cho bài lab bằng cách khởi tạo **CloudFormation** template.

- Bạn tải **CloudFormation** template tại [đây](https://github.com/AWS-First-Cloud-Journey/AWS-Elastic-Disaster-Recovery-Workshop/tree/main)

1. Truy cập vào giao diện **CloudFormation**

   - Chọn **Create stack**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **Create stack**

   - Chọn **Template is ready**
   - Chọn **Upload a template file**
   - Chọn **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0002.png?featherlight=false&width=90pc)

3. Đối với **Stack name**

   - Nhập **EDRW**
   - Đối với các thông số khác sử dụng mặc định.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0003.png?featherlight=false&width=90pc)

4. Chọn **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0004.png?featherlight=false&width=90pc)

5. Chọn **Next**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0005.png?featherlight=false&width=90pc)

6. Thực hiện chọn các **require capabilities**, sau đó chọn **Create stack**

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0006.png?featherlight=false&width=90pc)

7. Khoảng 30 phút sau, chúng ta sẽ quan sát giao diện và tạo thành công 5 stack.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0007.png?featherlight=false&width=90pc)

8. Xem **Outputs** của stack, chúng ta sẽ thấy tạo ra một BastionRDP dùng để kết nối.

![AWS Elastic Disaster Recovery Workshop](/images/1.1/0008.png?featherlight=false&width=90pc)
