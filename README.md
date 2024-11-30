<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์แนะนำตัวเอง</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>สวัสดีครับ/ค่ะ, ผม/ฉัน [ชื่อ]</h1>
        <nav>
            <ul>
                <li><a href="#about">เกี่ยวกับฉัน</a></li>
                <li><a href="#portfolio">ผลงาน</a></li>
                <li><a href="#services">บริการ</a></li>
                <li><a href="#contact">ติดต่อ</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>เกี่ยวกับฉัน</h2>
        <p>ผม/ฉันเป็น [อาชีพ] ที่มีความสนใจใน [สิ่งที่คุณสนใจ].</p>
        <p>ข้อมูลเพิ่มเติมเกี่ยวกับการศึกษาและประสบการณ์การทำงานของฉัน...</p>
    </section>
    <section id="portfolio">
        <h2>ผลงานของฉัน</h2>
        <p>ดูผลงานที่ฉันเคยทำ...</p>
        <div class="portfolio-item">
            <img src="project1.jpg" alt="โปรเจกต์ 1">
            <p>รายละเอียดเกี่ยวกับโปรเจกต์ 1</p>
        </div>
    </section>
    <section id="services">
        <h2>บริการของฉัน</h2>
        <p>รายละเอียดเกี่ยวกับบริการที่คุณเสนอ...</p>
    </section>
    <section id="contact">
        <h2>ติดต่อฉัน</h2>
        <p>อีเมล: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
        <p>หรือกรอกแบบฟอร์มด้านล่าง</p>
        <form action="submit_form.php" method="post">
            <label for="name">ชื่อ:</label>
            <input type="text" id="name" name="name">
            <label for="message">ข้อความ:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">ส่งข้อความ</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 [ชื่อของคุณ]. ทุกสิทธิ์สงวนไว้.</p>
    </footer>
</body>
</html>
