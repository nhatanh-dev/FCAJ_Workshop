---
title: "Worklog Tuần 8"
date: 2026-03-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Triển khai toàn diện các tính năng quản lý hóa đơn cốt lõi (CRUD, phân quyền, lưu nháp).
* Nâng cấp bảo mật hệ thống thông qua mô hình RBAC và AWS Parameter Store.
* Tối ưu hóa hiệu năng xử lý file và cải thiện trải nghiệm người dùng (UI/UX) cho các thành phần chính.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Triển khai logic luồng thêm, đọc, xóa, sửa (CRUD) cho Hóa đơn.<br>- Tối ưu hóa hiệu năng kịch bản đọc/xử lý file XML.<br>- Xây dựng tính năng Audit Logs để theo dõi lịch sử thao tác hệ thống. | 02/03/2026 | 02/03/2026 | |
| 3 | - Làm tính năng lọc (filtering) và phân trang (pagination) cho danh sách hóa đơn.<br>- Áp dụng mô hình RBAC (Role-Based Access Control) để kiểm soát quyền và tinh chỉnh giao diện người dùng. | 03/03/2026 | 03/03/2026 | |
| 4 | - Chuyển đổi cách lưu trữ biến môi trường bảo mật: cấu hình thay thế DotNetEnv bằng AWS Parameter Store.<br>- Xây dựng Service và UI cho tính năng Blacklist (Danh sách đen doanh nghiệp). | 04/03/2026 | 04/03/2026 | |
| 5 | - Tham gia phân tích nghiệp vụ hóa đơn, thêm tính năng để kiểm tra quyền sở hữu của hóa đơn (Ownership validation).<br>- Hoàn thiện tính năng quản lý hóa đơn nháp (Lưu nháp / Nộp / Xóa). | 05/03/2026 | 06/03/2026 | |
| 7 | - Test và cải thiện UI/UX, Backend cho các thành phần cốt lõi: Dashboard, Invoice, Risk, Audit.<br>- Sửa lỗi hiển thị dữ liệu lọc theo thời gian và cải thiện các tab trong trang chi tiết hóa đơn (InvoiceDetail). | 07/03/2026 | 07/03/2026 | |

### Kết quả đạt được tuần 8:

* Hoàn thiện luồng quản lý Hóa đơn với các tính năng CRUD, phân trang, lọc và kiểm tra quyền sở hữu.
* Nâng cao bảo mật hệ thống thành công nhờ áp dụng RBAC và lưu trữ biến môi trường an toàn qua AWS Parameter Store.
* Tối ưu thành công hiệu suất đọc file XML và cải thiện đáng kể UI/UX cho các trang cốt lõi của ứng dụng.