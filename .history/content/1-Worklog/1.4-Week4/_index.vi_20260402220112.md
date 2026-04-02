---
title: "Worklog Tuần 4"
date: 2026-01-26
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Tìm hiểu chi tiết về dịch vụ EC2, các tùy chọn lưu trữ, và cách thức mở rộng (Auto Scaling).
* Làm quen với các công cụ giám sát (CloudWatch) và quản lý tài nguyên (Tags, Resource Group).
* Tham gia giao lưu, học hỏi tại sự kiện AWS re:Invent Recap HCMC.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Học về EC2, các phân biệt các Instance Types, Hardware Node, Hypervision.<br>- Tiếp tục với AMI, Backup (Snapshot), Keypair, hai kiểu lưu trữ của EC2 là EBS, Instance Store.<br>- Học về EC2 User Data, EC2 Metadata.<br>- Học về EC2 Auto Scaling, các loại scaling của ASG.<br>- Đọc biết các Pricing Options. | 26/01/2026 | 26/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Học tiếp về Lightsail.<br>- Tìm hiểu các công cụ lưu trữ chia sẻ là Amazon EFS (Elastic File System) và Amazon FSx.<br>- Công cụ migrate AWS Application Migration Service (MGN). | 27/01/2026 | 27/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Làm bài lab 04: Làm việc với EC2 (Windows Instance và Linux Instance).<br>- Tạo AMI, custom AMI.<br>- Truy cập khi mất keypair bằng SSM (Windows), User Data (Linux).<br>- Giới hạn truy cập / thao tác trên EC2 bằng IAM. | 28/01/2026 | 28/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Tham gia event AWS re:Invent Recap HCMC.<br>- Biết thêm các dịch vụ mới của AWS mà em chưa được học, nghe về các bài trình bày của các anh chị talker.<br>- Gặp gỡ các anh chị SA, kết nối được với một số người cũng tìm hiểu về AWS và cloud. | 29/01/2026 | 29/01/2026 | |
| 6 | - Học về Tags và Resource Group.<br>- Làm bài lab 27: Tags và Resource Group.<br>- Thao tác với Tag (tạo, thêm, xóa, lọc bằng tag) bằng console và CLI.<br>- Tạo Resource Group.<br>- Học về AWS CloudWatch.<br>- Làm bài lab 08: Thao tác với CloudWatch, có Metrics, Logs, Alarms, Dashboards.<br>- Metrics: Tìm kiếm, toán học, dynamic labels. | 30/01/2026 | 30/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - Hoàn thành lab 08.<br>- Làm bài lab 06: Auto Scaling Group kết hợp Load Balancer, kiểm thử, hơi khó.<br>- Làm bài lab 45: Làm việc với Lightsail, dễ hiểu. | 31/01/2026 | 31/01/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

* Nắm vững các khái niệm xoay quanh EC2 (Instance Types, AMI, EBS, Instance Store, Metadata).
* Biết cách dùng IAM để giới hạn quyền truy cập EC2 và lấy lại quyền truy cập khi mất Keypair qua SSM/User Data.
* Hiểu và thực hành thao tác đánh Tag, nhóm tài nguyên hiệu quả bằng Resource Group.
* Giám sát hệ thống thông qua AWS CloudWatch (Metrics, Logs, Alarms).
* Thực hành cấu hình khả năng tự động co giãn tài nguyên qua bài Lab về Auto Scaling Group và Load Balancer.
* Mở rộng networking cá nhân và cập nhật kiến thức mới khi tham dự sự kiện thực tế của AWS.