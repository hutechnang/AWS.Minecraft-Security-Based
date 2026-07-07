---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Nghiên cứu rủi ro lộ lọt thông tin mã khóa lập trình tĩnh.
* Tìm hiểu phương pháp quản lý IAM Access Key an toàn.
* Thực hành thay thế Access Key bằng IAM Role cho máy chủ EC2 (Instance Profile).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Chuẩn bị môi trường CLI local phục vụ kiểm thử bảo mật credentials | 18/05/2026 | 18/05/2026 | https://000048.awsstudygroup.com/1-prepare/ |
| 3 | - Thực hành Lab: Tạo IAM Access Key và kiểm thử kết nối lập trình | 19/05/2026 | 19/05/2026 | https://000048.awsstudygroup.com/2-accesskey/ |
| 4 | - Mô phỏng tấn công rò rỉ mã nguồn chứa Access Key (Tư duy Red Team) | 20/05/2026 | 20/05/2026 | https://000048.awsstudygroup.com/2-accesskey/ |
| 5 | - Thực hành Lab: Tạo một IAM Role dành riêng cho dịch vụ máy chủ EC2 | 21/05/2026 | 21/05/2026 | https://000048.awsstudygroup.com/3-iamroleec2/ |
| 6 | - Thực hành Lab: Gán Instance Profile vào EC2 để thực thi lệnh không cần Key cứng | 22/05/2026 | 22/05/2026 | https://000048.awsstudygroup.com/3-iamroleec2/ |
| 7 | - Tiến hành thu hồi Access Key cũ và dọn dẹp hạ tầng lab (Cleanup) | 23/05/2026 | 23/05/2026 | https://000048.awsstudygroup.com/4-cleanup/ |
| CN | - Đánh giá ưu điểm giải pháp bảo mật Keyless phục vụ mục tiêu DevSecOps | 24/05/2026 | 24/05/2026 | Personal Notes, Security Logs |

### Kết quả đạt được tuần 5:

* Nhận thức sâu rủi ro của việc hardcode Access Key trong mã nguồn phần mềm.
* Cấu hình thành công cơ chế cấp quyền động an toàn thông qua Instance Profile.
* Loại bỏ hoàn toàn thông tin xác thực tĩnh, tăng cường an toàn hệ thống.