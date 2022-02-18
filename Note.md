cách tạo 1 project mới next js
```
https://nextjs.org/docs/getting-started
```

Cách cài yarn
```
npm install --global yarn
```

+ cách tạo static generate mode
Mở file package.json và thêm dòng trong scrips object
```
"export": "next build && next export",
```

sau đó gõ npm run export, nó sẽ build xong rồi export
```
npm run export
```

+ + nếu thành công thì nó sẽ tạo 1 thư mục mới tên là out rồi chưa html trong đó
+ + nễu thất bại thì có thể do 1 số lỗi sau (vd kiểu import component ảnh là ko được ...)
```
https://www.youtube.com/watch?v=T2Z6JVzz854
```

Còn 1 trường hợp ngáo ngơ nữa là build mãi k được, chứ báo đang chạy, có lẽ do chưa ngưng "npm run dev"
```
 ExperimentalWarning: The ESM module loader is experimental.
info  - Checking validity of types
```
