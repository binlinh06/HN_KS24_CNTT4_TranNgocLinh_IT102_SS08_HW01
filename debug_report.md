# DEBUG REPORT - SAAS SUBSCRIPTION

## 1. Thông tin bài tập

- Bài tập: Dò vết & Sửa lỗi Duyệt Mảng Struct Gói Thuê bao Dịch vụ SaaS
- Ngôn ngữ: C
- Chuẩn: ANSI C / C11
- Compiler: GCC
- Tệp mã nguồn: `subscription_report.c`

---

## 2. Mô tả lỗi

Chương trình có nhiệm vụ duyệt danh sách 4 tài khoản người dùng.

Quy tắc nghiệp vụ:

- `days_overdue <= 3`: tài khoản hợp lệ và được tính vào tổng doanh thu.
- `days_overdue > 3`: tài khoản quá hạn và không được tính doanh thu.

Tuy nhiên, chương trình ban đầu sử dụng:

```c
user_list[0].days_overdue