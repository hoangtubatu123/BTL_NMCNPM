## Cách deploy project

- Sử dụng tomcat server
- Chạy file database.sql => tạo ra database
- Tạo resource database jdbc/yourcart như trong bài giảng
- Sửa file context.xml trong folder conf của tomcat như sau: (tuỳ chỉnh theo user và password database)

  <img src="https://i.imgur.com/WUm0RR1.png">

- Compile các thư mục jar như hình dưới đây: File => Project Structure => Modules

    <img src="https://i.imgur.com/SlO0VTL.png">

- Tạo file config.properties trong folder javaCode/yourcart như sau:
  <img src="https://i.imgur.com/2ChNxcd.png">
  với username và password theo database trong máy của mình

- Run project
- Để chạy chương trình với tài khoản admin (username: cuong1, password: 123456)
