# Xây dựng ứng dụng tư vấn pháp luật sử dụng AI

Tất cả các microservices: Ghi lại thông tin request (request logs)

Tất cả các microservices: có request_id, code, success, message, data, total

# Chi tiết các microservices

## Auth Service

- Người dùng đăng nhập bằng google
- Gửi email để xác nhận email
- Người dùng xác nhận email
- Xác thực 2FA bằng TOTP
- Chuyển 1 user thành admin (cần Role ADMIN)
- Xem thông tin cá nhân
- Cập nhật ảnh avatar

## Settings Service

- Bật tắt dark mode
- Cấu hình Model mặc định (Cấp 1, 2, 3) về độ chính xác/tốc độ
- Cài đặt "Bối cảnh cá nhân" (Tự nhập thêm ai prompt)
- Tự động phát âm thanh khi trả lời
