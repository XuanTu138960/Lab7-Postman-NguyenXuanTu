LAB 7 - POSTMAN

1. Thông tin sinh viên

- Họ và tên: Nguyễn Xuân Tú
- Bài thực hành: Lab 7
- Nội dung: API Testing with Postman

2. Mục tiêu

- Làm quen với công cụ Postman.
- Biết cách gửi HTTP Request.
- Thực hành các phương thức GET, POST, PUT và DELETE.
- Kiểm tra Response của API.
- Thực hiện kiểm thử API cơ bản.

3. Công cụ sử dụng

- Postman
- GitHub
- JSONPlaceholder API

4. Thực hành GET

Request

GET:

https://jsonplaceholder.typicode.com/posts/1

Kết quả

![GET Request](screenshots/get-request.png)


5. Thực hành POST

Request

POST:

https://jsonplaceholder.typicode.com/posts

Body

```json
{
    "title": "Lab 7 Postman",
    "body": "Test POST request",
    "userId": 1
}
6. Thực hành PUT
6.1. Mục đích

Phương thức PUT được sử dụng để cập nhật dữ liệu của một tài nguyên.

6.2. Request
PUT https://jsonplaceholder.typicode.com/posts/1
6.3. Request Body

Chọn:

Body → raw → JSON

Dữ liệu gửi lên:

{
    "id": 1,
    "title": "Updated Lab 7",
    "body": "Updated using PUT in Postman",
    "userId": 1
}
6.4. Thực hiện

Trong Postman:

Chọn phương thức PUT.
Nhập URL:
https://jsonplaceholder.typicode.com/posts/1
Chọn Body.
Chọn raw.
Chọn JSON.
Nhập dữ liệu JSON.
Nhấn Send.
Kiểm tra Response trả về.
6.5. Kết quả

API trả về thông tin bài viết sau khi cập nhật.

7. Thực hành DELETE
7.1. Mục đích

Phương thức DELETE được sử dụng để gửi yêu cầu xóa một tài nguyên.

7.2. Request
DELETE https://jsonplaceholder.typicode.com/posts/1
7.3. Thực hiện

Trong Postman:

Chọn phương thức DELETE.
Nhập URL:
https://jsonplaceholder.typicode.com/posts/1
Không cần nhập Request Body.
Nhấn Send.
Kiểm tra Response trả về.
7.4. Kết quả

Request DELETE được gửi thành công đến API.

8. Tổng hợp kết quả kiểm thử
STT	Phương thức	URL	Chức năng	Kết quả
1	GET	/posts/1	Lấy thông tin bài viết	Thành công
2	POST	/posts	Tạo bài viết mới	Thành công
3	PUT	/posts/1	Cập nhật bài viết	Thành công
4	DELETE	/posts/1	Xóa bài viết	Thành công
9. Kết quả thực hành

Thông qua quá trình thực hành trên Postman, các request GET, POST, PUT và DELETE đã được thực hiện và kiểm tra.

Các kết quả thực tế được minh họa bằng hình ảnh trong thư mục screenshots của repository.

Các hình ảnh bao gồm:

get-request.png: Kết quả thực hiện GET.
post-request.png: Kết quả thực hiện POST.
put-request.png: Kết quả thực hiện PUT.
delete-request.png: Kết quả thực hiện DELETE.
10. Kiến thức đạt được

Sau bài thực hành, em đã hiểu được:

Cách sử dụng giao diện Postman.
Cách tạo HTTP Request.
Cách sử dụng phương thức GET để lấy dữ liệu.
Cách sử dụng phương thức POST để tạo dữ liệu.
Cách sử dụng phương thức PUT để cập nhật dữ liệu.
Cách sử dụng phương thức DELETE để gửi yêu cầu xóa dữ liệu.
Cách truyền dữ liệu JSON trong Request Body.
Cách kiểm tra HTTP Response.
Cách lưu trữ và trình bày kết quả kiểm thử API.
11. Kết luận

Sau khi hoàn thành Lab 7, em đã làm quen và thực hành được các chức năng cơ bản của công cụ Postman.

Em đã thực hiện thành công bốn phương thức HTTP cơ bản gồm GET, POST, PUT và DELETE trên JSONPlaceholder API.

Qua bài thực hành, em hiểu được quy trình cơ bản của việc kiểm thử API: tạo Request, gửi Request, nhận Response và kiểm tra kết quả.

Bài thực hành giúp em có thêm kiến thức và kỹ năng cơ bản trong việc sử dụng Postman để kiểm thử API trong quá trình phát triển và kiểm thử phần mềm.
