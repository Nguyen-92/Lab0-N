# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nông Văn Nguyên

**MSSV:** 1871020439

**Lớp/Nhóm:** 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm của sinh viên 
- Asset 2: Dữ liệu điểm của sinh viên 
- Asset 3 (nếu có): Hệ thống lưu trữ và website quản lý điểm

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability  
- Sự cố B -> Integrity  
- Sự cố C -> Confidentiality  

---

## 3. Phân tích sự cố B
- Threat: Người xấu hoặc người trong hệ thống truy cập trái phép và sửa điểm  
- Vulnerability: Mật khẩu yếu, phân quyền chưa chặt, không có ghi log theo dõi thay đổi  
- Mitigation: Sử dụng mật khẩu mạnh, phân quyền rõ ràng, ghi log hệ thống, áp dụng xác thực hai lớp (2FA)  

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài lab này, em hiểu rõ hơn về tầm quan trọng của bảo mật trong hệ thống lưu điểm. 
Mỗi sự cố đều ảnh hưởng đến một khía cạnh khác nhau của CIA. 
Nếu là quản trị viên, em sẽ ưu tiên xử lý vấn đề Integrity trước vì điểm bị sửa sai sẽ ảnh hưởng trực tiếp đến sinh viên. 
Sau đó, em sẽ cải thiện bảo mật để tránh rò rỉ dữ liệu. 
Cuối cùng, em sẽ đảm bảo hệ thống luôn hoạt động ổn định để người dùng có thể truy cập khi cần.

---

## 5. Bonus Flag
`FIT4012{A-A-B-I-C-C}`
Flag của em: FIT4012{A-A-B-I-C-C}
