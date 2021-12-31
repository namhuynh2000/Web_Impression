# Web_Impression
## Yêu cầu
Thực hiện các qui trình cần thiết trong quá trình học để hoàn thành project Hệ thống quản lý tổ
chức Hội nghị.
## Cơ sở dữ liệu
Dưới đây là mô tả các thành phần chính, có thể thêm các thành phần khác để hoàn thành chương
trình.
- Hội nghị bao gồm các thông tin: tên, mô tả ngắn gọn, mô tả chi tiết, hình ảnh, thời gian
tổ chức, địa điểm tổ chức, người tham dự (có số lượng giới hạn và phụ thuộc vào nơi tổ
chức).
- Địa điểm tổ chức có thông tin: tên, địa chỉ, sức chứa.
- Admin có các thông tin: tên, username, password (được mã hóa), email.
- User có các thông tin như admin.
- Các vấn đề ràng buộc (địa điểm không thể sử dụng chung trong cùng thời điểm), phân
quyền,…
## Các chức năng cần có
### Đối với phân hệ khách
- Màn hình chính giới thiệu chương trình và danh sách các Hội nghị với thông tin ngắn gọn
cho phép lựa chọn hình thức trình bày là: danh sách, cardview,…
- Màn hình xem chi tiết Hội nghị với đầy đủ thông tin của Hội nghị và cho phép đăng ký
tham dự (đề xuất lựa chọn nếu chưa có account thì đăng ký account, nếu đã có account
thì đăng nhập và đăng ký tham dự).
### Đối với phân hệ người dùng (user) đã đăng nhập
- Có đủ các chức năng của phân hệ Khách.
- Màn hình profile để xem và chỉnh sửa thông tin cá nhân.
- Màn hình thống kê các Hội nghị đã đăng ký tham dự (cho phép sắp xếp, tìm kiếm theo
nhiều tiêu chí).
### Đối với phân hệ Admin
- Màn hình quản lý Hội nghị: thêm mới, sửa đổi Hội nghị chưa diễn ra, chấp nhận yêu cầu
tham dự của User.
- Màn hình quản lý User: xem danh sách, ngăn chặn truy cập, sắp xếp, lọc theo nhiều tiêu
chí
## Demo
Link video: https://youtu.be/9mtJp9rVB1M
