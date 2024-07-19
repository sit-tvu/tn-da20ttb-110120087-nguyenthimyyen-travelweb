# tn-da20ttb-110120087-nguyenthimyyen-travelweb

## Đề tài: Xây dựng website giới thiệu các địa điểm du lịch trên địa bàn tỉnh Trà Vinh

## Mục tiêu: 
Xây dựng website giới thiệu các địa điểm du lịch nhằm giúp du khách dễ dàng tra cứu
thông tin về các điểm du lịch có trên địa bàn tỉnh Trà Vinh

## Kiến trúc:  
MVC

## Phần mềm sử dụng để triển khai:
- Visual Studio Code
- Xampp
  

## Hướng dẫn cài đặt
- Cài đặt PHP (phiên bản 8.2 hoặc cao hơn)
- Cài đặt Composer
- Cài đặt Xampp
- Tải dự án về máy từ github bằng lệnh <git clone> theo đường dẫn sau: https://github.com/yen0926/tn-da20ttb-110120087-nguyenthimyyen-travelweb.
- Import cơ sở dữ liệu từ tourist.sql từ thư mục src.
- Thay đổi cài đặt trong tệp .evn:
	DB_CONNECTION
	DB_DATABASE
	DB_USERNAME
	DB_PASSWORD
- Truy cập theo đường dẫn public/storage và tiến hành xoá thư mục storage. Sau đó mở terminal trong Visual Studio Code chạy lệnh: php artisan storage:link, tiếp theo chạy lệnh php artisan serve
- Mở trình duyệt Chrome và truy cập link: localhost:8000
