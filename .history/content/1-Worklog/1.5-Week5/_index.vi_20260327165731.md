---
title: "Worklog Tuần 5"
date: 2026-02-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Đi sâu vào dịch vụ Amazon S3, các Storage Classes, chức năng liên quan và Best Practices.
* Khám phá mô hình lưu trữ Hybrid bằng dịch vụ Storage Gateway, Snow Family.
* Tìm hiểu và cấu hình các chiến lược khôi phục sau thảm họa với AWS Backup.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Học về các dịch vụ lưu trữ.<br>- Học về S3, các thuật ngữ liên quan, đặc điểm, tính chất, cách thao tác với S3.<br>- Storage Class của S3.<br>- S3 phù hợp Static Web và hỗ trợ CORS.<br>- Control Access, S3 endpoint, Versioning, Object Key (liên quan performance). | 02/02/2026 | 02/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Học về Glacier.<br>- Học về Snow Family - dịch vụ hỗ trợ migrate của AWS.<br>- AWS Storage Gateway - lưu trữ hybrid, tận dụng lưu lượng cloud + on-premise.<br>- Các chiến lược Disaster Recovery, RTO/RPO, AWS Backup. | 03/02/2026 | 03/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Làm bài lab 57: Amazon S3, host static web bằng S3.<br>- Hiểu về việc chặn / mở chặn truy cập vào tài nguyên trong S3 bucket.<br>- Kết hợp với CloudFront để cải thiện tốc độ duyệt static web host ở S3.<br>- Versioning, di chuyển, sao chép object sang region khác.<br>- Best Practices khi làm việc với S3. | 04/02/2026 | 04/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Làm bài lab 13: Triển khai AWS Backup cho hệ thống, dùng SNS để gửi thông báo.<br>- Tạo Backup Plan và cài đặt thông báo cho SNS bằng CLI.<br>- Làm bài lab 14: AWS VM Import/Export (chưa xong do gặp vấn đề phần mềm). | 05/02/2026 | 05/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - Làm bài lab 24: File Storage Gateway - hay, bỏ file vô ổ đĩa ở laptop mà nó xuất hiện trên S3 luôn.<br>- Storage Gateway là cái xử lí trung gian, File Share là cái nối các điểm cần chia sẻ file.<br>- Làm bài lab 25: FSx trên Windows (chưa làm được do kh tạo được stack). | 06/02/2026 | 06/02/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

* Nắm vững kiến thức toàn diện về S3 bao gồm Storage Classes, Control Access, Versioning, Object Key và cách tối ưu hóa hiệu năng S3.
* Hoàn thiện kỹ năng Host Static Web trên S3, thiết lập quyền truy cập bucket, cấu hình CORS và dùng CloudFront tăng tốc độ phân phối.
* Có kiến thức cơ bản về AWS Snow Family, ứng dụng hybrid storage với AWS Storage Gateway.
* Cấu hình thành công Backup Plan với AWS Backup, kết hợp gửi thông báo qua SNS sử dụng CLI.
* Đúc kết được Best Practices khi làm việc với S3 và kinh nghiệm xử lý lỗi lab thực tế (như lỗi phần mềm Import/Export VM hay lỗi tạo stack với FSx).