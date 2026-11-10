# Bộ kỹ năng Tự Tra cứu & Gỡ lỗi (Troubleshooting Guide)

## 1. Kỹ năng Tìm kiếm Nâng cao (Google Search Operators)
Thay vì gõ câu hỏi văn nói thông thường, hãy bóc tách từ khóa kỹ thuật theo công thức:
- **Toán tử `site:`:** Giới hạn phạm vi tìm kiếm trên các nguồn uy tín.
  - *Ví dụ:* `site:stackoverflow.com "VS Code" "Terminal process failed"`[cite: 2]
- **Dấu ngoặc kép `""`:** Tìm kiếm chính xác từng ký tự dòng thông báo lỗi nguyên văn[cite: 2].
- **Dấu trừ `-`:** Loại bỏ các từ khóa nhiễu hoặc nội dung quảng cáo, phiên bản cũ[cite: 2].
  - *Ví dụ:* `cai dat git windows -quangcao -crack`[cite: 2]

## 2. Đọc hiểu nguồn tham khảo cộng đồng
- **StackOverflow:** Ưu tiên đọc các câu trả lời có dấu tích xanh (*Accepted Answer*) hoặc điểm *Upvote* cao; luôn kiểm tra năm đăng bài để tránh dùng giải pháp của các phiên bản phần mềm đã lỗi thời trên 5 năm[cite: 1, 2].
- **GitHub Issues:** Kiểm tra kỹ trạng thái của Issue là `Open` hay `Closed`, đồng thời tìm kiếm các giải pháp tạm thời (*Workaround*) được cộng đồng chia sẻ dưới phần bình luận[cite: 1, 2].

## 3. Công thức Prompt AI chuẩn 3 thành phần
Khi cần nhờ trợ lý AI (ChatGPT / Gemini) hỗ trợ giải thích lỗi, hãy cấu trúc câu hỏi theo đúng 3 phần sau[cite: 1, 2]:
1. **Ngữ cảnh (Context):** Mô tả vai trò và môi trường đang thao tác.
2. **Lỗi nguyên văn (Error Log):** Cung cấp chính xác dòng thông báo lỗi màu đỏ từ màn hình.
3. **Yêu cầu (Task):** Đưa ra câu hỏi cụ thể cần giải quyết.

> **Ví dụ Prompt mẫu:**
> *"Ngữ cảnh: Em là nhân viên mới đang chạy Visual Studio Code trên hệ điều hành Windows 11.*
> *Lỗi nguyên văn: 'Access is denied. Run as administrator.'*
> *Yêu cầu: Hãy giải thích nguyên nhân bằng tiếng Việt đơn giản và cung cấp 3 bước sửa lỗi an toàn."*[cite: 2]

## 4. Bug Reporting Framework (4 bước chuẩn hóa khi cần gửi IT hỗ trợ)
Tuyệt đối không nhắn tin mù mờ kiểu *"Anh ơi máy em bị lỗi giúp em với"*[cite: 1, 2]. Khi gửi yêu cầu hỗ trợ cho bộ phận IT hoặc đồng nghiệp, phải trình bày theo chuẩn 4 bước[cite: 1, 2]:
- **Context (Ngữ cảnh):** Đang làm gì, ở phần mềm/công cụ nào[cite: 1, 2]?
- **Expected (Kỳ vọng):** Kết quả đúng mong đợi là gì[cite: 2]?
- **Actual (Thực tế):** Sự cố thực tế xảy ra như thế nào[cite: 2]?
- **Log / Screenshot (Minh chứng):** Đính kèm ảnh chụp màn hình terminal hoặc đoạn mã log lỗi[cite: 2].