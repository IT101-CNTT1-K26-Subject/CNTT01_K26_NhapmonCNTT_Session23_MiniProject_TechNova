# Cấu hình Trình duyệt Chuyên nghiệp (Browser Setup)

## 1. Nguyên lý Data Isolation (Cách ly dữ liệu)
Nhân viên bắt buộc phải tạo tối thiểu 2 Profile độc lập trên trình duyệt (Chrome/Edge):
- **Profile 1 (`Personal`):** Dùng cho các hoạt động cá nhân, giải trí[cite: 2].
- **Profile 2 (`TechNova_Work`):** Dùng riêng cho công việc công ty, đảm bảo tách biệt tuyệt đối Cookies, Session, lịch sử duyệt web và không bị xung đột tài khoản (Session Conflict)[cite: 2].

## 2. Cấu trúc Bookmark Manager
Tổ chức hệ thống Bookmark thành 3 thư mục gốc gọn gàng:
1. `01_Work_Dev`: Chứa liên kết các môi trường Staging, Production, GitHub Repo, Jira/Trello công ty.
2. `02_Onboarding_Docs`: Chứa tài liệu nhập môn, quy chế công ty, cẩm nang kỹ thuật.
3. `03_Tools`: Chứa công cụ hỗ trợ như Bitwarden, ColorPicker, JSON Formatter.

## 3. Quản lý Extension theo 3 nhóm chủ đề
- **Dev Suite:** JSON Viewer, Octotree (hỗ trợ đọc cây thư mục GitHub)[cite: 2].
- **Productivity Suite:** ColorPicker, Dark Reader[cite: 2].
- **Security Suite:** uBlock Origin (chặn quảng cáo độc hại), Bitwarden[cite: 2].
- *Lưu ý:* Cài đặt quyền Site Access của Extension ở chế độ **"On click"** để tiết kiệm RAM và bảo vệ quyền riêng tư[cite: 2].

## 4. Kỹ năng Chrome DevTools (F12) cơ bản
- **Kiểm tra giao diện:** Nhấn `F12` hoặc chuột phải chọn *Inspect* vào thành phần giao diện để xem cấu trúc HTML và thông số CSS Box Model[cite: 2].
- **Xử lý lỗi hiển thị:** Khi giao diện cập nhật mã nguồn mới nhưng màn hình chưa thay đổi, chuyển sang tab **Network**, tích chọn **Disable Cache**, sau đó thực hiện **Hard Reload** (`Ctrl + Shift + R`) để ép trình duyệt tải lại toàn bộ tài nguyên sạch[cite: 2].