# Ai-Notification-when-abnormal
เป้นโมเดลที่สร้างขึ้นเพื่อการใช้ Machine Learning /Ai ในการทำนายว่าผู้สูงอายุนั้นมีความผิดปกติหรือไม่ถ้ามีจะมีความผิดปกติที่ระดับใดโดยการดูจากความดันเป็นหลัก
โดยจะมีการแบ่งเป็น 4 ระดับ (1.)ปกติ   (2.)ผิดปกติระดับ1   (3.)ผิดปกติระดับ2   (4.)ผิดปกติระดับ3 

โดยผิดปกติระดับ 1,2,3 จะแตกต่างกันที่ 

ระดับที่1 จะมีความดันอยู่ในช่วง 140 - 159 หรือมีค่าอื่นๆผิดปกติค่าใดค่านึง  

ระดับที่2 จะมีความดันอยู่ในช่วง 160-179 หรือมีค่าอื่นๆผิดปกติในเวลาเดียวกัน

ระดับที่3 จะมีความดันอยู่ในช่วง 180 ขึ้นไป หรือมีค่าอื่นๆผิดปกติในเวลาเดียวกัน

#  Database        
โดยข้อมูลที่เราทำการเอามาใช้จะมีข้อมูลทั้งหมด 219 ข้อมูลและมี 7 ช่อง 

ช่องที่ 1 จะเป็นอายุของผู้สูงอายุ

ช่องที่ 2 จะเป็นเพศ โดยที่เพศหญิงจะเก็บเป็นเลข 0 ส่วนผู้ชายจะเก็บเป็นเลข 1

ช่องที่ 3 จะเป็นค่าชีพจร

ช่องที่ 4 จะเป็นค่าความดัน

ช่องที่ 5 จะเป็นค่าออกซิเจนในเลือด

ช่องที่ 6 จะเป็นค่าอุณหภูมิร่างกาย

ช่องที่ 7 จะเป็นค่าบอกว่าข้อมูลช่องที่3-6จะมีความผิดปกติหรือไม่
![image](https://user-images.githubusercontent.com/96381276/146791180-84eb2408-40d0-44b4-b3f1-9affe8bc90a8.png)

# การอัพโหลด Database 
  ขั้นที่ 1 กดไปที่ลูกษรชี้
  
  ![image](https://user-images.githubusercontent.com/96381276/147100541-647b32cb-d490-456f-b494-05d9c4017c7a.png)

   ขั้นที่ 2 กดไปที่ลูกษรชี้ เพื่อเลือกไฟล์ database ที่เราโหลดไว้
   
   ![image](https://user-images.githubusercontent.com/96381276/147101671-564304c5-9d4e-48c6-a5f1-6d8e139f01bf.png)
![image](https://user-images.githubusercontent.com/96381276/147101815-2ddc4213-a025-4958-9744-4dc2aa0b5102.png)

   ขั้นที่ 3 อัพโหลดไฟล์เส็จ สามารถรันโปรแกรมได้ปกติ
   
   ![image](https://user-images.githubusercontent.com/96381276/147102437-8f3be3bc-2d11-4513-9e01-bd9d588a2b77.png)
  
  
# Train / Test
Training data จะมีความแม่นยำของโมเดลอยู่ที่ :  0.8536585365853658 หรือประมาน 85 %

Test data จะมีความแม่นยำของโมเดลอยู่ที่ :  0.9272727272727272 หรือประมาน 93 %

# แหล่งที่มา
https://youtu.be/qmqCYC-MBQo

https://youtu.be/kySc5Wg1Gxw
