## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3 

![pic](/Pictures/pic-10.png)

ไม่สามารถ build ได้เพราะ  b2 ในคลาส AAA โดยใช้อ็อบเจ็กต์ของ AAA, แต่ b2 เป็นตัวแปรสแตติก (static) ซึ่งต้องถูกเข้าถึงผ่านชื่อของคลาสตัวเองและไม่สามารถเข้าถึงได้โดยตรงจากอ็อบเจ็กต์.

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5

![pic](/Pictures/pic-11.png)

ไม่สามารถ run ได้เพราะ b2 ในคลาส AAA โดยใช้อ็อบเจ็กต์ของ AAA, แต่ b2 เป็นตัวแปรสแตติก (static) ซึ่งต้องถูกเข้าถึงผ่านชื่อของคลาสตัวเองและไม่สามารถเข้าถึงได้โดยตรงจากอ็อบเจ็กต์.


## อธิบายสิ่งที่พบในการทดลอง
โปรแกรมจะแสดงผล
- a1.b1 = 10
AAA.b2 = 40
a2.b1 = 30
a2.b2 = 40

## หลังแก้ไขโปรแกรม

![pic](/Pictures/pic-12.png)
![pic](/Pictures/pic-13.png)
![pic](/Pictures/pic-14.png)