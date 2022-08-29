---
title : "Cấu hình Launch Template "
date :  "`r Sys.Date()`" 
weight : 7
chapter : false
pre : " <b> 7. </b> "
---

#### Cấu hình EC2 Launch Template

1. Trong giao diện **DRS**

   - Chọn **Source Servers**
   - Chọn một source

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **source server**

   - Chọn **Launch settings**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0002.png?featherlight=false&width=90pc)

3. Đối với **Launch Setting**, chọn **None**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0003.png?featherlight=false&width=90pc)

4. Kiểm tra lại, ta sẽ thấy **Instance type right sizing** là **Off**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0004.png?featherlight=false&width=90pc)

5. Thực hiện cấu hình **EC2 Launch template**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0005.png?featherlight=false&width=90pc)

6. Đối với **Template version description** nhập **WorkshopTemplate**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0006.png?featherlight=false&width=90pc)

7. Đối với **Instance type**, chọn **t3.small**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0007.png?featherlight=false&width=90pc)

8. Đối với **Network Settings**, chọn **Target Private** cho **Subnet**

   - Đối với **existing security group**, chọn **TargetSecurityGroup**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0008.png?featherlight=false&width=90pc)

9. Về phần cấu hình **Configure Storage**

   - Chọn **Volume type** là **gp3**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/0009.png?featherlight=false&width=90pc)

10. Chọn **Create template version**

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00010.png?featherlight=false&width=90pc)

11. Tạo **template version** thành công.

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00011.png?featherlight=false&width=90pc)

12. Chi tiết các template.

![AWS Elastic Disaster Recovery Workshop](/images/6-setting/00012.png?featherlight=false&width=90pc)
