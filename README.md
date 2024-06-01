<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Louka's Video Creations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #1e1e1e;
            color: #f0f8ff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            color: #1e90ff;
        }
        footer {
            background-color: #1e1e1e;
            color: #f0f8ff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .video-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .video-item {
            flex: 1 1 calc(33% - 20px);
            background-color: #333;
            color: #f0f8ff;
            padding: 10px;
            border-radius: 8px;
        }
        .video-item video {
            width: 100%;
            border-radius: 8px;
        }
        .cta {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            text-align: center;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
        }
        .cta:hover {
            background-color: #e03e00;
        }
    </style>
</head>
<body>
    <header>
        <h1>Louka's Video Creations</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#videos">Videos</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hi, I'm Louka. I specialize in creating personalized videos for various occasions. Whether it's a hangout with friends, a special event, or a creative reel for social media, I've got you covered. My work has brought joy and cherished memories to many, and I'm excited to offer my services to you.</p>
        </section>
        <section id="videos" class="section">
            <h2>My Videos</h2>
            <div class="video-container">
                <!-- Example video items. Replace with your actual videos. -->
                <div class="video-item">
                    <video controls>
                        <source src="video1.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <p>Title of Video 1</p>
                </div>
                <div class="video-item">
                    <video controls>
                        <source src="video2.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <p>Title of Video 2</p>
                </div>
                <div class="video-item">
                    <video controls>
                        <source src="video3.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <p>Title of Video 3</p>
                </div>
            </div>
        </section>
        <section id="services" class="section">
            <h2>Services</h2>
            <p>I offer customized video creation services for:</p>
            <ul>
                <li>Social media reels (Instagram, TikTok, etc.)</li>
                <li>Personal event highlights</li>
                <li>Memorable moments compilations</li>
                <li>And more!</li>
            </ul>
            <a href="#contact" class="cta">Get in Touch</a>
        </section>
        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <p>If you have any questions or want to commission a video, please reach out to me:</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
                <input type="submit" value="Submit">
            </form>
        </section>
    </div>
    <footer>
        &copy; 2024 Louka's Video Creations. All rights reserved.
    </footer>
</body>
</html>
