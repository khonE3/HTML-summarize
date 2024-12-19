# HTML-summarize
All commands HTML

## 🚀 Fisrt Open and Run basic.HTML
Open and run file --->basic.HTML


## Usage/Examples

สรุป HTML5

```markdown
# สรุปโครงสร้าง HTML5 เบื้องต้น  

## 📝 **Basic Tags**  
- `<h1>` - `<h6>`: หัวข้อ ขนาดตัวอักษรเรียงจากใหญ่ (H1) ถึงเล็ก (H6)  
- `<a>`: สร้างลิงก์ไปยังหน้าอื่น หรือเปิดแท็บใหม่ (ใช้ `target="_blank"`)  
- `<p>`: ย่อหน้า  
- `<b>` / `<strong>`: ตัวหนา  
- `<i>` / `<em>`: ตัวเอียง  
- `<mark>`: ข้อความไฮไลต์  
- `<sub>` / `<sup>`: ตัวห้อย / ตัวบน  
- `<br>`: ขึ้นบรรทัดใหม่  
- `<hr>`: เส้นคั่น  

---

## 🔗 **การใส่ลิงก์ (Links)**  
- `<a href="URL">`: ลิงก์ไปหน้าอื่น  
- `target="_blank"`: เปิดในแท็บใหม่  
ตัวอย่าง:  
```html
<a href="https://translate.google.com" target="_blank">แปลภาษา</a>
```

---

## 🖼 **การใส่รูปภาพ (Images)**  
- `<img src="URL" alt="คำอธิบายรูป">`: แสดงภาพ  
- ใส่ลิงก์บนรูปภาพ:  
```html
<a href="https://translate.google.com" target="_blank">
  <img src="รูป.png" alt="คำอธิบายรูป">
</a>
```

---

## 📊 **ตาราง (Table)**  
- `<table>`: สร้างตาราง  
- `<thead>`: ส่วนหัวตาราง  
- `<tr>`: แถว  
- `<th>` / `<td>`: หัวข้อคอลัมน์ / ข้อมูล  
ตัวอย่าง:  
```html
<table>
  <thead>
    <tr>
      <th>ชื่อ</th>
      <th>นามสกุล</th>
      <th>อายุ</th>
    </tr>
    <tr>
      <td>สมชาย</td>
      <td>ใจดี</td>
      <td>25</td>
    </tr>
  </thead>
</table>
```

---

## 📝 **การทำรายการ (Lists)**  
- **Unordered List** (`<ul>`): รายการแบบจุด  
- **Ordered List** (`<ol>`): รายการแบบตัวเลข  
ตัวอย่าง:  
```html
<ul>
  <li>แมว</li>
  <li>หมา</li>
</ul>
<ol>
  <li>ข้าว</li>
  <li>น้ำ</li>
</ol>
```

---

## 🖥 **การสร้างฟอร์ม (Forms)**  
- `<form>`: ฟอร์ม  
- `<input>`: อินพุต  
- `<fieldset>` / `<legend>`: กรอบและหัวข้อ  
- `<label>`: ป้ายกำกับ  
ตัวอย่าง:  
```html
<form>
  <fieldset>
    <legend>สมัครสมาชิก</legend>
    <label>ชื่อ:</label>
    <input type="text" placeholder="ใส่ชื่อของคุณ">
    <input type="submit" value="ส่ง">
  </fieldset>
</form>
```

---

## 📦 **Block & Inline Elements**  
- **Block Elements**: `<div>`, `<header>`, `<footer>`, `<section>`  
- **Inline Elements**: `<span>`, `<a>`, `<img>`  

---

## 🌐 **iFrame**  
- แสดงหน้าเว็บอื่นในหน้าเว็บปัจจุบัน  
```html
<iframe src="https://www.youtube.com/embed/7MeQxBqchNU" width="560" height="315"></iframe>
```

---

## 🔢 **Entities**  
ใช้แสดงตัวอักษรพิเศษ เช่น `<` &lt;, `>` &gt;  

---

## 🛠 **Semantic Elements**  
- `<header>`: ส่วนหัว  
- `<nav>`: แถบนำทาง  
- `<section>`: ส่วนเนื้อหา  
- `<footer>`: ส่วนท้าย  

---

## 🎥 **เล่นวิดีโอและเสียง**  
- **วิดีโอ**  
```html
<video controls>
  <source src="วิดีโอ.mp4" type="video/mp4">
</video>
```  
- **เสียง**  
```html
<audio controls>
  <source src="เสียง.mp3" type="audio/mp3">
</audio>
```  

