# Check-in_Kerberos
HỆ THỐNG ĐIỂM DANH TỰ ĐỘNG SỬ DỤNG KERBEROS AUTHENTICATION
1. Giới Thiệu
1.1 Mô Tả
Hệ thống điểm danh tự động sử dụng Kerberos Authentication nhằm tối ưu quy trình điểm danh trong trường học và doanh nghiệp. Người dùng sẽ được xác thực tự động thông qua Active Directory hoặc MIT Kerberos thay vì nhập mật khẩu thủ công.
1.2 Mục Tiêu
Xây dựng hệ thống điểm danh điện tử bảo mật và nhanh chóng.
Tích hợp Kerberos Authentication để tự động nhận diện user.
Lưu trữ dữ liệu điểm danh vào cơ sở dữ liệu.
Cung cấp giao diện web cho user và admin quản lý.
2. Công Nghệ Sử Dụng
Ngôn ngữ Backend: C++ (CrowCpp / Boost.Beast)
Ngôn ngữ Frontend: React.js / Vue.js
CSDL: PostgreSQL / MySQL
Xác thực: MIT Kerberos / Active Directory
Môi trường Phát triển: Visual Studio / VS Code
Hệ Điều Hành: Windows 10/11 hoặc Windows Server
3. Yêu Cầu Phần Cứng
Server:
CPU: Intel Xeon hoặc AMD Ryzen 5 trở lên
RAM: Tối thiểu 8GB
Ổ cứng: SSD tối thiểu 256GB
Hệ điều hành: Windows Server 2019 / Linux (Ubuntu 20.04)
Client:
CPU: Intel Core i5 / AMD Ryzen 3 trở lên
RAM: Tối thiểu 4GB
Trình duyệt hỗ trợ JavaScript (Chrome, Firefox, Edge)
4. Kiến Trúc Hệ Thống
4.1 Sơ Đồ Kiến Trúc
Hệ thống gồm các thành phần:
Frontend (React.js/Vue.js): Giao diện người dùng.
Backend (C++ - CrowCpp): API xử lý điểm danh.
Database (PostgreSQL/MySQL): Lưu trữ dữ liệu.
Kerberos Authentication: Xác thực user.
4.2 Kế Hoạch Theo Giai Đoạn
Giai đoạn 1 (1-2 tuần): Phân tích yêu cầu, xác định công nghệ.
Giai đoạn 2 (2-3 tuần): Thiết kế kiến trúc, chuẩn bị cơ sở dữ liệu.
Giai đoạn 3 (3-5 tuần): Phát triển Backend và API.
Giai đoạn 4 (5-7 tuần): Xây dựng Frontend và giao diện.
Giai đoạn 5 (7-8 tuần): Tích hợp Kerberos Authentication.
Giai đoạn 6 (8-9 tuần): Kiểm thử và sửa lỗi.
Giai đoạn 7 (9-10 tuần): Triển khai và viết báo cáo.
5. Đánh Giá Dự Kiến
Khó khăn:
Cài đặt Kerberos Authentication đồi hỏi cấu hình Active Directory.
Việc tích hợp C++ với PostgreSQL có thể gây khó khăn ban đầu.
Debug API trong C++ tốn nhiều thời gian hơn so với C#.
Giải pháp:
Dùng Active Directory để xác thực nhanh hơn.
Debug API bằng Postman trước khi tích hợp với Frontend.
6. Kết LuẬn
Hệ thống điểm danh tự động sử dụng Kerberos sẽ giúp giảm tối đa thao tác điểm danh thủ công, đảm bảo bảo mật và đồng bộ trong doanh nghiệp hoặc trường học. Việc tích hợp C++ giúp hệ thống chạy nhanh và hiệu quả.


