---
title : "Tạo bucket"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

1. Đăng nhập vào [aws manament console](https://aws.amazon.com/vi/console/)

![Createbucket](/images/1.Createbucket/I.1.png)

2. Trên thanh tìm kiếm gõ S3

![Createbucket](/images/1.Createbucket/i.2.png)

3. Nhấn chọn S3

![Createbucket](/images/1.Createbucket/1.3.png)

4.	Trong giao diện của S3, bấm chọn **Create Bucket** phía bên phải giao diện

![Createbucket](/images/1.Createbucket/1.31.png)

5.	Trong 1 giao diện Create Bucket, chúng ta sẽ cấu hình cho bucket:
- **Bucket name**: Đặt tên cho bucket name, tên bucket này là duy nhất trên toàn thế giới 
- **Aws region**: lựa chọn region theo nhu cầu của bạn, region càng gần thì độ trễ càng thấp, chi phí có thể cao hơn. Ví dụ nếu công ty bạn ở Việt Nam thì chúng ta chọn region ở Singapore là gần nhất nhưng có thể chi phí cao hơn region ở Mỹ.

![Createbucket](/images/1.Createbucket/i.4.png)

- **Object Ownership**: Chọn ACLs disabled, để tăng độ bảo mật cho bucket này, chỉ được sở hữu duy nhất bởi tài khoản này. 

![Createbucket](/images/1.Createbucket/i.5.png)

- **Block Public Access settings for this bucket**: để mặc định 

![Createbucket](/images/1.Createbucket/i.51.png)

- **Bucket versioning**: để mặc định 

![Createbucket](/images/1.Createbucket/i.6.png)

6.	Ở cuối trang giao diện, bấm chọn **Create Bucket**

![Createbucket](/images/1.Createbucket/i.8.png)

