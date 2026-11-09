# เว็บไซต์เรียนรู้เรื่องชั้นบรรยากาศ

เว็บไซต์ Static ใช้ HTML, CSS และ JavaScript ไม่ต้องติดตั้ง PHP, MySQL หรือ Server

## โครงสร้าง
- `index.html` หน้าเว็บไซต์หลัก
- `style.css` รูปแบบและ Responsive layout
- `script.js` เมนู การ์ดข้อมูล และแบบทดสอบ 5 ข้อพร้อมคะแนน/เฉลย/ทำใหม่
- `assets/earth-atmosphere.svg` ภาพประกอบโลก
- `assets/favicon.svg` ไอคอนเว็บไซต์

## เปิดทดสอบในเครื่อง
แตกไฟล์ ZIP แล้วเปิด `index.html` ด้วย Chrome, Edge, Firefox หรือ Safari ได้ทันที เว็บไซต์ทำงานแบบ Static ไม่ต้องติดตั้ง Server ฟอนต์ Google Fonts จะโหลดเมื่อมีอินเทอร์เน็ต หากออฟไลน์จะใช้ฟอนต์สำรอง

## เผยแพร่ผ่าน GitHub Pages
1. สร้าง Repository ใหม่บน GitHub
2. อัปโหลดไฟล์ทั้งหมดและโฟลเดอร์ `assets` โดยให้ `index.html` อยู่ที่ราก Repository
3. เปิด Settings → Pages
4. เลือก Build and deployment: Deploy from a branch
5. เลือก Branch `main` และ Folder `/ (root)` แล้วกด Save
6. รอ GitHub Pages เผยแพร่ แล้วเปิด URL ที่แสดงในหน้า Pages

## ตรวจสอบ
ไฟล์ CSS, JavaScript, ภาพ และ favicon ใช้ relative paths; ไม่มี backend/API; แบบทดสอบตรวจคำตอบ คำนวณคะแนน แสดงคำอธิบาย และเริ่มใหม่ได้
