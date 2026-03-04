# Xây dựng ứng dụng tư vấn pháp luật sử dụng AI

Yêu cầu chức năng dự kiến:

- [ ] Ghi lại thông tin request (request logs)

- [ ] Ghi lại thông tin response: : có request_id, code, success, message, data, total

- [ ] Cài đặt người dùng (user-settings)
  - [ ] Bật tắt Dark mode
  - [ ] Bật tắt Tự động phát âm thanh khi trả lời
  - [ ] Cấu hình Model mặc định (Cấp 1, 2, 3) về độ chính xác/tốc độ
  - [ ] Cài đặt "Bối cảnh cá nhân" (Tự nhập thêm ai prompt)
  - [ ] Bật tắt Xác thực 2FA (có thể thêm sau)

<!-- local storage  -->

- [ ] Xác thực (auth)
  - [ ] Người dùng đăng nhập bằng google
    - [ ] Hệ thốngg gửi email để xác nhận
    - [ ] Người dùng xác nhận email
  - [ ] Xem thông tin cá nhân (profile)
    - [ ] Đếm thông tin số lượng sử dụng Token để tạo thống kê như github
    - [ ] Cập nhật ảnh avatar
  - [ ] Chuyển 1 user thành admin (cần Role ADMIN)
  - [ ] Xác thực 2FA bằng TOTP (có thể thêm sau)

- [ ] Thanh toán Token (dùng VNPAY sandbox)
  - [ ] Hiển thị các mức giá (mua nhiều được giảm %)
  - [ ] Người dùng mua số lượng Token
  - [ ] Lưu lịch sử giao dịch
  - [ ] Mỗi lần chat, hệ thống sẽ tính số lượng token (prompt đầu vào và response đầu ra)
  - [ ] Cửa sổ bật lên thông báo khi hết lượt dùng

- [ ] Lựa chọn nhân vật để trò chuyện
  - [ ] CRUD nhân vật (cần Role ADMIN)
  - [ ] Người dùng lựa chọn nhân vật để trò chuyện

- [ ] Cuộc trò chuyện (chat)
  - [ ] Đầu vào INPUT
    - [ ] Giao diện có phần input nhập văn bản
      - [ ] Có 1 số câu hỏi gợi ý mặc định
    - [ ] Có thể thêm micro giọng nói
      - [ ] Sóng âm (waveform animation)
    - [ ] Tải lên file tài liệu văn bản
  - [ ] Đầu ra OUTPUT
    - [ ] Trích xuất các nguồn tài liệu liên quan
    - [ ] Lịch sử cuộc trò chuyện
  - [ ] Chia sẻ cuộc trò chuyện (CRUD)
  - [ ] Ghi chú (note)
    - [ ] Người dùng có thể thả tim yêu thích cuộc trò chuyện
    - [ ] Cho phép người dùng phân loại theo chủ đề (labels)

- [ ] Thông báo (notification) - Worker
  - [ ] Gửi email chào mừng đăng ký người dùng mới
  - [ ] Thông báo cho người dùng dữ liệu văn bản mới (qua mail)
  - [ ] Thông báo cho người dùng về thanh toán (sắp hết số lượng, thành công)

- [ ] Chức năng Dashboard của ADMIN
  - [ ] Tổng số người dùng hệ thống
  - [ ] Tổng số người dùng hôm nay
  - [ ] Thống kê chi phí API (tiền trả cho OpenAI/Anthropic/Google...).
  - [ ] Thống kê doanh thu theo ngày/tháng từ VNPAY.

<!-- phê duyệt dữ liệu mới -->

<!-- Quay chờ công việc như  notebooklm  -->

<!-- tóm tắt cuộc trò chuyện -->
<!-- moderation : phê duyệt bot tự động thu hồi nếu SAI SAI, -->

<!-- Đa ngôn ngữ (Việt Nam, Có thế người nước ngoài thì sao) -->

<!-- Phân trang cho tất cả -->

<!-- thảo luận, comment (Chỉ có 1 người dùng nên khó trao đổi người khác) -->
