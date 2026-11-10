# Checklist An toàn Thông tin Cá nhân

## 1. Mô hình Xác thực 3 Lớp & Zero-Knowledge
- **Something You Know:** Mật khẩu chính (Master Password) bảo vệ Vault phải dài trên 20 ký tự, dạng cụm từ dễ nhớ (Passphrase)[cite: 2].
- **Something You Have:** Kích hoạt 2FA (TOTP) thông qua ứng dụng Authenticator (Google Authenticator / Aegis), đổi mới mỗi 30 giây[cite: 2]. 
- *Lưu ý tuyệt đối:* **Không** sử dụng SMS OTP làm phương thức 2FA chính do rủi ro tấn công hoán đổi SIM (SIM Swapping)[cite: 2].
- **Backup Codes:** Lưu trữ 10 mã dự phòng của tài khoản GitHub/Email vào trong Bitwarden[cite: 2].

## 2. Quy tắc phòng chống rủi ro
- **Quy tắc 5 KHÔNG:** Không dùng chung một mật khẩu cho nhiều tài khoản; không dùng SMS OTP chính; không bấm vào link lạ (phòng chống Phishing & Typosquatting); không cài phần mềm Crack/Keygen trôi nổi; không tắt phần mềm diệt virus[cite: 1, 2].
- **Bảo vệ Secrets trong Code:** Không bao giờ viết cứng (hardcode) API Key hay Password trực tiếp vào tệp mã nguồn. Luôn sử dụng bộ đôi `.env` và khai báo nó vào `.gitignore` trước khi thực hiện lệnh `git commit`[cite: 1, 2].