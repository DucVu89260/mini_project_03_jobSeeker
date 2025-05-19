# Website for Job-seeker
_*(Dự án vì cộng đồng - Cho đi là còn mãi)*_
## Đối tượng sử dụng
### Quản trị viên:
* Quản lý trang thông tin: Banner, giới thiệu
* Quản lý người dùng
* Quản lý file: JD, CV

### Nhà tuyển dụng:
* Đăng bài tuyển dụng
(tên công ty, địa điểm, remote?, partime?, mức lương, ngôn ngữ, yêu cầu, file JD)
* Tìm kiếm CV
* Chỉnh sửa thông tin các nhân (Công ty liên hệ, thông tin liên hệ)

### Ứng viên:
* Tìm kiếm công việc (công ty)
(mức lương, địa điểm, ngôn ngữ, trình độ, yêu cầu bằng cấp - chứng chỉ, số lượng)
* Đăng CV
* Xem danh sách công việc (sắp xếp ngẫu nhiên)
* Báo cáo vi phạm: Công ty, cá nhân
(lừa đảo, spam, không liên hệ được, thông tin sai)

## Phân tích chức năng
### Đăng bài tuyển dụng

| Các tác nhân  | Nhà tuyển dụng |
| ------------- |:-------------:|
| Mô tả     | Đăng bài tuyển dụng     |
| Kích hoạt     | Người dùng ấn nút “đăng bài tuyển dụng” trên thanh menu   |
| Đầu vào      | Tên công ty<br> Tên công việc<br> Địa điểm: Thành phố - quận (select2 - load về local)<br> Có remote không (radio)<br> Có partime không (radio)<br> Mức lương (slide bar)<br> Ngôn ngữ (multiple select2)<br> Yêu cầu thêm (text)  |
| Trình tự xử lý     | |
| Đầu ra      | Đúng:<br>Chuyển hướng tới giao diện quản lý và thông báo thành công<br>Sai:<br>Chuyển hướng về trang đăng nhập và thông báo lỗi     |
| Lưu ý     | *Regex: Điều kiện validate cho các thông tin đầu vào     |

## Bản quyền
_*dv89260*_

_*It's a free website anw!*_
