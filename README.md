<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My GitHub Portfolio</title>
    <style>
        /* Apply a background image */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://raw.githubusercontent.com/vaish1710/CS620/main/102393310-07478b80-3f8d-11eb-84eb-392d555ebd29.webp');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: white;
            overflow-x: hidden;
            transform: scale(0.95); /* Zoom out to 95% */
            transform-origin: top left;
            width: 105.26%; /* Adjust width to counteract scaling */
            height: 100%;
            box-sizing: border-box;
        }

        /* Container to ensure content stays within viewport */
        .content-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 120vh; /* Increased height to allow for extra scrolling */
            padding: 20px;
            box-sizing: border-box;
        }

        /* Style for the portfolio content */
        .portfolio {
            width: 100%;
            max-width: 900px;
            padding: 20px;
            border-radius: 15px;
            background-color: rgba(0, 0, 0, 0.6);
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            border: none;
            color: white;
            text-align: center;
            margin-top: 60px;
            margin-bottom: 120px; /* Increased margin-bottom for extra space */
        }

        /* Style for the name */
        h1 {
            font-size: 10em; /* Adjusted font size */
            margin: 0;
            font-weight: bold;
            text-decoration: none;
            text-align: center;
        }

        h1 a {
            text-decoration: none;
            color: inherit;
        }

        /* Paragraph styling */
        p {
            font-size: 1.2em;
            margin: 20px 0;
            color: black;
            background-color: transparent;
            padding: 10px;
            border-radius: 5px;
            max-width: 100%;
            text-align: center;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Button styling */
        .btn {
            display: inline-block;
            padding: 12px 30px;
            font-size: 1.1em;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 3px;
            text-decoration: none;
            cursor: pointer;
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
        }

        .btn:hover {
            background-color: #45a049;
        }

        /* Email Icon Styling */
        .icon img {
            width: 40px;
            height: 40px;
            cursor: pointer;
        }

        .bottom-buttons {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 20px;
            z-index: 1000;
        }

        /* Copyright Styling */
        .copyright {
            position: fixed;
            bottom: 20px;
            right: 20px;
            color: white;
            font-size: 1em;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 5px 10px;
            border-radius: 5px;
        }

        /* Scroll Back Up Link */
        .scroll-up {
            position: fixed;
            bottom: 80px; /* Position above the copyright */
            left: 50%;
            transform: translateX(-50%);
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-align: center;
            cursor: pointer;
            font-size: 1em;
            z-index: 1000;
        }

        .scroll-up:hover {
            background-color: rgba(0, 0, 0, 0.9);
        }
    </style>
</head>
<body>
    <div class="content-container">
        <div class="portfolio">
            <h1>Vaishnavi Paruchuri</h1>
            <p>Data Science and Analytics Master's Student</p>
            <p>I hold an undergraduate degree in Computer Science and am currently pursuing a master's in Data Science and Analytics. My primary interest lies in uncovering valuable outcomes from data, driving insights that lead to informed decisions and innovation.</p>
            <p>Check out my repositories on <a href="https://github.com/vaish1710" target="_blank">GitHub</a>.</p>
        </div>
    </div>

    <!-- Fixed buttons at the bottom -->
    <div class="bottom-buttons">
        <!-- Download Resume Button -->
        <a href="https://raw.githubusercontent.com/vaish1710/CS620/main/Resume.pdf" class="btn" download="Vaishnavi_Resume.pdf">Download Resume</a>

        <!-- Email Icon Button -->
        <div class="icon">
            <a href="mailto:vaish.paruchuri@gmail.com?subject=Portfolio Inquiry">
                <img src="https://cdn.pixabay.com/photo/2016/06/13/17/30/mail-1454733_640.png" alt="Email Icon" />
            </a>
        </div>
    </div>

    <!-- Copyright Text -->
    <div class="copyright">
        &copy; Vaishnavi Paruchuri
    </div>

    <!-- Scroll Back Up Text -->
    <div class="scroll-up" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">
        End of Page. Scroll Back Up
    </div>
</body>
</html>
