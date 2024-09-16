<!DOCTYPE html>
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
            background-size: cover; /* Ensures the image covers the entire viewport */
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh; /* Ensures the body takes the full viewport height */
            color: white;
            overflow-x: hidden; /* Prevent horizontal scroll */
        }

        /* Center the content and fill the entire page */
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100vw; /* Ensure container fills the viewport width */
            height: 100vh; /* Ensure container fills the viewport height */
            text-align: center;
            background-color: rgba(0, 0, 0, 0.6); /* Darken the background for readability */
            position: relative; /* Changed from absolute to ensure content is centered */
        }

        /* Style for the portfolio content */
        .portfolio {
            padding: 20px;
            border-radius: 15px;
            background-color: rgba(0, 0, 0, 0.6); /* Slightly darker background for readability */
            position: relative; /* Ensure proper centering */
            box-shadow: none !important; /* Force removal of box shadow */
            border: none; /* Ensure no border is applied */
        }

        /* Style for the name */
        h1 {
            font-size: 20em; /* Increase font size to 20em */
            margin: 0;
            font-weight: bold;
            text-decoration: none; /* Ensure no underline */
        }

        /* Ensure no underline for links within h1 */
        h1 a {
            text-decoration: none; /* Ensure no underline for links within h1 */
            color: inherit; /* Ensure links inherit the color from h1 */
        }

        /* Paragraph styling */
        p {
            font-size: 1.2em;
            margin: 0;
            color: black; /* Change paragraph color to black */
            background-color: rgba(255, 255, 255, 0.8); /* Slightly opaque background for readability */
            padding: 10px; /* Add padding for better readability */
            border-radius: 5px; /* Rounded corners for paragraphs */
        }

        a {
            color: #4CAF50;
            text-decoration: none; /* Ensure no underline for links */
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline; /* Underline only on hover */
        }

        /* Button styling */
        .btn {
            display: inline-block;
            padding: 12px 30px; /* Adjusted padding */
            font-size: 1.1em;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 3px; /* Reduced corner radius */
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2); /* Add subtle shadow */
            text-decoration: none;
            cursor: pointer;
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
            opacity: 0; /* Start with buttons hidden */
            visibility: hidden; /* Hide buttons initially */
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
        }

        .btn:hover {
            background-color: #45a049;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.4); /* Darker shadow on hover */
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
        }
    </style>
</head>
<body>
    <div class="container">
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

    <script>
        // JavaScript to show buttons when scrolled to the bottom
        window.addEventListener('scroll', function() {
            const bottomButtons = document.querySelector('.bottom-buttons');
            if (window.innerHeight + window.scrollY >= document.body.offsetHeight) {
                bottomButtons.style.opacity = '1';
                bottomButtons.style.visibility = 'visible';
            } else {
                bottomButtons.style.opacity = '0';
                bottomButtons.style.visibility = 'hidden';
            }
        });
    </script>
</body>
</html>
