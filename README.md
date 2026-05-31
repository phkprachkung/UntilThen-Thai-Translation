<div align="center">
  
# 🇹🇭 Until Then - Thai Translation (ม็อดแปลภาษาไทย)

![Version](https://img.shields.io/badge/Version-1.3.1-blue.svg)
![Status](https://img.shields.io/badge/Status-เนื้อเรื่อง_97%25_|_UI_90%25_|_ฟอนต์_95%25-brightgreen.svg)
![Platform](https://img.shields.io/badge/Platform-PC_(Steam)-lightgrey.svg)

โปรเจกต์แปลภาษาไทยอย่างไม่เป็นทางการสำหรับเกม **Until Then** เกมแนว Narrative Adventure ที่เต็มไปด้วยอารมณ์และเรื่องราวที่น่าประทับใจ

[ดาวน์โหลดไฟล์แปลภาษาไทยล่าสุด ที่หน้า Releases](https://github.com/phkprachkung/UntilThen-Thai-Translation/releases)

</div>

---

## 📊 สถานะการแปล
* **เนื้อเรื่องทั้งหมด:** 💯 97% (แปลครบจบเกมแล้ว!)
* **เมนูและอินเตอร์เฟส:** ✅ 90% (แปลข้อความส่วนที่ลึกที่สุดของโค้ด เช่น แอปพยากรณ์อากาศ, หน้าจอซื้อตั๋วรถไฟ, คำสั่งโซเชียลมีเดีย)
* **ฟอนต์ภาษาไทย:** ✅ 95% (ปลดล็อกระบบเกมให้รองรับฟอนต์ไทยสมบูรณ์แบบ ใช้ฟอนต์ NotoSansThai แก้ปัญหาสระลอยและฟอนต์ไม่มีหัวเรียบร้อย)

---

## 📸 ภาพตัวอย่างในเกม (Screenshots)

<p align="center">
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/77f1b81b-eb50-4599-b636-2f43934bfe45" />
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/8c273925-8017-4469-8fb9-b10a49b0cf1e" />
</p>
<p align="center">
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/6a54fd19-fd21-4462-9583-a074d4c28ed2" />
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/e7208c62-1a7e-4eb5-a935-9b427075d815" />
</p>
<p align="center">
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/b803c3ee-da99-41c4-9755-6468d9576b66" />
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/9580cedf-94de-4ce4-b06e-2c0b55a6fb18" />
</p>
<p align="center">
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/968d659a-b8f2-4c43-b386-45462993b41d" />
  <img width="49%" alt="image" src="https://github.com/user-attachments/assets/e3a0fe11-77a2-4cc6-a359-d29c8799a167" />
</p>







---

## ⚙️ วิธีการแพ็คไฟล์และติดตั้งม็อด
ในโฟลเดอร์นี้คือไฟล์ Source ของม็อดแปลภาษาไทย ที่คุณสามารถนำไปแพ็คอัปเดตไฟล์ `.pck` ดั้งเดิมของตัวเกมได้เลย

**สิ่งที่ต้องเตรียม:**
1. โปรแกรม **Godot PCK Explorer**
2. ไฟล์ Source Code โฟลเดอร์ `game` จาก Repository นี้

**ขั้นตอนการติดตั้งและแพ็คไฟล์:**
1. เปิดโปรแกรม **Godot PCK Explorer** ไปที่เมนู `File > Open File` เลือกไฟล์ `UntilThen.pck` ของตัวเกมในโฟลเดอร์ Steam
2. เลือกเมนู `Extract > Extract All` เพื่อแตกไฟล์ทั้งหมดของเกมออกมา (แนะนำให้สร้างโฟลเดอร์ `game` รอไว้แล้วแตกไฟล์ลงไป)
3. นำโฟลเดอร์ `game` จาก Source Code ของเรา **ไปลากวางทับ** โฟลเดอร์เกมที่คุณเพิ่งแตกไฟล์มา (กดยอมรับ Replace All)
4. ในโปรแกรม Godot PCK Explorer ไปที่เมนู `File > Pack or Embed Folder`
5. ตั้งค่าการแพ็กไฟล์ดังนี้:
   - **Path to the folder to pack:** เลือกโฟลเดอร์ `game` ที่เพิ่งวางม็อดทับไป
   - ติ๊กถูกที่ **Enabled patching** แล้วเลือกไฟล์ `UntilThen.pck` ต้นฉบับ
   - กำหนดเวอร์ชันเป็น **Godot 4.1.4**
6. กด **Pack** ระบบจะถามหาที่เซฟ ให้ตั้งชื่อเป็น `UntilThen.pck` แล้วบันทึกทับไฟล์เกมตัวเก่าใน Steam ไปเลย 
*(⚠️ แนะนำให้สำรองไฟล์ `.pck` ต้นฉบับของเกมเก็บไว้ก่อน)*
7. คุณสามารถลบโฟลเดอร์ที่แตกออกมาทิ้งไปได้เลย เข้าเกมและสนุกกับเนื้อเรื่องภาษาไทยได้ทันที!

---

## ☕ ช่องทางการสนับสนุน (Support/Donate)
หากคุณชื่นชอบผลงานแปลนี้ และอยากสนับสนุนยาแก้ปวดหลังหรือค่าน้ำชาให้กับทีมงานแปล (DongDib Studio) สามารถสนับสนุนได้ตามช่องทางนี้ครับ:

<img width="100" height="100" alt="Donate QR" src="https://github.com/user-attachments/assets/654a21a5-876f-486a-8308-3768d5b01b40" />

หรือเพียงแค่ช่วยกด ⭐️ **Star** ที่มุมขวาบนของโปรเจกต์นี้ ก็เป็นกำลังใจให้ผู้แปลมากๆ แล้วครับ ขอบคุณครับ 🙏

---

## 🤝 การแจ้งปัญหา (Issues)
หากพบคำผิด บั๊กแปลไม่แสดงผล หรือต้องการเสนอแนะการแก้ไขคำ สามารถแจ้งได้ที่หน้า **[Issues]** ของ GitHub นี้ได้เลยครับ
