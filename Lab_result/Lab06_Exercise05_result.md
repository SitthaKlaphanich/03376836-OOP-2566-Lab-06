## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3 

![pic](/Pictures/pic-15.png)

- สามารถ Build ได้ปกติ แต่ จะถูกเตือนว่ามีค่า field ที่ถูกประกาศเป็น non-nullable (ไม่สามารถมีค่าเป็น null ได้) และไม่ได้รับค่าในตัว constructor ของ
คลาส ซึ่งทำให้มีความเสี่ยงที่จะมีค่า null

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5

- สามารถ run ได้ปกติ ไม่มีข้อผิดพลาด

![pic](/Pictures/pic-16.png)

## อธิบายสิ่งที่พบในการทดลอง

- โปรแกรมจะแสดงผล
-  Integer i : 123, floating point f : 1234.56, string s  : Hello World!