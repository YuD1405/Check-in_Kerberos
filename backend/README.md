│── backend/                # Backend (C++ Crow + MySQL + Kerberos)
│   ├── src/                # Code nguồn
│   │   ├── main.cpp        # File chính chạy server
│   │   ├── auth.cpp        # Xử lý xác thực Kerberos
│   │   ├── database.cpp    # Kết nối MySQL
│   │   ├── routes.cpp      # API check-in, xác thực
│   │   ├── CMakeLists.txt  # CMake build file
│   ├── include/            # Header files (.h)
│   ├── config/             # File cấu hình (MySQL, Kerberos)
│   │   ├── database.json   # Cấu hình kết nối MySQL
│   │   ├── krb5.conf       # Cấu hình Kerberos
│   ├── Dockerfile          # Nếu triển khai bằng Docker
│   ├── README.md           # Hướng dẫn backend