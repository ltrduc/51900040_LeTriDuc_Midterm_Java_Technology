1. Nguyên tắc, mẫu và thực hành phát triển phần mềm được áp dụng trong dự án này có thể bao gồm:
    •	Nguyên tắc SOLID: Đảm bảo rằng các lớp và phương thức được thiết kế để có tính kế thừa, đơn trách nhiệm và thực thi nguyên tắc mở / đóng.
    •	Mẫu thiết kế MVC (Model-View-Controller): Sử dụng kiến trúc phân lớp này để phân tách logic xử lý, giao diện người dùng và dữ liệu.
    •	Sử dụng Hibernate để cung cấp một cách tiếp cận đơn giản hóa việc lưu trữ dữ liệu và phát triển các tác vụ truy vấn dữ liệu.
    •	Sử dụng Spring Boot để cung cấp cấu hình mặc định và hỗ trợ nhiều loại ứng dụng phức tạp.
    •	Sử dụng Thymeleaf để phát triển các trang web mà có thể được tùy chỉnh bởi nhà phát triển.
    •	Sử dụng Maven để quản lý các thư viện phụ thuộc và quản lý quy trình xây dựng và triển khai dự án.
    •	Sử dụng Lombok để tạo các lớp POJO (Plain Old Java Object) nhẹ hơn và đơn giản hóa mã.

2. Cấu trúc của thư mục dự án
    ├───src
    │   ├───main
    │   │   ├───java\midterm\commerce
    │   │   │           ├───api
    │   │   │           │   ├───controller
    │   │   │           │   ├───model
    │   │   │           │   ├───repository
    │   │   │           │   ├───request
    │   │   │           │   ├───response
    │   │   │           │   ├───service
    │   │   │           │   └───upload
    │   │   │           └───user
    │   │   │               └───controller
    │   │   └───resources
    │   │       ├───static
    │   │       └───templates

- Thư mục "src" chứa mã nguồn của dự án.
- Thư mục "main" là nơi chứa mã nguồn chính của ứng dụng.
- Thư mục " java\midterm\commerce" là đường dẫn đến tên module của ứng dụng.
    * Thư mục "api" là nơi chứa các lớp và tài nguyên liên quan đến API của ứng dụng.
        •	Thư mục "controller" là nơi chứa các lớp điều khiển (Controller) trong mô hình MVC (Model-View-Controller).
        •	Thư mục "model" chứa các lớp đại diện cho dữ liệu và các đối tượng của ứng dụng.
        •	Thư mục "repository" chứa các lớp cung cấp khả năng truy cập dữ liệu vào cơ sở dữ liệu.
        •	Thư mục "request" chứa các lớp đại diện cho yêu cầu gửi đến API.
        •	Thư mục "response" chứa các lớp đại diện cho kết quả trả về từ API.
        •	Thư mục "service" chứa các lớp cung cấp các dịch vụ cho API.
        •	Thư mục "upload" chứa các lớp quản lý tải lên tệp tin.
    * Thư mục "user" là nơi chứa các lớp và tài nguyên liên quan đến người dùng của ứng dụng.

- Thư mục "resources" chứa các tài nguyên như tệp cấu hình, tệp SQL, tệp CSS, JavaScript và các tài nguyên khác.
    •	Thư mục "static" chứa các tài nguyên tĩnh như tệp CSS, JavaScript và hình ảnh.
    •	Thư mục "templates" chứa các mẫu HTML để hiển thị nội dung của ứng dụng.

3. Các bước chạy dự án và các thao tác chức năng
Để chạy dự án và sử dụng các chức năng, chúng ta có thể xem video hướng dẫn tại đường link: https://youtu.be/4lmDC9Eg1OA hoặc xem file videoDemo.mp4 trong thư mục "videoDemo". Video này sẽ hướng dẫn các bước để chạy dự án và thực hiện các yêu cầu đã nêu trong đề bài.

4. Các lệnh CURL đầy đủ hoặc ảnh chụp nhanh Postman để xác minh các API
	Để xác minh các CURL thì chúng ta có thể truy cập vào đường link sau https://documenter.getpostman.com/view/18201727/2s93RTPrbD hoặc có thể import file “java_api_v1.postman_collection.json” trong thư mục "postmanApi" vào trong Postman để có thể xem các API đã tạo.
Tài liệu này là tài liệu API của đề bài được xây dựng bằng Postman. Nó cung cấp thông tin về các yêu cầu API, các tham số yêu cầu, các phản hồi API và các mã lỗi. Tài liệu này cho phép người dùng cuối và nhà phát triển có thể tìm hiểu về cách sử dụng API của ứng dụng và các yêu cầu API khác nhau mà họ có thể gửi đến ứng dụng.
Tài liệu được tổ chức thành các phần khác nhau, bao gồm "category", "product", "user", "cart", order. Mỗi phần bao gồm một số yêu cầu API khác nhau và cung cấp thông tin về cách sử dụng các yêu cầu đó.
Mỗi yêu cầu API được mô tả chi tiết, bao gồm URL của yêu cầu, phương thức HTTP được sử dụng (GET, POST, PUT, DELETE), các tham số yêu cầu, định dạng dữ liệu đầu vào và đầu ra, và các thông tin khác liên quan đến yêu cầu đó.
Tài liệu cũng cung cấp ví dụ về cách sử dụng các yêu cầu API bằng cách sử dụng Postman để gửi yêu cầu và hiển thị phản hồi của ứng dụng. Tài liệu này là một tài liệu quan trọng cho người dùng cuối và nhà phát triển để hiểu và tương tác với ứng dụng của mình
	

