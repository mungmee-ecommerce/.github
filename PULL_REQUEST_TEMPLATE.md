## Description ( Motivation and Context ) อธิบายจุดประสงค์ & ที่มาที่ไป ในการเปิด PR เพื่อ change

<!--- Why is this change required? What problem does it solve? -->

## How Has This Been Tested? เทสยังไงถ้า manual เทสยังไง หรือ มี Unit Test มั้ย?

<!--- รายละเอียดวิธีเช็คและเทส -->
<!--- environment ที่เช็ค -->
<!--- มีผลกระทบกับ code ส่วนอื่นๆด้วยมั้ย -->

## Screenshots/Video Record (ถ้ามี):

<!--- แนบหลักฐานการเทส --->

## Checklist:

<!--- ใส่ `x` ในข้อที่ทำ -->
<!--- ถ้าไม่แน่ใจ, ให้ถาม -->
 
- [ ] เขียน function ให้ทำงาน 1 อย่างจริงๆ ต่อ 1 function เพื่อที่สามารถทำ Unit Test ได้ง่าย
- [ ] มีการเขียน Test ครอบคลุม code ที่เพิ่มเข้ามาใหม่
- [ ] มีการรัน Unit Test แล้วผ่าน
- [ ] business logic ไม่อยู่ใน controller
- [ ] ตรวจสอบคิวรี่ linq <> sql query แล้วคำสั่งที่แปลงมีประสิทธิภาพ 
- [ ] มีการตรวจเช็ค query ด้วย Execution Plan
