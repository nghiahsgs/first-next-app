This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
# SOME NOTE
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





# ------------------------
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
