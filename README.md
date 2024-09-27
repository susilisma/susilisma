<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>甘廉红的个人主页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        section {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .profile {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 20px;
        }
        .profile h2 {
            margin: 0;
            font-size: 24px;
        }
        .profile p {
            margin: 5px 0;
        }
        .content {
            margin-top: 20px;
        }
        .content h3 {
            color: #2980b9;
        }
        .gallery img {
            width: 100%;
            max-width: 600px; /* Adjust the maximum width as necessary */
            margin-bottom: 20px;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        footer a {
            color: #f39c12;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>甘廉红的个人主页</h1>
    <nav>
        <a href="#about">关于我</a>
        <a href="#experience">工作经验</a>
        <a href="#gallery">个人相册</a>
        <a href="#contact">联系我</a>
    </nav>
</header>

<section id="about">
    <div class="profile">
        <img src="profile.jpg" alt="甘廉红">
        <div>
            <h2>甘廉红</h2>
            <p>拥有超过 10 年的管理经验，专注于运营、销售与市场拓展，擅长电子烟行业的渠道开发和客户管理。</p>
        </div>
    </div>
</section>

<section id="experience" class="content">
    <h3>工作经验</h3>
    <ul>
        <li><strong>深圳猫芯科技有限公司</strong> - 运营经理 (2021.09 - 至今)</li>
        <li><strong>印尼 OPPO 有限公司</strong> - SandTalk 运营主管 (2019.01 - 2020.09)</li>
        <li><strong>深圳市新快马科技有限公司</strong> - 运营主管 (2018.01 - 2019.12)</li>
        <li><strong>深圳市千岛旅行有限公司</strong> - 运营经理 (2016.01 - 2017.12)</li>
        <li><strong>印尼亨泰源钢铁公司</strong> - 总经理助理 (2012.06 - 2015.12)</li>
    </ul>
</section>

<section id="gallery" class="content">
    <h3>个人相册</h3>
    <!-- 添加个人图片 -->
    <img src="profile_poster.jpg" alt="甘廉红宣传海报">
</section>

<section id="contact" class="content">
    <h3>联系我</h3>
    <p>手机: 15578830798</p>
    <p>邮箱: ganlianhong@126.com</p>
</section>

<footer>
    <p>© 2024 甘廉红 | <a href="mailto:ganlianhong@126.com">联系我</a></p>
</footer>

</body>
</html>
