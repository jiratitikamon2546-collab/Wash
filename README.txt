AR Washing Machine - Fixed

ไฟล์:
1. index.html       = หน้า AR
2. marker.html      = หน้า Hiro Marker สำหรับพิมพ์

จุดที่แก้:
- ไม่พึ่งไฟล์ washing-machine.glb อีกต่อไป
- สร้างเครื่องซักผ้า 3D ด้วย A-Frame primitives จึงควรแสดงทันที
- ใช้ Hiro Marker มาตรฐานของ AR.js
- ปุ่ม -/+ ปรับ 0-1200 RPM
- หมุนเฉพาะถังซัก

วิธีใช้งาน:
1. เปิด index.html ผ่าน HTTPS หรือ localhost
2. อนุญาต Camera
3. เปิด marker.html และพิมพ์ Hiro Marker
4. หันกล้องไปที่ Marker
5. กด + เพื่อเพิ่ม RPM

หมายเหตุ:
ต้องใช้งานผ่าน HTTPS หรือ localhost เพื่อให้ Browser อนุญาตกล้อง
