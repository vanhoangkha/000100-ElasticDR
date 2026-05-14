---
title : "Giới thiệu"
date: 2024-01-01
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

#### Tổng quan

AWS Elastic Disaster Recovery (AWS DRS) giúp giảm thiểu thời gian ngừng hoạt động và mất dữ liệu nhờ khả năng phục hồi các ứng dụng tại chỗ và trên đám mây một cách nhanh chóng, đáng tin cậy bằng cách sử dụng kho lưu trữ có mức chi phí hợp lý, tài nguyên điện toán tối thiểu và phục hồi về một thời điểm.

![AWS Elastic Disaster Recovery Workshop](/images/1/0001.png?featherlight=false&width=60pc)

Bài lab này thực hiện mô phỏng một môi trường tại chỗ cho phép khách hàng thực hiện sao chép khôi phục sau thảm họa sang AWS.

Môi trường mô phỏng được hỗ trợ bởi các  Amazon EC2  instance và được định cấu hình theo cách phù hợp với nhiều môi trường của khách hàng. Network bao gồm các private subnet và public, dịch vụ DNS, các ứng dụng được cài đặt sẵn và một máy chủ bastion host Windows.

Hình ảnh bên dưới là sơ đồ mạng cơ bản cho dịch vụ AWS Elastic Disaster Recovery (thường được gọi là DRS). Môi trường mô phỏng phù hợp với các yêu cầu dịch vụ.

![AWS Elastic Disaster Recovery Workshop](/images/1/0002.png?featherlight=false&width=60pc)

#### Kiến ​​thức cơ bản
Đây là Lab được tạo ra cho Kiến trúc sư Giải pháp, SysOps, ServerOps, InfraOps và các chuyên gia khác.

Để tận dụng tối đa lab này, bạn phải nắm rõ những điều sau:

- Kết nối với máy chủ Microsoft Windows bằng Remote Desktop Protocol (RDP)
- Kết nối với máy chủ Linux bằng SSH