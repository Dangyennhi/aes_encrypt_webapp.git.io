1. Mô tả thuật toán AES (Advanced Encryption Standard)
Nguyên lý hoạt động:
AES là một thuật toán mã hóa khối đối xứng (symmetric block cipher), tức là cùng một khóa được dùng cho cả mã hóa và giải mã.

Dữ liệu được chia thành từng khối 128-bit, sau đó được xử lý qua nhiều vòng (round) chuyển đổi.

Mã hóa:

Dữ liệu đầu vào được thêm padding để chia khối đủ 16 byte (AES block size).

Dùng AES.new(..., AES.MODE_CBC, iv) để mã hóa bằng chế độ CBC.

Giải mã:

Ngược lại với mã hóa: giải mã xong sẽ unpad() để loại bỏ phần đệm.


2. Mô tả giao diện web (Flask + HTML/CSS/JS)
Giao diện mã hóa
![image](https://github.com/user-attachments/assets/8ea097f3-b49a-49c0-b1bb-125ffd1dddc1)
Giao diện giải mã 
![image](https://github.com/user-attachments/assets/52cc29c6-dbf2-4f1a-9aa7-1b076bd4d0ba)
