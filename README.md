# SocialNetwork - Mạng Xã Hội Cựu Sinh Viên

Hệ thống mạng xã hội dành cho cựu sinh viên, giảng viên và quản trị viên trường đại học, hỗ trợ chia sẻ thông tin, tương tác xã hội, khảo sát và chat trực tuyến.

 Demo hệ thống đã được triển khai online:  
- **Frontend:** https://social-network-frontend-omega.vercel.app/  
- **Backend API:** https://socialnetwork-backend-n201.onrender.com/socialNetwork

## ⚠️ Lưu ý khi truy cập Demo

Backend được deploy trên Render (Free Tier), do đó **server sẽ tự động chuyển sang chế độ sleep khi không có request trong một khoảng thời gian**.  

⏳ Khi truy cập lần đầu, backend có thể mất **khoảng 5 phút để khởi động lại** trước khi API sẵn sàng.

Sau khi server đã hoạt động, các request tiếp theo sẽ phản hồi nhanh hơn.

## 🏗️ Kiến trúc Hệ thống

Dự án được chia thành hai phần chính:

1.  **[Backend (Spring Boot)](file:///d:/Code/Github/SocialNetwork/socialNetwork-Backend)**: Cung cấp API RESTful, quản lý cơ sở dữ liệu, xác thực JWT và xử lý nghiệp vụ.
2.  **[Frontend (ReactJS)](file:///d:/Code/Github/SocialNetwork/socialNetwork-Frontend)**: Giao diện người dùng hiện đại, tương tác thời gian thực và quản lý trạng thái.

---

## 🛠️ Công nghệ Sử dụng

### Backend
- **Ngôn ngữ:** Java 21+
- **Framework:** Spring MVC, Spring Security
- **Xác thực:** JWT (JSON Web Token)
- **Cơ sở dữ liệu:** MySQL (Hibernate ORM)
- **Lưu trữ:** Cloudinary (Ảnh), Firebase (Chat Metadata)
- **Email:** Spring Mail

### Frontend
- **Framework:** ReactJS
- **Routing:** React Router
- **Giao diện:** Bootstrap / TailwindCSS
- **Chat:** Firebase Realtime Database
- **API Client:** Axios

---

## ✨ Tính năng Chính

-   **Xác thực & Phân quyền:** Phân quyền chi tiết cho Admin, Giảng viên và Cựu sinh viên.
-   **Quản lý Bài viết:** Đăng bài, like, thả tim và bình luận đa dạng.
-   **Khảo sát & Sự kiện:** Admin có thể tạo khảo sát và gửi thông báo qua email.
-   **Chat Thời gian thực:** Tích hợp Firebase cho trải nghiệm nhắn tin mượt mà.
-   **Trang Quản trị:** Dashboard thống kê người dùng, bài viết và duyệt thành viên (sử dụng Thymeleaf).

---

## 🚀 Bắt đầu

### Phía Backend
1. Di chuyển vào thư mục backend.
2. Cấu hình database trong `databases.properties`.
3. Chạy với Tomcat server (khuyên dùng bản 11.0.4).
4. Chi tiết xem tại: [Backend README](file:///d:/Code/Github/SocialNetwork/socialNetwork-Backend/README.md)

### Phía Frontend
1. Di chuyển vào thư mục frontend.
2. Chạy `npm install` để cài đặt thư viện.
3. Chạy `npm start` để khởi động ứng dụng.
4. Chi tiết xem tại: [Frontend README](file:///d:/Code/Github/SocialNetwork/socialNetwork-Frontend/README.md)

---

## 👥 Nhóm Thực hiện
- **Trần Quang Trường**
- **Email:** tranquangtruong25@gmail.com
- **GitHub:** [QuangTruongPractice](https://github.com/QuangTruongPractice)
