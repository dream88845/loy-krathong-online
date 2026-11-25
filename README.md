# ลอยกระทงออนไลน์

เว็บไซต์ลอยกระทงแบบหน้าเดียว เลือกแบบกระทง ใส่ชื่อ และเขียนคำอธิษฐานให้ลอยไปบนฉากแม่น้ำได้

## รันทดสอบด้วย Node.js

```bash
npm start
```

จากนั้นเปิด `http://localhost:3000`

## Deploy ด้วย GitHub Pages

เวิร์กโฟลว์ใน `.github/workflows/pages.yml` จะ Deploy เนื้อหาใน `public/` เมื่อ push ไปยัง branch `main` หรือสั่งรันจากแท็บ Actions

ใน Repository ให้เลือก **Settings → Pages → Build and deployment → Source: GitHub Actions** หากยังไม่ได้เปิดใช้งาน Pages จากนั้นรอเวิร์กโฟลว์สำเร็จ

รูปแบบ URL ของเว็บคือ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repository>/`
