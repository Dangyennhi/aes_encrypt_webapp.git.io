1. Giới thiệu

    AES Encrypt WebApp cung cấp giao diện thân thiện để người dùng nhập văn bản và khóa bí mật, sau đó thực hiện mã hóa hoặc giải mã dữ liệu. Ứng dụng sử dụng thuật toán AES ở chế độ CBC (Cipher Block Chaining) để đảm bảo tính bảo mật và toàn vẹn của dữ liệu.

3. Chức năng cơ bản

  Mã hóa văn bản: Nhập văn bản và khóa để nhận được chuỗi mã hóa.

  Giải mã văn bản: Nhập chuỗi mã hóa và khóa để khôi phục văn bản gốc.

  Giao diện người dùng trực quan: Dễ dàng sử dụng với hướng dẫn rõ ràng.

Hiển thị kết quả: Kết quả mã hóa và giải mã được hiển thị ngay trên giao diện.

3. Kỹ thuật và công nghệ sử dụng
Ngôn ngữ lập trình: Python

Framework backend: Flask

Thư viện mã hóa: PyCryptodome (cho thuật toán AES)

Giao diện người dùng: HTML, CSS, JavaScript

Chế độ mã hóa: AES-CBC với padding và unpadding để xử lý dữ liệu không đủ khối

2. Mô tả giao diện web (Flask + HTML/CSS/JS)
Giao diện mã hóa
![image](https://github.com/user-attachments/assets/8ea097f3-b49a-49c0-b1bb-125ffd1dddc1)
Giao diện giải mã 
![image](https://github.com/user-attachments/assets/52cc29c6-dbf2-4f1a-9aa7-1b076bd4d0ba)
