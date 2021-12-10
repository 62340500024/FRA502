# FRA502
https://drive.google.com/file/d/1SKHkeWmrvRuuNkj5PJgjvoKQofkqhtRo/view?usp=sharing

ทนุพงษ์ แก้วบุบผา 62340500024
วิธีการใช้งาน ทำการ run ที่ terminal 
1.roscore 
2.roslaunch Robothos gazebo1.launch (open map in gazebo)
3.roslaunch Robothos nav.launch (navigation in rviz)
4.rosrun Robothos speech.py (speech to control)
  keywork room one 
          room two
          room three
          room four
          room five 
          room six
          standby (home point)
ปัญหาที่พบ
urdf โครงสร้าง เกิดการไม่สมดุลทำให้ตอน gmapping เกิดการผิดพลาด เนื่องจาก
สร้างจุดที่เดินไม่ได้ที่พื้นเพราะว่าเกิดการยกหน้าของหุ่น
speech มีการ delay นานทำให้ไม่สามารถทดลองให้ดูได้
แต่มีการทดสอบการรับคำซึ่งใช้ได้

