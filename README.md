 Lab7-Postman-Testing
Bài tập Lab 7 - API Testing bằng Postman Web

1. Mục tiêu bài lab
+ Làm quen và sử dụng thành thạo công cụ Postman (phiên bản Web).
+ Thực hiện kiểm thử các HTTP Methods cơ bản (GET, POST, DELETE).
+ Quản lý và lưu trữ kết quả kiểm thử bằng GitHub.

2. API sử dụng
+ API Thử nghiệm: JSONPlaceholder API (https://jsonplaceholder.typicode.com).

3. Các Test Case thực hiện
  Test Case 1: GET tất cả bài viết
+ URL:"https://jsonplaceholder.typicode.com/posts"
+ Kết quả: Status Code 200 OK, hiển thị danh sách toàn bộ bài viết dạng JSON.
<img width="1306" height="943" alt="post-product" src="https://github.com/user-attachments/assets/36b0c869-6f48-4b3a-a783-d148e7626bbf" />


  Test Case 2: GET bài viết theo ID
+ URL: "https://jsonplaceholder.typicode.com/posts/1"
+ Kết quả: Status Code 200 OK, thông tin trả về đúng bài viết có ID = 1 và userId = 1.

  Test Case 3: POST thêm bài viết mới
+ URL: "https://jsonplaceholder.typicode.com/posts"
+ Kết quả: Status Code 201 Created, hệ thống tiếp nhận dữ liệu body và trả về ID mới tạo là 101.

  Test Case 4: DELETE bài viết theo ID
+ URL: "https://jsonplaceholder.typicode.com/posts/1"
+ Kết quả: Status Code 200 OK, hệ thống phản hồi thành công với object rỗng `{}` (đã xóa dữ liệu).


  Nhận xét kết quả:  Tất cả các request đều hoạt động chính xác với cấu hình kiểm thử.
