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

<!-- Supabase -->

## Settings Service

- Bật tắt dark mode
- Cấu hình Model mặc định (Cấp 1, 2, 3) về độ chính xác/tốc độ
- Cài đặt "Bối cảnh cá nhân" (Tự nhập thêm ai prompt)
- Tự động phát âm thanh khi trả lời

## Token Service

- Hiển thị các mức giá (mua nhiều được giảm %)
- Người dùng mua số lượng Token
- Lưu lịch sử giao dịch
- Mỗi lần chat, hệ thống sẽ tính số lượng token (prompt đầu vào và response đầu ra)
- Cửa sổ bật lên thông báo khi hết lượt dùng
- Đếm thông tin số lượng sử dụng để tạo thống kê như github

<!-- - Thanh toán (payment) (dùng VNPAY sandbox) -->
