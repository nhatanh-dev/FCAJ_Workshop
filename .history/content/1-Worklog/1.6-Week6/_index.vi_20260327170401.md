---
title: "Worklog Tuần 6"
date: 2026-02-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Tìm hiểu sâu về các dịch vụ và mô hình bảo mật trên AWS (Shared Responsibility Model, IAM, Cognito, KMS).
* Nắm bắt cách quản lý định danh và tài khoản tập trung với AWS Organizations và AWS Identity Center.
* Thực hành triển khai các chính sách bảo mật, cấp quyền và giám sát an toàn hệ thống (Security Hub, Permission Boundary).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Học về các dịch vụ bảo mật.<br>- Tìm hiểu Shared Responsibility Model - cho biết lỗi thuộc về ai khi hệ thống bị hack.<br>- Tìm hiểu kĩ hơn về IAM (Root Account, IAM Principal, IAM User/Policy/Role).<br>- Học về Amazon Cognito - dịch vụ xác thực do AWS quản lý, ứng dụng cho phần đăng ký, đăng nhập. | 09/02/2026 | 09/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Học về AWS Organizations - quản lý cùng lúc nhiều account bằng cách chia ra nhiều OU (Organization Unit), có Nested OU.<br>- Học AWS Identity Center - giới hạn việc tạo nhiều account/role, chỉ cần tạo account và chọn role cần thiết.<br>- Học AWS KMS - quản lý encryption key, hỗ trợ encrypt/decrypt dữ liệu.<br>- Học AWS Security Hub - công cụ chạy tự động đánh giá chất lượng bảo mật môi trường hiện tại.<br>- Làm bài lab 02: Thao tác với IAM Role.<br>- Làm bài lab 44: Thao tác với condition của IAM Policy. | 10/02/2026 | 10/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Làm bài lab 48: Cấp quyền cho Services bằng IAM Role thay vì access key => tránh lộ key khi upload lên GitHub, bảo mật hơn.<br>- Làm bài lab 30: IAM Permission Boundary - giới hạn quyền user tránh lỗ hổng bảo mật khi có quá nhiều user.<br>- Làm bài lab 28: Quản lý quyền với EC2 bằng Policy và Resource Tags.<br>- Làm bài lab 18: Chạy kết hợp Security Hub và AWS Config để kiểm tra bảo mật tài khoản. | 11/02/2026 | 11/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Làm bài lab 12: Identity Center, login nhiều acc, time-based access control, customer managed policies (CMP), Identity Store APIs (dùng CLI để thực hiện nhiều lệnh cùng lúc) => Bài lab này khá khó.<br>- Làm bài lab 33: AWS KMS - Mã hóa xong có thể Make Public và dùng Athena để tra cứu.<br>- Về quê nghỉ Tết. | 12/02/2026 | 12/02/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 6:

* Hiểu rõ mô hình Trách nhiệm chung (Shared Responsibility Model) và cấu trúc chuyên sâu của IAM.
* Biết cách ứng dụng Amazon Cognito cho việc xác thực người dùng và AWS KMS để quản lý khóa mã hóa dữ liệu.
* Hoàn thành các bài thực hành thiết lập IAM Role, Policy, và Permission Boundary để tối ưu hóa bảo mật hệ thống.
* Triển khai cấu hình quản lý nhiều tài khoản thông qua AWS Organizations và AWS Identity Center.
* Sử dụng thành thạo Security Hub và AWS Config để tự động kiểm tra, đánh giá tình trạng bảo mật của tài khoản.