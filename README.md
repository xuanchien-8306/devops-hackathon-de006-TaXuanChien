# DevOps Hackathon - Đề 006: Quản lý sinh viên (Student)

## 1. Thông tin sinh viên
| Họ và tên     | Mã sinh viên  | Lớp   | Tài khoản Linux   | GitHub        | Cổng Nginx    |
|Tạ Xuân Chiến  |PTIT-HN-084    | CNTT3 |xuanchien-8306     |xuanchien-8306 |   8080        |

## 2. Môi trường triển khai
(Hệ điều hành, phiên bản Nginx, Git, nơi chạy: VPS / máy ảo /WSL2)
Hệ điều hành: Ubuntu 22.04 LTS
phiên bản nginx: 1.18.0
git version: 2.34.1
nơi chạy : VPS

## 3. Cấu trúc dự án
hackathon/
    -README.md
    src/
        -index.html
    -screenshots/
    -nginx
    -gitignore

## 4. Cấu hình Nginx

| Tham số trong template | Giá trị đã điền | Giải thích |
post: 8080 | Cổng mà Nginx sẽ lắng nghe các yêu cầu HTTP |
server_name | localhost | Tên miền hoặc địa chỉ IP mà Nginx sẽ phục vụ |
web_root | /var/www/html | Thư mục gốc chứa các tệp HTML của trang web |
index_file | index.html | Tệp HTML chính của trang web |
ten_tai_khoan | xuanchien-8306 | Tài khoản người dùng trên hệ thống |
allow_directive | allow all | Quy tắc cho phép truy cập từ tất cả các địa chỉ IP |
## 5. Tường lửa UFW
(Các rule đã thêm + kết quả ` sudo ufw status verbose')

## 6. Các bước triển khai
(Các lệnh đã chạy thực tế, theo đúng thứ tự)

## 7. Kiểm tra & minh chứng
![Trang web](screenshots/04-website.png)

## 8. Quy trình cập nhật website
(Sửa -> commit -> push -> git pull trên server -> kiểm tra)

## 9. Sự cố gặp phải & cách khắc phục (nếu có)