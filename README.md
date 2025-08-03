<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Eloheh Healthcare - Services</title>
    <style>
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        body {
            font-family: 'Verdana', sans-serif;
            color: #333333;
            margin: 0;
            padding: 0;
        }

        .banner {
            background-image: url('https://img.freepik.com/free-photo/medical-banner-with-doctor-wearing-goggles_23-2149611193.jpg?w=740');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 1px 1px 3px black;
            font-size: 30px;
        }

        .banner h1 {
            font-size: 36px;
            font-family: 'Georgia', serif;
            background-color: rgba(0, 0, 0, 0.4);
            padding: 10px 20px;
            border-radius: 8px;
        }

        h2 {
            margin-top: 40px;
        }

        ul, ol {
            padding-left: 20px;
        }

        .download-btn {
            display: inline-block;
            background-color: #004c3f;
            color: white;
            padding: 10px 20px;
            border-radius: 6px;
            font-size: 16px;
            font-weight: bold;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        .download-btn:hover {
            background-color: #006b50;
        }
    </style>
</head>
<body>

    <header class="banner">
        <h1>Eloheh Healthcare Services</h1>
    </header>

    <div class="container">
    <center>
        <h2>Included Services</h2>
    </center>
        <p><strong>Eloheh Healthcare</strong> was <u>established in 2015</u> with a mission to deliver inclusive, compassionate, and accessible healthcare to individuals from all walks of life.</p>

        <ul>
            <li>In-home healthcare services</li>
            <li>Telehealth consultations</li>
            <li>Wellness education & prevention programs</li>
            <li>Medical equipment & supply delivery</li>
            <li>Community health initiatives</li>
            <li>Chronic illness care coordination</li>
            <li>Sustainability and community support</li>
        </ul>

        <img src="https://via.placeholder.com/800x300.png?text=Eloheh+Team+and+Community+Wellness" alt="Eloheh Team Photo">

        <p>For more on global health efforts, visit the <a href="https://www.who.int" target="_blank">World Health Organization</a>.</p>

        <p><a class="download-btn" href="eloheh_services_brochure.pdf" download>📄 Download Our Brochure</a></p>

        <p><a href="mailto:contact@elohehhealth.org">📧 Contact Me</a></p>
    </div>

    <footer>
        <p>Last updated: 
            <script>
                document.write(new Date(document.lastModified).toLocaleDateString());
            </script>
        </p>
    </footer>

</body>
</html>
