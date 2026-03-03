# Xây dựng ứng dụng tư vấn pháp luật sử dụng AI

Yêu cầu chức năng dự kiến:

- [ ] Ghi lại thông tin request (request logs)
- [ ] Tải file
  - [ ] Tải ảnh avatar
  - [ ] Tải tài liệu văn bản
- [ ] Cài đặt hệ thống (admin-settings)
  - [ ] Bắt buộc Xác thực 2FA
  - [ ] Bắt buộc Xác thực email
- [ ] Cài đặt người dùng (user-settings)
  - [ ] Bật tắt dark mode
  - [ ] Bật tắt Xác thực 2FA
  - [ ] Cấu hình Model (Cấp 1, 2, 3) về độ chính xác/tốc độ
  - [ ] Cài đặt Bối cảnh cá nhân (Tự nhập thêm ai prompt)
- [ ] Xác thực (auth)
  - [ ] Người dùng đăng nhập bằng google
    - [ ] Xác nhận email
  - [ ] Xác thực 2FA bằng TOTP
  - [ ] Thông tin tài khoản (profile)
    - [ ] Đếm thông tin số lượng sử dụng để tạo thống kê như github
  - [ ] Chuyển 1 user thành admin (ADMIN)
- [ ] Thanh toán (payment) (dùng VNPAY sandbox)
  - [ ] Người dùng mua số lượng câu hỏi
  - [ ] Hiển thị các mức giá (mua nhiều được giảm %)
  - [ ] Lịch sử giao dịch
  - [ ] Cửa sổ bật lên thông báo khi hết lượt dùng
- [ ] Cuộc trò chuyện (chat)
  - [ ] Giao diện có phần input nhập văn bản
    - [ ] Có 1 số câu hỏi gợi ý mặc định
  - [ ] Có thể thêm micro giọng nói
    - [ ] Sóng âm (waveform animation)
  - [ ] Trích xuất các nguồn tài liệu liên quan
  - [ ] Lịch sử cuộc trò chuyện
  - [ ] Chia sẻ link public cuộc trò chuyện (CRUD)
  - [ ] Đánh giá mức độ hài lòng cuộc trò chuyện
  - [ ] Chức năng nâng cao: Tải lên file văn bản ?
  - [ ] Chức năng nâng cao: Lựa chọn nhân vật để trò chuyện (roleplays) ?
- [ ] Ghi chú (note)
  - [ ] Người dùng có thể đánh dấu lưu lại cuộc trò chuyện (bookmark)
  - [ ] Cho phép người dùng phân loại theo chủ đề (labels)
- [ ] Thông báo (notification)
  - [ ] Gửi email chào mừng đăng ký người dùng mới
  - [ ] Gửi email thiết bị mới
  - [ ] Thông báo cho người dùng dữ liệu văn bản mới (qua mail)
  - [ ] Thông báo cho người dùng về thanh toán (sắp hết số lượng, thành công)

- Báo cáo
- Dashboard của admin
  Tổng số người dùng hệ thống
  Tổng số người dùng hôm nay

<!-- phê duyệt dữ liệu mới -->

<!-- Quay chờ công việc như  notebooklm  -->

<!-- tóm tắt cuộc trò chuyện??? -->
<!-- moderation : phê duyệt bot tự động thu hồi nếu SAI SAI, -->

<!-- Đa ngôn ngữ (Việt Nam, Có thế người nước ngoài thì sao) -->

<!-- Phân trang cho tất cả -->

<!-- thảo luận, comment??? (Chỉ có 1 người dùng nên khó trao đổi người khác) -->
