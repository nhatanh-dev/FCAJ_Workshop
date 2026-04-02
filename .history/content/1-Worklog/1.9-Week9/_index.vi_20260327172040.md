---
title: "Worklog Tuần 9"
date: 2026-03-09
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Tích hợp cổng thanh toán và triển khai hệ thống xử lý bất đồng bộ (VNPay, Amazon SQS).
* Nâng cấp bảo mật hệ thống thông qua việc hoàn thiện phân quyền (RBAC) và cách ly dữ liệu (Data Isolation).
* Hoàn thiện các tính năng báo cáo/xuất dữ liệu và tối ưu hóa toàn diện UI/UX.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nâng cấp logic RBAC và cách ly dữ liệu thành viên (Data Isolation) đảm bảo không lộ chéo dữ liệu.<br>- Fix bug hiển thị giao diện cho các trang AuditLogs, InvoiceList, RiskCheck. | 09/03/2026 | 09/03/2026 | |
| 3 | - Tối ưu hóa API backend, tái cấu trúc (Refactor) các entities của database liên quan đến hóa đơn.<br>- Đánh bóng và trau chuốt lại toàn diện UI/UX cho các trang Landing page, Đăng nhập, và Đăng ký. | 10/03/2026 | 10/03/2026 | |
| 4 | - Tích hợp Cổng thanh toán VNPay, cấu hình các bảng giao dịch PaymentTransaction.<br>- Hoàn thiện Service quản lý Gói cước thuê bao (Subscription Packages) và giới hạn dung lượng tải lên (Quota Management).<br>- Cập nhật logic tích hợp API VietQR để tự động kiểm tra trạng thái hoạt động của doanh nghiệp từ Mã số thuế. | 11/03/2026 | 11/03/2026 | |
| 5 | - Import thư viện Amazon SQS và thiết lập Message Queue cho luồng kiểm tra thông tin VietQR để xử lý dữ liệu nặng chạy ngầm (async validation).<br>- Áp dụng kỹ thuật Smart Polling UI phía Frontend để tự động load lại trạng thái khi xử lý SQS xong. | 12/03/2026 | 12/03/2026 | |
| 6 | - Phát triển tính năng thống kê báo cáo (ReportPage).<br>- Lập trình công cụ cho phép xuất dữ liệu hàng loạt hóa đơn ra file Excel.<br>- Thiết kế thêm Popup cảnh báo xác nhận khi người dùng vô tình rời khỏi trang Upload hóa đơn. | 13/03/2026 | 13/03/2026 | |
| CN | - Debug và sửa lỗi chữ ký không hợp lệ (Invalid Signature) từ luồng thanh toán VNPay.<br>- Sửa lỗi logic cấu trúc dữ liệu InvoiceCheckResult và quy trình Đăng ký tài khoản công ty mới. | 15/03/2026 | 15/03/2026 | |

### Kết quả đạt được tuần 9:

* Tích hợp thành công cổng thanh toán VNPay và hệ thống Message Queue (Amazon SQS) để xử lý dữ liệu bất đồng bộ một cách mượt mà.
* Nâng cao bảo mật và tính riêng tư của hệ thống nhờ áp dụng triệt để logic RBAC và Data Isolation.
* Hoàn thiện công cụ xuất báo cáo Excel, cải thiện đáng kể trải nghiệm người dùng (UI/UX) và khắc phục thành công các lỗi quan trọng trong luồng hệ thống.