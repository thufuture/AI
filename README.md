# 🎓 AI Exam Studio - Bộ 5 Đề Ôn Thi AI

> **500 câu trắc nghiệm, 100 câu tự luận trong các đề và một đề tự luận tổng hợp riêng, kèm rubric và chấm bằng DeepSeek.**

---

### 🌐 Trải nghiệm trực tiếp trên Web:
👉 **[https://thufuture.github.io/AI/](https://thufuture.github.io/AI/)**

*(Hoặc: [https://thufuture.github.io/AI/Bo_5_De_On_Thi_AI.html](https://thufuture.github.io/AI/Bo_5_De_On_Thi_AI.html))*

---

### 📂 Cấu trúc Repository:
- `Bo_5_De_On_Thi_AI.html`: Giao diện ứng dụng ôn thi AI tương tác trực tiếp trên trình duyệt.
- `tools/build_exam.js`: Script build & xử lý dữ liệu ngân hàng đề thi.
# Bộ đề ôn thi AI

## Tài liệu học tự luận

Đọc [SO_TAY_ON_THI_TU_LUAN_AI.md](SO_TAY_ON_THI_TU_LUAN_AI.md) trước khi làm đề. Tài liệu tổng hợp dạng bài, kiến thức cần học, khung trả lời và đáp án mẫu.

Mở PowerShell tại thư mục này và chạy:

```powershell
node server.js
```

Sau đó mở `http://localhost:3000` để làm bài và dùng DeepSeek chấm tự luận.

- Mỗi đề: 100 câu trắc nghiệm + 20 câu tự luận tình huống.
- API key nằm trong `.env`, không được nhúng vào HTML và đã được chặn bởi `.gitignore`.
- Có thể đổi model bằng biến `DEEPSEEK_MODEL` trong `.env`.
