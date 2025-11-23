[Untitled-1.html](https://github.com/user-attachments/files/23694115/Untitled-1.html)[Uploading Untitled<!DOCTYPE html>
<html lang="th">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHER YOUR SELVES</title>
    <style>
        /* ส่วนนี้คือ CSS ที่จะช่วยกำหนดรูปแบบและการจัดวาง */
        body {
            /* กำหนดรูปภาพพื้นหลัง */
            background-image: url('html.jpg.jpg');

            /* ตั้งค่าให้รูปภาพครอบคลุมทั้งพื้นที่ */
            background-size: cover;

            /* ป้องกันไม่ให้รูปภาพซ้ำ */
            background-repeat: no-repeat;

            /* กำหนดตำแหน่งของรูปภาพให้อยู่กึ่งกลาง */
            background-position: center;

            /* กำหนดความสูงของ body ให้เต็มหน้าจอ */
            height: 100vh;

            /* ใช้ Flexbox เพื่อจัดวางปุ่มไว้ด้านล่าง */
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            /* จัดให้อยู่ด้านล่าง */
            align-items: center;
            /* จัดให้อยู่ตรงกลางแนวนอน */
            margin: 0;
            /* ลบระยะขอบเริ่มต้นของ body */
            padding-bottom: 50px;
            /* เพิ่มพื้นที่ด้านล่างเพื่อไม่ให้ปุ่มติดขอบ */
        }

        .next-button {
            /* จัดรูปแบบสำหรับปุ่ม */
            padding: 10px 20px;
            font-size: 18px;
            background-color: #007bff;
            /* สีพื้นหลังปุ่ม */
            color: white;
            /* สีข้อความ */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .next-button:hover {
            /* เปลี่ยนสีเมื่อชี้เมาส์ */
            background-color: #00b34b;
        }
    </style>
</head>

<body>
    <button class="next-button" onclick="window.location.href='next_page.html'">
        ถัดไป
    </button>
</body>

</html>-1.html…]()
