---

# ID Reader (โปรแกรมอ่านบัตรประชาชนจากเครื่องอ่านบัตรอัจฉริยะ)

ID Reader เป็นโปรแกรมที่ช่วยในการอ่านข้อมูลบัตรประชาชนโดยอัตโนมัติผ่านเครื่องอ่านบัตรอัจฉริยะ โดยมีวัตถุประสงค์เพื่ออำนวยความสะดวกในการทำงานและลดข้อผิดพลาดในการบันทึกข้อมูล

## เครื่องมือที่ใช้พัฒนา
- Visual Studio Code
- XAMPP
- Inno Setup Compiler

## ภาษาที่ใช้พัฒนา
Python

## รูปแบบของโปรแกรม
- ติดตั้งลงเครื่อง
- เปิดใช้งานอัตโนมัติเมื่อเครื่องคอมพิวเตอร์เปิด

## ลักษณะการทำงาน
โปรแกรม ID Reader ทำงานเป็นพื้นหลังและอ่านข้อมูลบัตรประชาชนที่เสียบเข้ากับเครื่องอ่านบัตร (Smart Card Reader) ที่เชื่อมต่อกับคอมพิวเตอร์ ข้อมูลที่อ่านได้จะถูกแสดงผลบนหน้าเว็บ localhost:5000 โดยแบ่งเป็น 3 สถานะดังต่อไปนี้:

1. **"ไม่พบเครื่องเสียบบัตร"**: หมายถึงไม่พบเครื่องอ่านบัตรที่เชื่อมต่อกับคอมพิวเตอร์
2. **"ไม่พบบัตรประชาชน"**: หมายถึงไม่พบบัตรประชาชนที่ถูกเสียบเข้ากับเครื่องอ่านบัตร
3. **"อ่านข้อมูลสำเร็จ"**: หมายถึงการอ่านข้อมูลบัตรประชาชนสำเร็จและแสดงข้อมูลบนหน้าเว็บ

## วิธีการใช้งาน
1. เริ่มต้นโปรแกรม ID Reader โดยการติดตั้งลงในเครื่องคอมพิวเตอร์ของคุณ
2. เมื่อเปิดคอมพิวเตอร์ โปรแกรมจะทำงานเป็นพื้นหลังโดยอัตโนมัติ
3. เมื่อเสียบบัตรประชาชนเข้ากับเครื่องอ่านบัตร และข้อมูลถูกอ่านสำเร็จ ผลลัพธ์จะแสดงบนหน้าเว็บ localhost:5000

## ข้อตกลงการใช้งาน
โปรแกรม ID Reader สามารถใช้งานได้ฟรีและเป็นการเปิดเผย สามารถนำไปใช้งานหรือปรับปรุงต่อยอดได้โดยไม่มีข้อจำกัด โดยต้องให้เครดิตแก่ผู้พัฒนาต้นฉบับ

