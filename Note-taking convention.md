1. **Quy tắc đặt tên file**
- **Ngôn ngữ**: Sử dụng tiếng Anh để dễ dàng chia sẻ và tránh lỗi khi zip hoặc đồng bộ.
- **Không sử dụng ký tự đặc biệt**: Tránh các ký tự như `#`, `/`, `\`, hoặc Unicode.
- **Ignore file**: Các file có tiền tố `_ignore_` sẽ bị bỏ qua trong quá trình quản lý hoặc đồng bộ.
2. **Cấu trúc thư mục**
- **Draft**: Chứa các ý tưởng thô, chưa được xử lý.
- **Entry**: Chứa các note tổng hợp, kết nối nhiều note khác.
- **Reference**: Chứa các note dựa trên tài liệu hoặc nguồn bên ngoài (sách, bài viết, AI). Cần ghi rõ nguồn.
- **Permanent**: Chứa các note đã được xử lý, tự diễn đạt lại bằng ngôn ngữ cá nhân.
3. **Quy tắc nội dung note**
- **Ngôn ngữ**: Nội dung note viết bằng tiếng Việt để tiện diễn đạt, thuật ngữ chuyên ngành nên giữ nguyên tiếng Anh để chính xđạt
- **Tag**: Mỗi note cần có ít nhất một tag ở đầu file. Một số tag phổ biến:
    - `#topic`: Note tổng hợp thông tin của một chủ đề.
    - `#question`: Câu hỏi cần giải đáp.
    - `#code-snippet`: Note xoay quanh việc giải thích mã nguồn quan trọng.
- **Liên kết trong**: Sử dụng liên kết nội bộ Obsidian (`[[Tên note]]`) để kết nối các note liên quan.
- **Liên kết ngoài**: Đặt các liên kết không chỉ giữa các note mà còn với nguồn tham khảo bên ngoài nếu cần (sử dụng markdown link `[Name](URL)`), giúp mở rộng kiến thức và đảm bảo độ tin cậy.
- **Không sử dụng header**: Note có thể phân cấp bằng tab, nếu phân cấp quá nhiều thì nên refactor, không sử dụng header (#).
4. **Quy tắc viết nội dung**
- **Atomic Note**: Mỗi note chỉ nên chứa một ý tưởng hoặc khái niệm duy nhất.
- **Ngắn gọn, rõ ràng**: Tránh viết dài dòng, tập trung vào ý chính.
- **Nguồn tham khảo**: Ghi rõ nguồn ở cuối note nếu nội dung dựa trên tài liệu bên ngName