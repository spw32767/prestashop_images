## Project Documentation and Resources

- **Sprint Backlog**: [Sprint Backlog Access]([#link-to-sprint-backlog](https://docs.google.com/spreadsheets/d/1gHyhZkWK8st6c8J_GZUHQ6ZtWnURtJH-R3EzkDi2-j4/edit#gid=1445771383)) - Detailed breakdown of work for the current sprint.
- **Docker Image**: [Docker Hub Link](#link-to-docker-image) - Our project's Docker image for easy deployment and testing.
- **A-DAPT Blueprint**: [Blueprint Details](#link-to-A-DAPT-Blueprint) - Architectural and design patterns for our project.
- **Presentation Slides**: [View Slides](#link-to-presentation-slide) - Slides for our project presentations and updates.




## 1. เครื่องมือที่ใช้พัฒนา
- **Visual Studio Code**: ใช้ในการเขียนโปรแกรม
- **Docker**: ใช้ในการสร้างและจัดการ Containers
- **Google Chrome**: ใช้สำหรับการทดสอบเว็บ
- **Git**: ใช้สำหรับการควบคุมเวอร์ชัน
- **Playwright**: ใช้สำหรับการทดสอบอัตโนมัติ

## 1.2 ขอบเขตและข้อจำกัด
### 1.2.1 ขอบเขตของผู้ใช้งานทั่วไป
- ดูสินค้าและรายละเอียดของสินค้า
- นำสินค้าใส่ในตะกร้า
- สั่งซื้อสินค้า

### 1.2.2 ขอบเขตของผู้ดูแลระบบ
- ดูข้อมูลของลูกค้า
- เพิ่มลบสินค้า
- แก้ไขและจัดการรายละเอียดสินค้า
- ปรับแต่งรายละเอียดหน้าเว็บไซต์
- แก้ไขสถานะของคำสั่งซื้อ

### 1.2.3 ข้อจำกัดของระบบ
- ต้องรันผ่านเซิร์ฟเวอร์

## 2. คู่มือการใช้งาน
คู่มือนี้จะแบ่งผู้ใช้งานออกเป็น 2 กลุ่ม: ผู้ใช้ทั่วไป และผู้ดูแลระบบ

### 2.1 การเข้าใช้สำหรับผู้ใช้ทั่วไป
หน้านี้เเสดงสินค้าทั้งหมด สามารถคลิกที่ตัวสินค้าเพื่อไปยังหน้ารายละเอียดของสินค้านั้นๆ สามารถกดเพิ่มสินค้าเข้าตระกร้าสินค้าได้

![หน้าแรก](https://github.com/spw32767/prestashop_images/blob/main/1.png?raw=true)
<p align="center">
  <strong>ภาพที่ 1 หน้าแรก</strong>
</p>

หน้านี้จะเเสดงรายละเอียดของสินค้าที่กดดูจากหน้าเเรก (ภาพที่ 1) สามารถเลือกขนาด ดูรูปภาพเพิ่มเติมของสินค้า เเละสามารถเลือกสินค้าเข้าตระกร้าสินค้าได้

![หน้ารายละเอียดของสินค้า](https://github.com/spw32767/prestashop_images/blob/main/2.png?raw=true)
<p align="center">
  <strong>ภาพที่ 2 หน้ารายละเอียดของสินค้า</strong>
</p>

จากภาพที่ 2 เมื่อกดเลือกสินค้าเข้าตระกร้าสินค้าเเล้ว สามารถเลือกได้ว่าจะเข้าสู่หน้าตระกร้าสินค้าที่เลือกไว้ หรือจะเลือกสินค้าอื่นๆต่อ

![หน้าตระกร้าสินค้า](https://github.com/spw32767/prestashop_images/blob/main/3.png?raw=true)
<p align="center">
  <strong>ภาพที่ 3 หน้าตระกร้าสินค้า</strong>
</p>

จากภาพที่ 3 เมื่อคลิกที่ 'proceed to checkout' เพื่อไปยังหน้ากรอกข้อมูลสำหรับการสั่งซื้อ เพื่อทำการจัดส่งสินค้าไปยังที่อยู่ตามข้อมูลที่กรอก

![หน้ากรอกข้อมูลและที่อยู่](https://github.com/spw32767/prestashop_images/blob/main/4.png?raw=true)
<p align="center">
  <strong>ภาพที่ 4 หน้ากรอกข้อมูลและที่อยู่</strong>
</p>

หน้านี้จะแสดงสินค้าที่คุณเลือกไว้ในตะกร้า คุณสามารถปรับจำนวนสินค้า, ยกเลิกสินค้าที่เลือก, หรือดำเนินการชำระเงิน.

![หน้าการจัดส่ง](https://github.com/spw32767/prestashop_images/blob/main/5.png?raw=true)
<p align="center">
  <strong>ภาพที่ 5 หน้าการจัดส่ง</strong>
</p>

หน้านี้ให้คุณกรอกข้อมูลสำหรับการจัดส่ง เช่น ชื่อ, ที่อยู่, และข้อมูลติดต่อ คุณสามารถเลือกประเทศและเมืองจาก dropdown menu.

![หน้าการชำระเงิน](https://github.com/spw32767/prestashop_images/blob/main/6.png?raw=true)
<p align="center">
  <strong>ภาพที่ 6 หน้าการชำระเงิน</strong>
</p>

หน้านี้จะแสดงตัวเลือกวิธีการจัดส่ง คุณสามารถเลือกรูปแบบการจัดส่งที่ต้องการและกรอกข้อมูลเพิ่มเติมหากจำเป็น.

![หน้ารายละเอียดการซื้อ](https://github.com/spw32767/prestashop_images/blob/main/7.png?raw=true)
<p align="center">
  <strong>ภาพที่ 7 หน้ารายละเอียดการซื้อ</strong>
</p>

หน้านี้ให้คุณเลือกวิธีการชำระเงิน คุณสามารถเลือกจากรูปแบบการชำระเงินที่มีให้และยินยอมตามเงื่อนไขการชำระเงิน.

![หน้าประวัติการสั่งซื้อ](https://github.com/spw32767/prestashop_images/blob/main/8.png?raw=true)
<p align="center">
  <strong>ภาพที่ 8 หน้าประวัติการสั่งซื้อ</strong>
</p>

หลังจากชำระเงินเสร็จสิ้น หน้านี้จะแสดงรายการสินค้าที่คุณได้ทำการซื้อไปพร้อมกับรายละเอียดสินค้าและเลขที่อ้างอิงการสั่งซื้อ.

![หน้าเข้าสู่ระบบผู้ดูแลระบบ](https://github.com/spw32767/prestashop_images/blob/main/9.png?raw=true)
<p align="center">
  <strong>ภาพที่ 9 หน้าเข้าสู่ระบบผู้ดูแลระบบ</strong>
</p>

หน้านี้แสดงประวัติการสั่งซื้อทั้งหมดของคุณ แสดงสถานะการจัดส่ง และรายละเอียดของการสั่งซื้อแต่ละครั้ง.

### 2.1.2 การเข้าใช้สำหรับผู้ดูแลระบบ

![หน้าสรุปข้อมูลสำหรับผู้ดูแลระบบ](https://github.com/spw32767/prestashop_images/blob/main/10.jpg?raw=true)
<p align="center">
  <strong>ภาพที่ 10 หน้าสรุปข้อมูลสำหรับผู้ดูแลระบบ</strong>
</p>

หน้านี้ให้ผู้ดูแลระบบกรอกอีเมลและรหัสผ่านเพื่อเข้าสู่ระบบ.

![หน้าแสดงผลิตภัณฑ์](https://github.com/spw32767/prestashop_images/blob/main/11.png?raw=true)
<p align="center">
  <strong>ภาพที่ 11 หน้าแสดงผลิตภัณฑ์</strong>
</p>

หน้านี้แสดงข้อมูลสรุปและสถิติต่างๆ ที่เกี่ยวข้องกับการซื้อขายบนเว็บไซต์.

![หน้าสถานะการจัดส่ง](https://github.com/spw32767/prestashop_images/blob/main/12.png?raw=true)
<p align="center">
  <strong>ภาพที่ 12 หน้าสถานะการจัดส่ง</strong>
</p>

หน้านี้แสดงรายการผลิตภัณฑ์ทั้งหมด ผู้ดูแลระบบสามารถเพิ่ม, ลบ, แก้ไขผลิตภัณฑ์ และจัดการกับการแสดงผลของสินค้า.

![หน้าการจัดส่ง](https://github.com/spw32767/prestashop_images/blob/main/13.png?raw=true)
<p align="center">
  <strong>ภาพที่ 13 หน้าการจัดส่ง</strong>
</p>

หน้านี้แสดงสถานะการจัดส่งสำหรับการสั่งซื้อทั้งหมด ผู้ดูแลระบบสามารถเข้าดูและแก้ไขสถานะการจัดส่งได้.
