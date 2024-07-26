<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعي الشخصي</title>
    <link rel="stylesheet" href="style.css"> <!-- ربط ملف CSS -->
</head>
<body>
    <header>
        <h1>مرحبًا بك في موقعي</h1>
    </header>
    <main>
        <section>
            <h2>حول</h2>
            <p>هذا هو وصف الموقع.</p>
        </section>
        <section>
            <h2>خدماتي</h2>
            <ul>
                <li>خدمة 1</li>
                <li>خدمة 2</li>
                <li>خدمة 3</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 جميع الحقوق محفوظة</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header, footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

main {
    padding: 20px;
}

h1, h2 {
    color: #333;
}document.addEventListener('DOMContentLoaded', function() {
    alert('مرحبًا بك في موقعي!');
});
