---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Nghiên cứu kiến trúc mạng máy tính đám mây với Amazon VPC.
* Tìm hiểu hệ thống tường lửa hai lớp (Security Group & Network ACLs).
* Thực hành cấu hình tiền đề và khởi tạo máy chủ EC2 đặt trong VPC an toàn.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Học lý thuyết mạng: Subnet, Route Table, Internet Gateway, CIDR blocks | 01/06/2026 | 01/06/2026 | https://000003.awsstudygroup.com/1-introduce/ |
| 3 | - So sánh cơ chế hoạt động của Security Group (Stateful) và NACL (Stateless) | 02/06/2026 | 02/06/2026 | https://000003.awsstudygroup.com/2-firewallinvpc/ |
| 4 | - Thực hành cấu hình Rule tường lửa: Chặn/Mở IP dải port cụ thể để tăng cường bảo mật | 03/06/2026 | 03/06/2026 | https://000003.awsstudygroup.com/2-firewallinvpc/ |
| 5 | - Chuẩn bị các thông số kỹ thuật mạng và kiểm tra thông tin định tuyến | 04/06/2026 | 04/06/2026 | https://000003.awsstudygroup.com/3-prerequisite/ |
| 6 | - Thực hành Lab: Tạo lập thành công thực thể máy chủ EC2 nằm trong phân vùng VPC | 05/06/2026 | 05/06/2026 | https://000003.awsstudygroup.com/4-createec2server/ |
| 7 | - Thực hiện kiểm tra kết nối mạng hai chiều từ internet đến EC2 Server | 06/06/2026 | 06/06/2026 | https://000003.awsstudygroup.com/4-createec2server/ |
| CN | - Mô phỏng lại sơ đồ kiến trúc mạng tuần 7 phục vụ báo cáo tiến độ | 07/06/2026 | 07/06/2026 | Personal Notes, Draw.io |

### Kết quả đạt được tuần 7:

* Nắm vững quy hoạch dải mạng CIDR và phân tách phân vùng logic trên AWS.
* Xây dựng hệ thống tường lửa 2 lớp bảo vệ máy chủ điện toán khỏi các rủi ro mạng.
* Triển khai thực tế hạ tầng EC2 Server an toàn bảo mật.