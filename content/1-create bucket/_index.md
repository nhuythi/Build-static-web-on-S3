---
title : "Create bucket"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

1. Log into [aws manament console](https://aws.amazon.com/vi/console/)

![Createbucket](/images/1.Createbucket/I.1.png)

2. In the search bar type S3

![Createbucket](/images/1.Createbucket/i.2.png)

3. Choose S3

![Createbucket](/images/1.Createbucket/1.3.png)

4.	In the interface of S3, click **Create Bucket** the right side of the interface

![Createbucket](/images/1.Createbucket/1.31.png)

5.	In the Create Bucket interface, we will configure the bucket:
- **Bucket name**: Name the bucket name, this bucket name is unique all over the world 
- **Aws region**: choose the region according to your needs, the closer the region, the lower the latency, the cost may be higher. For example, if your company is in Vietnam, we choose the region in Singapore as the closest, but it may cost more than the region in the US.

![Createbucket](/images/1.Createbucket/i.4.png)

- **Object Ownership**: Select ACLs disabled, to increase the security of this bucket, which is only owned by this account. 

![Createbucket](/images/1.Createbucket/i.5.png)

- **Block Public Access settings for this bucket**: leave default 

![Createbucket](/images/1.Createbucket/i.51.png)

- **Bucket versioning**: leave default 

![Createbucket](/images/1.Createbucket/i.6.png)

6.	At the bottom of the interface page, click **Create Bucket**

![Createbucket](/images/1.Createbucket/i.8.png)