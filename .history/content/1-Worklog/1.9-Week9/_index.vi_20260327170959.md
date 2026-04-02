---
title: "Worklog Tuần 9"
date: 2026-03-09
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Xây dựng luồng phê duyệt hóa đơn đa cấp và hệ thống lưu vết lịch sử (Audit Logs).
* Phân tích và thiết kế cơ sở dữ liệu cho tính năng Gói cước khách hàng (Subscription).
* Tích hợp thành công các cổng thanh toán nội địa (VNPay, VietQR) để hoàn thiện luồng thanh toán gói cước.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 4 | - Bắt đầu viết flow phê duyệt hóa đơn đa cấp (Multi-level approval workflow).<br>- Thiết kế database cho phần ghi log lại lịch sử duyệt (Audit Logs). | 11/03/2026 | 12/03/2026 | |
| 6 | - Tìm hiểu và thiết kế cấu trúc database cho phần tính năng Subscription (gói cước khách hàng). | 13/03/2026 | 13/03/2026 | |
| 7 | - Code tích hợp cổng thanh toán VNPay và VietQR cho phần thanh toán mua gói cước.<br>- Test thử luồng thanh toán Sandbox. | 14/03/2026 | 15/03/2026 | |

### Kết quả đạt được tuần 9:

* Thiết kế và triển khai thành công luồng phê duyệt hóa đơn phức tạp, đáp ứng nhu cầu phê duyệt nhiều cấp.
* Xây dựng cấu trúc cơ sở dữ liệu hoàn chỉnh, chuẩn xác cho hệ thống Audit Logs và module Subscription.
* Tích hợp thành công và an toàn cổng thanh toán VNPay cùng VietQR.
* Đã thực hiện kiểm thử thành công toàn bộ luồng thanh toán mua gói cước trên môi trường Sandbox.