---
title: "Truy cập Hybrid an toàn đến S3"
date: 2024-01-01
chapter: false
---

# Truy cập Hybrid an toàn đến S3 bằng VPC Endpoint

## Tổng quan

**AWS PrivateLink** cung cấp kết nối riêng tư đến các dịch vụ AWS từ VPC và mạng on-premises mà không đưa lưu lượng qua Internet công cộng.

Trong workshop này, bạn sẽ tạo, cấu hình và kiểm tra các VPC Endpoint để workload truy cập Amazon S3 qua kết nối riêng tư. Workshop sử dụng hai loại endpoint dành cho Amazon S3:

- **Gateway Endpoint** — định tuyến lưu lượng Amazon S3 từ VPC qua route table mà không cần Internet Gateway hoặc NAT Gateway.
- **Interface Endpoint** — cung cấp địa chỉ IP riêng và tên DNS để truy cập từ VPC hoặc mạng on-premises.

## Nội dung workshop

1. [Tổng quan workshop](1-Workshop-overview/)
2. [Các bước chuẩn bị](2-Prerequisite/)
3. [Truy cập S3 từ VPC](3-S3-vpc/)
4. [Truy cập S3 từ môi trường on-premises](4-S3-onprem/)
5. [Chính sách VPC Endpoint](5-Policy/)
6. [Dọn dẹp tài nguyên](6-Cleanup/)
