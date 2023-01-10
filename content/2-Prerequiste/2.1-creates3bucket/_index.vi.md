---
title : "Tạo S3 bucket"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

#### Tạo S3 bucket

{{% notice info %}}
Để tải xuống file **pii.csv**, bạn click [vào đây](https://raw.githubusercontent.com/AWS-First-Cloud-Journey/Discover-sensitive-data-present-in-S3-bucket-using-Amazon-Macie/main/pii.csv),  nhấp chuột phải vào nút *Raw* ở đầu file, chọn *Save Link As…*, rồi chọn nơi bạn muốn lưu file trên máy tính của bạn, chọn *Save*.
{{% /notice %}}

1. Truy cập vào giao diện **S3**

- Chọn **Create bucket**

![Launch EC2](/images/1/0001.png?featherlight=false&width=90pc)

2. Đối với **Create bucket**

    - **Bucket name**, bạn nhập tên tùy ý nhưng phải là giá trị duy nhất.
    - Chọn **AWS Region** mà bạn triển khai.

![Launch EC2](/images/1/0002.png?featherlight=false&width=90pc)

3. Chọn **Create bucket**

![Launch EC2](/images/1/0003.png?featherlight=false&width=90pc)

4. Sau khi tạo bucket thành công. Bạn chọn **Object** và tiếp tục chọn **Upload**

![Launch EC2](/images/1/0004.png?featherlight=false&width=90pc)

5. Upload file csv bạn đã tải về.

![Launch EC2](/images/1/0005.png?featherlight=false&width=90pc)

6. Upload thành công.

![Launch EC2](/images/1/0006.png?featherlight=false&width=90pc)

