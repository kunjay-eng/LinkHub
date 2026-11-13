# Link Hub v1.0.1

## โครงสร้าง
- `index.html`  หน้าบ้าน (HTML + JS ล้วน โฮสต์บน GitHub Pages)
- `config.js`   ตั้งค่า API_URL
- `Code.gs`     หลังบ้าน Google Apps Script

## ติดตั้ง
1. สร้าง Google Sheet → Extensions > Apps Script → วางโค้ด `Code.gs`
2. Project Settings > Script properties เพิ่ม `ADMIN_PIN` = รหัสของคุณ
3. Deploy > New deployment > Web app (Execute as: Me, Access: Anyone) → คัดลอก URL `/exec`
4. ใส่ URL ลง `config.js` → push ขึ้น GitHub → เปิด Settings > Pages
5. ไม่ใส่ URL = โหมดทดลอง ข้อมูลเก็บในเบราว์เซอร์

## Changelog
- v1.0.0 โครงร่างแรก: ธีมมืด, ค้นหา, หมวดหมู่, ปักหมุด, สถานะออนไลน์, เพิ่ม/แก้ไข/ลบการ์ด
- v1.0.1 ออกแบบการ์ดใหม่ให้เข้ากับธีม Dark Tech: การ์ดแนวนอน แถบสถานะด้านซ้าย แสดงโดเมนและสถานะ ปุ่มปักหมุด/แก้ไขเป็นไอคอน SVG
