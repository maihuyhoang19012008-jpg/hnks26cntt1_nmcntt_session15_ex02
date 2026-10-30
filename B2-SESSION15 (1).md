


# VẤN ĐỀ 
 
muốn chia sẻ file này cho các trưởng bộ phận để xem và nhận xét, nhưng một nhân viên đã vô tình gửi link với quyền Editor cho một ứng viên bên ngoài.
# YÊU CẦU 
- Áp dụng Quy tắc Cờ Đỏ Bảo mật để thiết lập lại toàn bộ quyền truy cập cho tệp danh sách ứng viên.
-  Sử dụng tính năng Suggesting Mode để các trưởng bộ phận có thể góp ý mà không làm thay đổi dữ liệu gốc khi chưa được duyệt.
# CÁCH LÀM 
- Bản thiết kế phân quyền: Bảng phân loại đối tượng tương ứng với các mức quyền truy cập an toàn nhất.
- Kịch bản xử lý sự cố: Quy trình 3 bước xử lý khi phát hiện dữ liệu bị chia sẻ sai quyền.
## PHẦN 1 : Bảng phân  quyền truy cập dữ liệu 
|Chức Vụ|Cấp Quyền truy cập  |
|-|-|
|Nhân  Viên |Xem |
|Trưởng Phòng Nhân Sự  | Quyền chỉnh sửa |
|Trưởng Phòng  Bộ Phận  |Quyền  COMMENT|
|Ứng viên bên ngoài  |kKhông có quyền  |
| 
## PHẦN 2 : Quy trình 3 bước sử lý khi bị mất chia sẽ sai quyền truy cập 
B1: Ngăn chặn ngay lập tức quyền truy cập khi cấp quyền sai 
B2: Xem lại  lịch sử chỉnh sửa truy cập.Điều tra và khác phục lại báo cáo sự cố sảy ra 
B4: Thay đổi đúng quyền truy cập 
