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
Request

PUT:

https://jsonplaceholder.typicode.com/posts/1

Body
{
    "id": 1,
    "title": "Updated Lab 7",
    "body": "Updated using PUT in Postman",
    "userId": 1
}
7. Thực hành DELETE
Request

DELETE:

https://jsonplaceholder.typicode.com/posts/1

