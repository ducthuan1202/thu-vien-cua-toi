## Cơ bản về `pm2`

Thông tin tham khảo tại [đây](https://github.com/Unitech/pm2)

- Cài đặt ở chế độ global
```sh
npm install -g pm2
```

- Chạy 1 ứng dụng với `pm2`
```sh
pm2 start app.js
```

Mặc định, pm2 sẽ lấy tên file (không tính phần extension) để đăt tên cho `app-name`. Tuy nhiên, chúng ta cũng có thể tự định nghĩa tên cho 1 app:
```sh
pm2 start app.js --name "customer-name"
```

- Xem danh sách các ứng dụng đang chạy
```sh
pm2 list
```

- Tạm dừng 1 ứng dụng
```sh
pm2 stop app_name
```

- Khởi động lại 1 ứng dụng
```sh
pm2 restart app_name
```

- Xóa 1 ứng dụng đã đăng ký trong mp2
```sh
pm2 delete app_name
```

[Về trang chủ](../../)