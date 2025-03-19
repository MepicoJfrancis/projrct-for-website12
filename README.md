<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Webpage Portfolio</title>
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <style>
        body {
            font-family: 'Lucida Console', sans-serif;
            line-height: 1.6;
            margin: 1.5;
            padding: 1.5;
            background-color: #FAE8B4;
            color: #000000;
        }

        header {
            background-color: #244414;
            color: #ee8036;
            padding: 60px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li a {
            color: #00ffb3;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        main {
            padding: 30px;
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
            font-size: 1.6rem;
        }

        h3 {
            color: #5315e4;
            font-size: 2.5rem;
        }

        p {
            font-size: 2rem;
            line-height: 1.8;
        }

        .video-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            margin-bottom: 20px;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 2px solid #333;
            border-radius: 10px;
        }


        .image-container, .map-container, .image-map-container {
            margin-bottom: 20px;
            text-align: center;
        }

        .image-container img {
            width: 100%;
            max-width: 400px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .map-container iframe {
            width: 100%;
            height: 450px;
            border: 2px solid #a7ff03;
            border-radius: 10px;
        }

        .image-map-container img {
            width: 100%;
            max-width: 600px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        aside {
            background-color: #e99313;
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
        }

        aside h3 {
            margin-top: 0;
        }

        aside ul {
            list-style: none;
            padding: 0;
        }

        aside ul li {
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>🚀 Welcome to Our Portfolio! 🚀</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Were are currently collaborating with My teammate on this project, and together we're building something amazing!</p>
            <p>Here is  a fun fact: I ♥ using symbol entities like &amp; and &lt; in my projects!</p>
            <p> As for my teamates he Like design the website </p>
        </section>

        <section id="interests">
            <h2>Our Interests</h2>
            <article>
                <h3>YouTube Video: Our Favorite Tutorial</h3>
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/Jz9OX0_Dy5E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </article>



            <article>
                <h3>Our University: Cebu Eastern College</h3>
                <div class="image-container">
                    <img src="https://pbs.twimg.com/profile_images/1364256335546617866/zeFzz7e6_400x400.jpg" alt="Cebu Eastern College Logo">
                </div>
                <div class="map-container">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3925.258693029914!2d123.8960169!3d10.2944329!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33a99bfcc60d650d%3A0x5ee73506c68dd233!2sCebu%20Eastern%20College%20Cebu%20city!5e0!3m2!1sen!2sph!4v1698765432100!5m2!1sen!2sph" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </article>




            <article>
                <h3>Clickable Image Map</h3>
                <div class="image-map-container">
                    <img src="image-map.jpg" alt="Clickable Image Map" usemap="#resources">
                    <map name="resources">
                        <area shape="rect" coords="0,0,200,200" href="https://www.google.com/maps/@10.2946584,123.8967177,3a,90y,247.53h,90.8t/data=!3m7!1e1!3m5!1sb0EiFJyq-4ia0bCrVTFY4A!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-0.7971370991046882%26panoid%3Db0EiFJyq-4ia0bCrVTFY4A%26yaw%3D247.52555228005804!7i16384!8i8192?entry=ttu&g_ep=EgoyMDI1MDMxMi4wIKXMDSoASAFQAw%3D%3D" alt="Wikipedia">
                        <area shape="rect" coords="200,0,400,200" href="https://www.google.com/maps/@10.2946584,123.8967177,3a,90y,247.53h,90.8t/data=!3m7!1e1!3m5!1sb0EiFJyq-4ia0bCrVTFY4A!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-0.7971370991046882%26panoid%3Db0EiFJyq-4ia0bCrVTFY4A%26yaw%3D247.52555228005804!7i16384!8i8192?entry=ttu&g_ep=EgoyMDI1MDMxMi4wIKXMDSoASAFQAw%3D%3D" alt="GitHub">
                    </map>
                </div>
            </article>
        </section>

        <aside>
            <h3>Favorite Emojis</h3>
            <ul>
                <li>&#x1F600; - Smiling Face</li>
                <li>&#x1F609; - Winking Face</li>
                <li>&#x1F60E; - Smiling Face with Sunglasses</li>
            </ul>
        </aside>
    </main>

    <footer id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:jfrancistm211@gmail.com">jfrancistm211@gmail.com</a></p>
        <p>&copy;2025 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
