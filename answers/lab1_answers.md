# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn đình trí

**MSSV:** 1871020580

**Lớp/Nhóm:** CNTT-18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Bảng điểm sinh viên
- Asset 2: Tài khoản sinh viên
- Asset 3 (nếu có):

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Không đăng nhập
- Sự cố B -> Điểm bị đổi
- Sự cố C -> Lộ dữ liệu

---

## 3. Phân tích sự cố B
- Threat: truy cập trái phép
- Vulnerability: Mật khẩu yếu
- Mitigation: Yêu cầu phê duyệt khi sửa chữa

---

## 4. Reflection
Viết 5-7 dòng.

Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề sửa điểm trái phép trước vì đây là vấn đề ảnh hưởng trực tiếp đến tính chính xác của dữ liệu.
Khi điểm bị thay đổi sai, hệ thống sẽ mất uy tín và gây ảnh hưởng lớn đến sinh viên và giảng viên.
Vì vậy cần triển khai phân quyền rõ ràng, bật xác thực nhiều lớp và ghi log đầy đủ để kiểm soát việc chỉnh sửa điểm.
Sau đó mới xử lý các vấn đề khác như đăng nhập và bảo mật dữ liệu.

---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-A-B-I-C-C}

