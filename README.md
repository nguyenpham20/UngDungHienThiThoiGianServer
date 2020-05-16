# UngDungHienThiThoiGianServer
Bước 1: Tạo thư mục chứa mã nguồn.

Với XAMPP trên Windows: Đến thư mục htdocs của Apache
Với Apache trên Linux (Ubuntu, Debian, CentOS, v.v...): Đến thư mục /var/www
Tạo một thư mục con, đặt tên là server_time. Đây sẽ là thư mục chứa mã nguồn của chúng ta.

Bước 2: Tạo file index.php

Bên trong thư mục server_time tạo một file mới, đặt tên là index.php.

Thử viết dòng chữ sau vào file index.php: "Xin chào".

Bước 3: Truy cập trang index.php từ trình duyệt

Mở trình duyệt và gõ vào địa chỉ http://localhost/server_time. Trang web sẽ hiển thị thông điệp "Xin chào".

Nếu không thấy thông điệp "Xin chào" thì chắc chắn chúng ta đã không làm tốt ở một bước nào trước đó, hãy kiểm tra lại cẩn thận, hoặc nhờ sự trợ giúp của huấn luyện viên\trợ giảng\bạn học\...

Bước 4: Hiển thị thời gian của máy chủ

Nếu bước 3 đã thành công thì có nghĩa là ứng dụng của chúng ta đang hoạt động tốt, bây giờ hãy tạo một trang web đơn giản và chèn vào đó một câu lệnh PHP để hiển thị thời gian của máy chủ.

<html>
    <head>
       <title>Thời gian hiện tại</title>
    </head>
    <body>
        <h1> Bây giờ là: <?php echo date('Y-M-d h:m:s'); ?> </h1>
    </body>
</html>
Đoạn mã ở trên bao gồm các thẻ HTML cơ bản, và một câu lệnh PHP duy nhất trong đó sử dụng hàm date(). Hàm date() có chức năng trả về thời gian theo một định dạng nhất định (Năm-Tháng-Ngày Giờ:Phút:Giây).

Chúng ta có thể thay đổi định dạng thời gian theo mong muốn của mình, chi tiết về hàm date() và cách sử dụng các định dạng thời gian có thể tham khảo ở đây: http://php.net/manual/en/function.date.php

Bước 5: Tải lại trang web ở trình duyệt để quan sát kết quả.

Hãy thử thay đổi định dạng của thời gian và tải lại trang web để quan sát thay đổi.

Chúc mừng bạn! Chúng ta đã hoàn thành ứng dụng web đầu tiên với PHP, các bước đã thực hiện bao gồm:

1. Tạo một thư mục mới bên trong htdocs (hoặc /var/www/

2. Tạo một tệp index.php để chứa mã nguồn

3. Đưa mã nguồn vào tệp index.php

4. Truy cập trình duyệt để quan sát kết quả
