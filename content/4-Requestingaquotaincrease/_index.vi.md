---
title : "Yêu cầu tăng giới hạn"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 4. </b> "
---

#### Yêu cầu tăng giới hạn


1. Truy cập vào giao diện [Service Quotas ](https://console.aws.amazon.com/servicequotas/home)

![Service Quotas](/images/2/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **Dashboard**

   - Chọn **AWS services**
   - Tìm dịch vụ bạn muốn xin thêm giới hạn (Ví dụ trong lab: **Amazon Elastic Compute Cloud (Amazon EC2)**)
   - Chọn **Amazon Elastic Compute Cloud (Amazon EC2)**

![Service Quotas](/images/2/0002.png?featherlight=false&width=90pc)

3. Sau khi truy cập vào tên dịch 

- Chọn **Quota name** mà chúng ta cần xin giới hạn. (Ví dụ trong bài lab là **Running On-Demand Standard (A, C, D, H, I, M, R, T, Z) instances**)

![Service Quotas](/images/2/0003.png?featherlight=false&width=90pc)

4. Xem thông tin và nhập **Change quota value** mà bạn muốn tăng.

  - Trong bài lab tăng từ 32 lên 100.
  - Sau đó chọn **Request**

![Service Quotas](/images/2/0004.png?featherlight=false&width=90pc)

5. Thực hiện yêu cầu gia tăng giới hạn thành công.

![Service Quotas](/images/2/0005.png?featherlight=false&width=90pc)

6. Trở về Dashboard chúng ta sẽ thấy **Pending service quota requests**

![Service Quotas](/images/2/0006.png?featherlight=false&width=90pc)

7. Chọn **Quota request history** để xem lịch sử yêu cầu tăng giới hạn.

- Bảng điều khiển Yêu cầu tăng giới hạn gần đây hiển thị thông tin về các yêu cầu tăng giới hạn đang mở gần đây của bạn và bất kỳ yêu cầu nào đã đóng trong vòng 90 ngày.

  - Dịch vụ - Hiển thị tên dịch vụ được chọn cho yêu cầu.

  - Tên giới hạn - Hiển thị tên giới hạn được chọn để tăng giới hạn.

  - Trạng thái - Hiển thị trạng thái của yêu cầu tăng giới hạn.

- Bạn có thể thấy các loại trạng thái sau:

  - Đã đóng - Việc tăng giới hạn được phê duyệt và yêu cầu đã đóng.

  - Yêu cầu giới hạn đã được phê duyệt - Việc tăng hạn mức được phê duyệt tự động.

  - Đã yêu cầu giới hạn - Yêu cầu tăng hạn mức đang chờ Bộ phận hỗ trợ AWS phê duyệt.

  - Giá trị giới hạn được yêu cầu - Giá trị giới hạn tăng lên mà bạn đã yêu cầu cho giới hạn.

  - Ngày yêu cầu - Ngày bạn yêu cầu tăng giới hạn.

  - Ngày cập nhật lần cuối - Ngày cuối cùng yêu cầu nhận được bản cập nhật.


![Service Quotas](/images/2/0007.png?featherlight=false&width=90pc)

8. Kiểm tra mail và sao chép đường dẫn trong mail.

![Service Quotas](/images/2/0008.png?featherlight=false&width=90pc)

9. Mở đường dẫn đã sao chép trong mail.

![Service Quotas](/images/2/0009.png?featherlight=false&width=90pc)

10. Sau đó bạn có thể theo dõi trạng thái yêu cầu của mình cho tới khi được chấp thuận bởi đội hỗ trợ dịch vụ của AWS.