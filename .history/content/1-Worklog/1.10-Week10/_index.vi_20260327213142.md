---
title: "Worklog Tuần 10"
date: 2026-03-16
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Triển khai luồng phê duyệt đa cấp độ và các module cài đặt hệ thống.
* Tích hợp AI và OCR, bao gồm thiết lập môi trường Docker GPU và chuẩn bị Gemini API.
* Giải quyết các conflict nhánh, hoàn thiện tính năng quản lý (Khách hàng, Nhóm) và sửa các lỗi tồn đọng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Triển khai logic cho tính năng chuông thông báo (Notification Bell).<br>- Viết luồng phê duyệt hóa đơn đa cấp độ (Multi-class Approval Workflow) cho doanh nghiệp.<br>- Thêm module cài đặt hệ thống (System Config) như các cấu hình workflow, thời gian.... | 16/03/2026 | 16/03/2026 | |
| 3 | - Tích hợp các System Config Provider vào core service.<br>- Cải thiện luồng xử lý hóa đơn bất đồng bộ kết hợp các dịch vụ lõi. | 17/03/2026 | 17/03/2026 | |
| 4 | - Xây dựng Document hướng dẫn cài đặt quy trình OCR bóc tách khối dữ liệu ảnh hóa đơn.<br>- Viết và dọn dẹp core engine cho mô hình AI quét ảnh.<br>- Thay đổi, nâng cấp sâu giao diện hiển thị các lỗi xác thực hóa đơn chuẩn (BusinessValidationSummary). | 18/03/2026 | 18/03/2026 | |
| 5, 6 | - Tập trung gỡ lỗi và resolve các conflict lớn giữa các branch hệ thống.<br>- Hoàn thiện các tính năng quản lý khách hàng (Tenant Management) và Quản lý nhóm (Team Management).<br>- Sửa các lỗi tồn đọng cho chức năng Thùng rác (Trash Invoice) và Xuất dữ liệu Excel. | 19/03/2026 | 20/03/2026 | |
| 7 | - Cài đặt môi trường Docker để build các library Deep Learning, yêu cầu có thiết lập GPU (Docker GPU).<br>- Chuẩn bị API key cho Gemini API (Mô hình LLM) để bypass vào luồng xử lý AI. | 21/03/2026 | 21/03/2026 | |
| CN | - Cập nhật màn hình Điều khoản dịch vụ (Terms of Use) và Chính sách quyền riêng tư (Privacy Policy).<br>- Bổ sung tính năng tự động gửi lại Email xác thực. | 22/03/2026 | 22/03/2026 | |

### Kết quả đạt được tuần 10:

* Triển khai thành công luồng phê duyệt đa cấp độ và hệ thống chuông thông báo.
* Xây dựng nền tảng AI/OCR thông qua việc cấu hình Docker GPU và chuẩn bị tích hợp Gemini API.
* Xử lý dứt điểm các conflict mã nguồn lớn và hoàn thiện các module quản trị cốt lõi (Khách hàng, Nhóm).