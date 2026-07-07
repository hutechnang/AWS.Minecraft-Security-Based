---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Làm chủ giải pháp lưu trữ đối tượng Amazon S3 Static Website Hosting.
* Thiết lập quy tắc bảo mật: Block Public Access kết hợp S3 Bucket Policy định danh.
* Tích hợp mạng phân phối nội dung Amazon CloudFront tối ưu HTTPS bảo mật.
* Cấu hình S3 Versioning và Cross-Region Replication (CRR) phòng chống thảm họa.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Học lý thuyết Amazon S3, cấu trúc Bucket, Object phân cấp | 15/06/2026 | 15/06/2026 | https://000057.awsstudygroup.com/1-introduce/ <br> https://000057.awsstudygroup.com/2-prerequiste/ |
| 3 | - Thực hành Lab: Đưa source code trang web lên S3, kích hoạt Static Website Hosting | 16/06/2026 | 16/06/2026 | https://000057.awsstudygroup.com/3-staticwebsite/ |
| 4 | - Thực hành cấu hình an toàn dữ liệu: Block Public Access và tinh chỉnh Bucket Policy | 17/06/2026 | 17/06/2026 | https://000057.awsstudygroup.com/4-blockpublicaccess/ <br> https://000057.awsstudygroup.com/5-publicobject/ <br> https://000057.awsstudygroup.com/6-testwebsite/ |
| 5 | - Thực hành Lab: Cấu hình CloudFront Distribution, bật Origin Access Control (OAC) | 18/06/2026 | 18/06/2026 | https://000057.awsstudygroup.com/7-cloudfront/ |
| 6 | - Thực hành Lab: Kích hoạt S3 Versioning để theo dõi lịch sử chỉnh sửa object tập tin | 19/06/2026 | 19/06/2026 | https://000057.awsstudygroup.com/8-versioning/ <br> https://000057.awsstudygroup.com/9-moveobject/ |
| 7 | - Thực hành Lab: Thiết lập S3 Cross-Region Replication (CRR) đồng bộ dữ liệu sang một phân vùng khác | 20/06/2026 | 20/06/2026 | https://000057.awsstudygroup.com/10-s3ccr/ <br> https://000057.awsstudygroup.com/11-cleanup/ |
| CN | - Kiểm thử hệ thống CDN toàn cầu, theo dõi cache behavior và ghi chép tài liệu | 21/06/2026 | 21/06/2026 | Personal Notes, S3 Dashboard |

### Kết quả đạt được tuần 9:

* Xây dựng thành công hệ thống lưu trữ website tĩnh tính bền vững cao, tối ưu chi phí.
* Bảo mật hoàn toàn S3 Bucket bằng cách chặn truy cập public trực tiếp, bắt buộc đi qua CloudFront OAC.
* Thiết lập thành thạo cơ chế sẵn sàng cao và khôi phục thảm họa qua Versioning và CRR liên vùng.