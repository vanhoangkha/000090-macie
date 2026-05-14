---
title : "Giới thiệu"
date: 2024-01-01
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

####  Giới thiệu

Amazon Macie phát hiện và bảo vệ dữ liệu nhạy cảm của bạn được lưu trữ trong S3 bucket. Trước tiên, nó xác định dữ liệu nhạy cảm trong bucket của bạn, chẳng hạn như thông tin nhận dạng cá nhân hoặc thông tin sức khỏe cá nhân, thông qua các jobs. Bạn có thể lên lịch các job này để theo dõi dữ liệu mới được thêm vào bucket của mình. Sau khi tìm thấy dữ liệu nhạy cảm, Macie liên tục đánh giá bucket của bạn và thông báo cho bạn khi bucket không được mã hóa, có thể truy cập công khai hoặc được chia sẻ với các tài khoản AWS bên ngoài tổ chức của bạn.


![Launch EC2](/images/1/00014.png?featherlight=false&width=90pc)

Định giá của Macie thay đổi theo số lượng dữ liệu mà nó xử lý và số lượng S3 bucket mà nó giám sát.

- Amazon Macie sử dụng tính năng đối sánh mẫu và học máy để bảo vệ dữ liệu nhạy cảm được lưu trữ trong S3 bucket.
- Nó phát hiện danh sách các loại dữ liệu bao gồm PII (Thông tin nhận dạng cá nhân) như tên, địa chỉ, số thẻ tín dụng, v.v.
- Cùng với việc phát hiện dữ liệu, nó cung cấp cho bạn khả năng hiển thị đầy đủ về các S3 bucket của bạn và thông tin của nó như các bucket có thể truy cập công khai, bucket không được mã hóa và các bucket được chia sẻ với các tài khoản khác.
- Để bắt đầu với Amazon Macie, bạn có thể sử dụng bản dùng thử miễn phí trong 30 ngày để đánh giá bucket.
- Bản dùng thử miễn phí không bao gồm việc phát hiện ra dữ liệu nhạy cảm có trong S3 bucket .

![Launch EC2](/images/1/00013.png?featherlight=false&width=90pc)