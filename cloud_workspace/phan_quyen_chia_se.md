# Hướng dẫn Vận hành Không gian Cộng tác Đám mây (Cloud Workspace)

## 1. Mô hình Hybrid Workflow
- **Local Storage:** Lưu trữ và thao tác trực tiếp trên ổ cứng máy tính cá nhân giúp tốc độ đọc/ghi đạt mức tối đa[cite: 2].
- **Cloud Storage:** Kích hoạt đồng thời Google Drive for Desktop (Auto Sync) để tự động sao lưu dữ liệu lên đám mây và kích hoạt tính năng *Version History*[cite: 2].

## 2. Bảng phân quyền chia sẻ Google Drive chuẩn doanh nghiệp
| Đối tượng phân quyền | Mức quyền hạn (Permission) | Ghi chú & Ràng buộc bảo mật |
|----------------------|-----------------------------|-------------------------------|
| Chủ sở hữu (Owner) | **Editor** (Toàn quyền) | Có quyền chỉnh sửa, xóa và quản lý thành viên[cite: 2]. |
| Đồng đội cùng dự án | **Editor** (Giới hạn) | **Bắt buộc** tắt tùy chọn *“Editors can change permissions”*[cite: 2]. |
| Người góp ý / Mentor | **Commenter** | Chỉ để lại nhận xét/đóng góp, không sửa trực tiếp tệp gốc[cite: 2]. |
| Người xem tham khảo | **Viewer** (Restricted) | Chỉ định danh sách Email cụ thể được truy cập, tuyệt đối không dùng chế độ mở công khai[cite: 2]. |

## 3. Quy tắc giao tiếp nhóm (Lark / Slack)
- **Kênh chuyên biệt:** Sử dụng `#onboarding` để hỏi đáp với Mentor, `#dev-<ten-du-an>` cho thảo luận kỹ thuật và `#thong-bao` (chỉ đọc) cho thông tin chung.
- **Quy tắc nhắn tin:** Luôn áp dụng *Reply in Thread*, *Tagging* đúng người cần hỗ trợ, tránh bẫy *No-Hello* và không spam `@all` ngoài giờ làm việc[cite: 1, 2].