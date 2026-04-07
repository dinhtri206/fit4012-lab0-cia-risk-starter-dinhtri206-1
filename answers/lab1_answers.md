# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Đình Trí

**MSSV:** 1871020580

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Bảng điểm sinh viên
- Asset 2: Tài khoản giảng viên
- Asset 3 (nếu có): Cơ sở dữ liệu hệ thống

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Bảo mật
- Sự cố B -> Chính trực
- Sự cố C -> Tính khả dụng

---

## 3. Phân tích sự cố B
- Threat: Sinh viên hoặc hacker truy cập trái phép vào tài khoản giảng viên để sửa điểm trong hệ thống lưu điểm
- Vulnerability: Mật khẩu yếu, không có xác thực 2 lớp, hệ thống bảo mật kém và phân quyền truy cập chưa chặt chẽ
- Mitigation: Sử dụng mật khẩu mạnh, bật xác thực 2 yếu tố (2FA), ghi log đăng nhập và phân quyền rõ ràng cho tài khoản

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài lab này, em hiểu rõ hơn về mô hình CIA trong an ninh mạng gồm Confidentiality, Integrity và Availability. Em nhận ra rằng hệ thống lưu điểm cần được bảo vệ để tránh bị rò rỉ thông tin, sửa điểm trái phép và bị sập hệ thống. Việc phân tích threat, vulnerability và mitigation giúp em hiểu cách phát hiện lỗ hổng và đưa ra biện pháp phòng chống. Bài lab giúp em nắm rõ cách áp dụng kiến thức an ninh vào hệ thống thực tế. Đây là kiến thức quan trọng trong lĩnh vực an toàn thông tin và phát triển phần mềm.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:
FIT4012{A-Confidentiality-B-Integrity-C-Availability}
