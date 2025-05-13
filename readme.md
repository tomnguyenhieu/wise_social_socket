# Hướng dẫn sử dụng:

Mở terminal và chạy lần lượt các lệnh sau:

```bash
git clone https://github.com/tomnguyenhieu/wise_social_socket.git wise_social_socket

cd wise_social_socket

rm -rf .git

npm install

node comment_socket.js
```

---

# Hướng dẫn cài đặt và chạy Socket.IO với Node.js

## Bước 1: Khởi tạo project Node.js

Mở terminal và chạy lệnh sau để khởi tạo một project Node.js mới:

```bash
npm init -y
```

Lệnh này sẽ tạo ra một file `package.json` với các thiết lập mặc định.

---

## Bước 2: Cài đặt các thư viện cần thiết

### Cài đặt Socket.IO

```bash
npm install socket.io
```

### Cài đặt Express (framework để tạo web server)

```bash
npm install express
```

---

## Bước 3: Tạo file máy chủ Socket.IO

Tạo một file JavaScript, ví dụ: `socket_server_name.js`, sau đó viết mã xử lý socket tại đây.

---

## Bước 4: Chạy máy chủ Socket.IO

Dùng lệnh sau trong terminal để chạy server:

```bash
node socket_server_name.js
```

Nếu thành công sẽ thấy dòng:

```
Server is running at http://localhost:3000
```
