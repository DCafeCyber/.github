# DCofe Cyber Management
## Giới thiệu phần mềm
Ứng dụng [**DCafe Cyber Management**](https://DCafeCyber.github.io) đóng vai trò quan trọng trong việc quản lý cơ sở kinh doanh Cofe/Net, Xử lý các giao dịch và quản lý máy trạm một cách nhanh chóng. Đặc biệt, DCafe được hướng đến như một phần mềm mã nguồn mở, triển khai nhanh chóng và minh bạch mã nguồn.
## Chức năng chính
### Mục tiêu hoạt động
Mục tiêu hoạt động cơ bản:
- Danh sách máy tính
- Trạng thái máy tính (Đóng - Mở - Đang Sử Dụng)
- Quản Lý Khách Hàng (Tính Theo Giờ)
- Thống kê Thu Nhập (N/A)
### Quản Lý Máy Tính
- **Create:** Thêm máy mới (ID, IP, Cấu Hình)
- **Read:** Xem danh sách các máy đang có
- **Update:** Cập nhập thông tin máy (Trạng thái máy)
- **Delete:** Nếu máy tính không còn được sử dụng nữa
### Quản Lý Phiên Sử Dụng Máy
- **Create:** Khi khách bắt đầu sử dụng máy => tạo phiên sử dụng
- **Read:** Xem danh sách các phiên đang chạy
- **Update:** Kết thúc phiên, tính thời gian, tính tiền
- **Delete:** Xoá phiên (nếu cần xóa lịch sử)
### Quản Lý Khách Hàng
- **Create:** Thêm tài khoản khách hàng (nếu có hệ thống đăng nhập)
- **Read:** Xem danh sách khách hàng
- **Update:** Cập nhật thông tin cá nhân, số dư tài khoản
- **Delete:** Xoá tài khoản
### Quản Lý Dịch Vụ Thêm
- **Create:** Thêm dịch vụ
- **Read:** Xem danh sách dịch vụ
- **Update:** Cập nhật thông tin dịch dụ, giá cả
- **Delete:** Xoá dịch vụ nếu không còn được sử dụng nữa
### Thống kê (đọc dữ liệu - Read only)
- Tổng số giờ sử dụng hôm nay
- Tổng tiền thu được theo ngày/tháng
- Lọc theo từng máy, từng khách
### Tài khoản
- Phân quyền tài khoản Chủ Quán (Admin Of Admin)
- Phân quyền tài khoản Admin
- Phân quyền tài khoản Nhân viên trực ca
### Thanh toán
- Chấp nhận thanh toán bằng mã QR (Chuyển khoản)
- Chấp nhận thanh toán tiền mặt
### Logs
- Chức năng in bill (Khách hàng)
- Chức năng in order (Product order)
### Tìm kiếm
- Tìm máy tính theo tên
- Lọc tài khoản theo chức vụ
- Tìm tài khoản theo tên
- Lọc tài khoản theo số tiền đã nạp (Hội viên)
### Order (Đặt hàng)
- Nạp tiền vào tài khoản
- Đặt món có trong menu

## Đóng góp
* [**Trần Nguyễn Tuấn Anh**](https://github.com/dopaemon)
* [**Phan Văn Nhật Trường**](https://github.com/Girrint)
* [**Lê Thị Mai Anh**](https://github.com/)
* [**Nguyễn Minh Anh**](https://github.com/)
## Triển Khai
* [**Manifest**](https://github.com/DCafeCyber/manifest)
