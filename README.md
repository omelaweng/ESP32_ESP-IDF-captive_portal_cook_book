แนวทางการทำงาน ESP32_ESP-IDF-captive_portal_cook_book

ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน

เลือก new project แล้วตั้งชื่อโปรเจค ที่เก็บโฟลเดอร์ และเลือก port

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 15 08 05" src="https://github.com/user-attachments/assets/1a3e3dcc-0c0a-404e-b9a0-68ddba987fac">

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 15 09 44" src="https://github.com/user-attachments/assets/e4b46939-6683-492e-974b-af01e4244b30">

เลือกโปรเจค captive_portal แล้วกด create project

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 14 35 14" src="https://github.com/user-attachments/assets/fc9f025f-98b4-4d5a-a28a-e9b51cc5a308">

ทำการ build และ run โปรแกรม

<img width="973" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 15 12 16" src="https://github.com/user-attachments/assets/15fb2d70-cd4b-46e2-99fc-0c0abb8eac85">

เลือกเชื่อมต่อ Wi-Fi esp32_ssid

![IMG_8408](https://github.com/user-attachments/assets/541a4ff2-3ec8-413c-92fa-0f8f17cbea64)

เมื่ออุปกรณ์เชื่อมต่อกับ Wi-Fi จะเด้งเข้าหน้าเว็บการเชื่อมต่อโดยดึงหน้า root.html มาใช้

![IMG_8407](https://github.com/user-attachments/assets/85f04f09-c624-4210-863a-7b7658b513bf)

สามารถแก้ไข SSID และ PASSWORD Access Point โดยกด configmenu

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 14 48 11" src="https://github.com/user-attachments/assets/fb45ba80-5ae5-4c0d-ba0b-64cf2d066b6a">

และสามารถแก้หน้า root.html ได้ในไฟล์ root.html

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 14 58 40" src="https://github.com/user-attachments/assets/2439052b-3563-4f11-8319-7eaca96a863e">

เมื่อแก้ไขให้ทำการ build และ run โปรแกรม

<img width="1470" alt="ภาพถ่ายหน้าจอ 2567-11-10 เวลา 14 58 40" src="https://github.com/user-attachments/assets/c927b325-c090-4006-b185-d33c1eb26edc">

