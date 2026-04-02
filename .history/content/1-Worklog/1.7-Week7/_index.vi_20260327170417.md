---
title: "Worklog Tuần 7"
date: 2026-02-25
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Tìm hiểu và thực hành với cơ sở dữ liệu quan hệ trên AWS (Amazon RDS, Migration Tools).
* Bắt tay vào dự án thực tế: Xây dựng module xử lý và chuẩn hóa dữ liệu hóa đơn XML.
* Hoàn thiện hệ thống xác thực, phân quyền người dùng (JWT, Policy-based Authorization) cho Frontend và Backend.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 4 | - Học về RDS, DB Subnet, DB Snapshot, Read Replicas, AWS Database Migration Service và Schema Conversion Tool.<br>- Làm bài lab thao tác với RDS. | 25/02/2026 | 26/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - Nghiên cứu và xây dựng bộ quy tắc xác thực (validation rules) đọc file hóa đơn XML theo chuẩn quy định của Tổng Cục Thuế.<br>- Viết script xử lý trích xuất dữ liệu gốc từ XML và map sang DTO. | 27/02/2026 | 27/02/2026 | |
| 7 | - Hoàn thiện module quản lý người dùng.<br>- Cấu hình và fix lỗi xác thực bảo mật JWT Token trên giao diện Swagger. | 28/02/2026 | 28/02/2026 | |
| CN | - Thiết lập context xác thực (AuthContext) và bảo vệ các luồng điều hướng (ProtectedRoute) ở phía Frontend.<br>- Viết cấu hình ủy quyền dựa trên chính sách (Policy-based Authorization) cho Backend.<br>- Refactor lại một số UI component và cập nhật cấu hình Tailwind. | 01/03/2026 | 01/03/2026 | |

### Kết quả đạt được tuần 7:

* Nắm vững kiến thức về kiến trúc Amazon RDS, các tính năng sao lưu (Snapshot), nhân bản (Read Replicas) và dịch vụ di chuyển cơ sở dữ liệu.
* Hoàn thành bài thực hành triển khai và cấu hình cơ sở dữ liệu trên AWS.
* Xây dựng thành công kịch bản trích xuất và chuẩn hóa dữ liệu hóa đơn định dạng XML sang đối tượng DTO.
* Cấu hình và khắc phục triệt để các lỗi liên quan đến xác thực bảo mật JWT Token tích hợp với Swagger.
* Triển khai an toàn các luồng điều hướng bảo vệ (ProtectedRoute) trên Frontend và hệ thống phân quyền (Policy-based Authorization) trên Backend.