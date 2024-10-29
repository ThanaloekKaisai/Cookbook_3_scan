# Example นี้คือ scan
Example นี้จะทำหน้าที่ในการ scan access point บริเวณที่ ESP32 สามารถเชื่อมต่อได้โดยที่จะสามารถกำหนดจำนวน WiFi ที่มองเห็นได้

เริ่มจากการ Show Example โดยที่เราจะเลือก scan
![image](https://github.com/user-attachments/assets/268319ca-de7c-49e8-9f83-d66e1c8af63b)

จากนั้นไปที่ menuconfig แล้วค้นหา Max size of scan list

![image](https://github.com/user-attachments/assets/039ee5e9-8c89-47b9-85fd-b52a1d3578be)

โดยที่เราสามารถกำหนดจำนวนไวไฟที่เห็นได้

Build และ Flash ลงบอร์ด

![image](https://github.com/user-attachments/assets/54ea5088-01aa-4abb-8512-d3764fbbb863)

ใน Serial Moniter จะแสดงข้อมูลต่างๆของไวไฟที่สามารถเชื่อมต่อได้ในระยะของ ESP32
