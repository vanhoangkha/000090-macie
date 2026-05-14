---
title : "Tạo Custom data identifiers"
date: 2024-01-01
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Tạo Custom data identifiers

1. Truy cập vào giao diện **Macie**

    - Chọn **Create job**

![Macie](/images/2/0001.png?featherlight=false&width=90pc)

2. Thực hiện cấu hình job, bước đầu tiên là **Choose S3 bucket**

   - Chọn **Select specific buckets**

![Macie](/images/2/0002.png?featherlight=false&width=90pc)

3. Chọn **S3 bucket**, ta đã tạo.

![Macie](/images/2/0003.png?featherlight=false&width=90pc)

4. Bước tiếp theo, thực hiện **Review S3 bucket**.

![Macie](/images/2/0004.png?featherlight=false&width=90pc)

5. Thực hiện **Refine the scope**

- Chọn **Include existing objects**
- Chọn **One-time job**
- Chọn **Next**

![Macie](/images/2/0005.png?featherlight=false&width=90pc)

6. Cấu hình **Object criteria**

- Chọn **File name extensions**
- Nhập **```csv```**
- Chọn **Include**

![Macie](/images/2/0006.png?featherlight=false&width=90pc)

7. Chọn **Next**

![Macie](/images/2/0007.png?featherlight=false&width=90pc)

8. Thực hiện **Select managed data identifiers**

- Chọn **All**
- Chọn **Next**

![Macie](/images/2/0008.png?featherlight=false&width=90pc)

9. Tạo **Manage custom identifiers**

![Macie](/images/2/0009.png?featherlight=false&width=90pc)

10. Trong giao diện **Custom data identifiers**, chọn **Create**.

![Macie](/images/2/00010.png?featherlight=false&width=90pc)

11. Đối với **Name**, nhập **```EmpID```**

- **Regular expression**, nhập **```[a-z][2][0-9][4]```**

![Macie](/images/2/00011.png?featherlight=false&width=90pc)

12. Chọn **Submit**

![Macie](/images/2/00012.png?featherlight=false&width=90pc)

13. Tạo **Custom data identifiers** thành công.

![Macie](/images/2/00013.png?featherlight=false&width=90pc)



