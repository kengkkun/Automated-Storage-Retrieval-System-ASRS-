# Automated Storage-Retrieval System ASRS

##This is my senior project, if you want to use this code please credit to me.

## Abstract
  Currently, the inventory management system of company has been applied the
automatic control system to reduce worker costs, safety, and increase logistics efficiency. The
objective of this project is to present the model of automated storage and retrieval system
(ASRS) with PID controller to control the moving of motor to the desired position more
precisely and reduce the operation time. We use microcontroller namely, NI myRIO-1900 and
using program LabVIEW to control the moving of motor to storage and retrieval the products.
Robotic control uses three motors to function horizontally (X), vertically (Y) and gripper (Z).
We can track the working status of robot in the real time by the monitor. If the power supply
failures until the robot stopped working, the robots can remember the latest position and can
resume from the current position immediately. From the experiment results when compared
with the non-PID control systems, the maximum percent overshoot is reduced about 15% and
the operation time (setting time) of robots is reduced about 0.2 seconds.
Keywords : Microcontroller, robot, automated control system, LabVIEW program, PID controller

## บทคัดย่อ

  ปัจจุบันระบบการจัดการคลังเก็บสินค้าของโรงงานได้มีการนำระบบอัตโนมัติมาประยุกต์ใช้เพื่อลดแรงงานคน เพิ่มความปลอดภัยในการทำงาน และเพิ่มประสิทธิภาพการขนส่งทางโลจิสติกส์ ปริญญานิพนธ์เล่มนี้มีได้นำเสนอแบบจำลองระบบจัดเก็บและเรียกคืนสินค้าอัตโนมัติด้วยตัวควบคุมพีไอดี เพื่อควบคุมการทำงานของมอเตอร์ให้สามารถเคลื่อนไปยังตำแหน่งที่ต้องการได้แม่นยำขึ้นและใช้เวลาในการทำงานลดลง โดยใช้ไมโครคอนโทรเลอร์ของ Nation Instrument รุ่น myRIO ในการควบคุมมอเตอร์ไฟฟ้าซึ่งเป็นตัวขับเคลื่อนโรบอทให้เคลื่อนที่ไปยังชั้นวางสินค้าในตำแหน่งที่ต้องการเพื่อจัดเก็บหรือเรียกคืนสินค้าในช่องใส่สินค้าที่ได้ระบุไว้ โดยระบบจะใช้มอเตอร์ทั้งหมด 3 ตัว ประกอบเป็นส่วนต่าง ๆ ของตัวโรบอทเพื่อให้สามารถเคลื่อนที่ได้ทั้งในแกน X (แนวนอน), แกน Y (แนวตั้ง) และแกน Z (Gripper) ในการพัฒนาโปรแกรมได้ใช้โปแกรม LabVIEW ในการเขียนโปรแกรมควบคุมอุปกรณ์ทำงานต่าง ๆ ของระบบ การติดตามผลการทำงานของระบบสามารถแสดงผ่านหน้าจอคอมพิวเตอร์แบบเวลาจริง หากแหล่งจ่ายไฟเสียหายและส่งผลให้โรบอทหยุดทำงาน โรบอทสามารถจดจำตำแหน่งล่าสุดได้ และสามารถเริ่มต้นทำงานจากตำแหน่งปัจจุบันได้ทันทีเมื่อแหล่งจ่ายสามารถทำงานได้ตามปกติ จากผลการทดสอบด้วยการนำไปเปรียบเทียบกับระบบที่ไม่ใช้ตัวควบคุมพีไอดีพบว่า เปอร์เซนต์โอเวอร์ชูตของระบบลดลงประมาณ 15% และโรบอทใช้เวลาลดลงในการเคลื่อนที่ไปยังตำแหน่งที่ต้องการโดยเฉลี่ยประมาณ 0.2 วินาที

คำสำคัญ : ไมโครคอนโทรลเลอร์  โรบอท  ระบบควบคุมแบบอัตโนมัติ  โปรแกรมแลปวิว  ระบบควบคุมแบบพีไอดี



