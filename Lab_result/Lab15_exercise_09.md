4.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/65030121natthamon/03376836-OOP-2566-Lab-15/assets/144195611/99e683fd-a8f1-4fb2-80af-bebd9713f6a1)

6.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/65030121natthamon/03376836-OOP-2566-Lab-15/assets/144195611/4a85e85f-5b7a-4832-b56d-5f49282545e1)

7.อธิบายสิ่งที่พบในการทดลอง
- ใช้ Action เพื่อระบุว่าเราต้องการทำงานเป็นการเรียกใช้งานฟังก์ชันที่ไม่มีการรับค่าคืน หรือฟังก์ชันที่ไม่มีการรับพารามิเตอร์
- Action a = Print; ระบุ Action ที่ชื่อว่า a โดยมีการกำหนดให้เป็นฟังก์ชัน Print ซึ่งเป็นการเรียกใช้งานฟังก์ชัน Print โดยไม่มีการรับค่าคืน
- Action<int, int, int> s = PrintSum; สร้าง Action delegate ที่รับพารามิเตอร์ 3 ตัว และกำหนดให้ชี้ไปยังเมท็อด PrintSum และเรียกใช้ Action นี้ด้วย s(4, 5, 6); เพื่อส่งค่าเข้าไปในเมท็อด PrintSum
- Action<int, int> sum = (a, b) => {...}; ใช้ Action delegate รับพารามิเตอร์ 2 ตัว และกำหนดให้เป็น lambda expression ที่รับ a และ b และคำนวณผลรวมของสอง และหาผลลัพธ์ 
