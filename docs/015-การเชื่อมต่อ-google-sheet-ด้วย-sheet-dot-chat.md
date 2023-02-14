# 15. การเชื่อมต่อ 💬 Google Sheet ️📊 ด้วย Sheet.chat

ด้วยความสามารถที่หลากหลาย [[001-slack-คืออะไร|Slack]] สามารถเชื่อมต่อกับ Google Sheet ที่เรากำหนดไว้ได้ โดยผ่าน Apps ตัวกลางที่ชื่อว่า [Sheet.chat](https://sheet.chat)

![Sheet.chat](../images/2023-02-14_09-22-59.png){loading=lazy}

## ขีดจำกัดของตัวฟรี

- ข้อมูลใน sheet จะต้องไม่เกิน 200 บรรทัด
- จำกัดการใช้ Google Sheet แค่ 2 อัน

![sheet.chat limitation](../images/2023-02-14_11-15-30.png){loading=lazy}

## การใช้งาน Sheet.chat 

1. ไปที่ [https://sheet.chat/](https://sheet.chat/) แล้วกดปุ่ม `Sign in` 
![Sheet.chat](../images/2023-02-10_12-49-42.png){loading=lazy}
2. กดปุ่ม `Allow` เพื่อเชื่อมต่อ Sheet.chat กับ Slack
![Sign in](../images/2023-02-10_12-50-21.png){loading=lazy}
3. ตัว Sheet.chat จะบอกขั้นตอนในการติดตั้ง 3 ขั้นตอน
![3 steps setup](../images/2023-02-14_10-33-41.png){loading=lazy}
4. เสร็จแล้วกด `Connect a Google account` เพื่อ Sheet.chat จะทำการเชื่อมต่อกับ Google Sheet ผ่าน Google Account
![Sheet.chat เชื่อมต่อ Google Sheet](../images/2023-02-10_12-51-03.png){loading=lazy}
5. แล้วกด `Allow` ให้ Sheet.chat เพื่อเชื่อมต่อ Google Account โดยบอกเงื่อนไขดังกล่าว
![Allow Google Account](../images/2023-02-14_10-36-46.png){loading=lazy}
6. Sheet.chat จะบอกขั้นตอนต่อไป 
![Step 2](../images/2023-02-10_12-51-30.png){loading=lazy}
7. กด `Install the Slack app in your workspace` แล้วจะปรากฎดังรูปด่านล่าง
![Allow Sheet.chat](../images/2023-02-10_12-51-46.png){loading=lazy}
8. กด `Allow` เพื่ออนุญาติให้ Sheet.chat เชื่อมต่อกับ Slack ได้
![เสร็จสิ้นขั้นตอนเชื่อมต่อ Slack](../images/2023-02-14_10-45-25.png){loading=lazy}
9. ให้เราเตรียม Google Sheet ขึ้นมา
![เตรียมข้อมูล Google Sheet](../images/2023-02-10_11-18-54.png){loading=lazy}
<br/>9.1. ใน Google Sheet ต้องมีบรรทัดแรกเป็นข้อมูลหัวตารางเสมอ โดยจะมีกี่ column ก็ได้
<br/>9.2. ชื่อของ Sheet จะต้องเป็นภาษาอังกฤษ
10. กด `Setup your first sheet` จะปรากฎหน้าจอให้เรากรอกรายละเอียด URL ของ Google Sheet
![กรอก step3](../images/2023-02-10_12-53-05.png){loading=lazy}
11. กรอก URL ของ Google Sheet แล้วเลือก Sheet ที่เราจะให้ข้อมูลกรอกลงไป แล้วกด `Submit`
12. Sheet.chat จะให้เราตั้งค่าเพิ่มเติม 
![setup เพิ่มเติม](../images/14-2-2023_11512_sheet.chat.jpeg){loading=lazy}
<br/>12.1. ชื่อของ Sheet จะกลายเป็นคำสั่งใน slack

<br/>12.2. ให้เราเลือก channel ที่จะเป็นตัวแจ้งเตือน

<br/>12.3. กด `Save` เพื่อบันทึก
13. Sheet.chat จะแสดงให้เห็นว่าเรามี Google Sheet ที่ผูกกับ Slack อยู่กี่อัน
![sheet ที่ผูกอยู่](../images/2023-02-14_11-31-43.jpg){loading=lazy}