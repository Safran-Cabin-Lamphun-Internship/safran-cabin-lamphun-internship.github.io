SAFRAN INTERNSHIP WEBSITE – ADMIN FIXED

ไฟล์ในชุดนี้
- index.html = หน้า Public V10 + ระบบอ่าน site-content.json ที่แก้ให้เสถียรขึ้น และมีข้อมูลสำรองในตัว
- data/site-content.json = ข้อมูลที่แก้จาก Admin
- admin/index.html = หน้า Admin แบบแก้ตามหัวข้อ

ติดตั้งใน GitHub
1) แทนที่ index.html ใน root
2) แทนที่ data/site-content.json
3) แทนที่ admin/index.html
4) Commit changes

ใช้งาน Admin
1) เปิด /admin/
2) เปิดหัวข้อ About Safran (เปิดไว้ให้แล้ว)
3) แก้ English / ไทย
4) กด Preview
5) กด บันทึกการแก้ไข
6) กด Download JSON
7) นำ site-content.json ที่ดาวน์โหลดไปแทน data/site-content.json ใน GitHub
8) Commit changes และรอ Pages Deploy

หมายเหตุ: Admin ไม่ฝัง GitHub Token และไม่ได้เขียน Repository อัตโนมัติ เพื่อความปลอดภัย
