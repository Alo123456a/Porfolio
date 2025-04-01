# Porfolio
A b o u t  m e
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang web cá nhân</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            background-color: #F0F0F0;
            color: #333;
            scroll-behavior: smooth;
        }

        header {
            padding: 20px 40px;
            background-color: white;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 10;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header nav a {
            margin-left: 20px;
            text-decoration: none;
            color: #333;
            transition: color 0.3s;
        }

        header nav a:hover {
            color: #0077b6;
        }

        section {
            padding: 100px 40px;
            max-width: 1200px;
            margin: auto;
            transition: all 0.5s ease;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 30px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
            transition: all 0.5s ease;
            cursor: pointer;
        }

        .card:hover {
            transform: scale(1.03);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .morph {
            background: linear-gradient(135deg, #e0e0e0, #ffffff);
            border-radius: 40px;
            padding: 30px;
            transition: all 0.5s ease;
        }

        .morph:hover {
            border-radius: 50px;
            background: linear-gradient(135deg, #d0d0d0, #f7f7f7);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>Trang cá nhân của bạn</h1>
    <nav>
        <a href="#home">Giới thiệu</a>
        <a href="#projects">Dự án</a>
        <a href="#contact">Liên hệ</a>
    </nav>
</header>

<section id="home" class="morph">
    <h2>Giới thiệu</h2>
    <p>Xin chào! Mình là một nhà thiết kế yêu thích phong cách tối giản và hiện đại.</p>
</section>

<section id="projects">
    <div class="card">
        <h2>Dự án 1</h2>
        <p>Mô tả ngắn về dự án của bạn.</p>
    </div>
    <div class="card" style="margin-top: 20px;">
        <h2>Dự án 2</h2>
        <p>Mô tả ngắn về dự án của bạn.</p>
    </div>
    <div class="card" style="margin-top: 20px;">
        <h2>Dự án 3</h2>
        <p>Mô tả ngắn về dự án của bạn.</p>
    </div>
</section>

<section id="contact" class="morph">
    <h2>Liên hệ</h2>
    <p>Email: yourname@email.com</p>
</section>

<footer>
    <p>© 2025 Trang cá nhân của bạn. Thiết kế bởi bạn.</p>
</footer>

</body>
</html>
