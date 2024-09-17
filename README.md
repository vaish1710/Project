
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My GitHub Portfolio</title>
    <style>
        /* Apply a space-themed background for the entire page */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000; /* Fallback color */
            background-image: url('https://blenderartists.org/uploads/default/original/4X/7/e/2/7e2d7bea4ac21388c4a96e1371f375c4ce00094b.jpg'); /* Space background image */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: white; /* Adjust text color for better contrast */
            overflow-x: hidden;
            height: 100vh; /* Full viewport height */
            box-sizing: border-box;
        }

        /* White background content section with transparent overlay */
        .content-container {
            position: relative;
            background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white */
            padding: 20px;
            border-radius: 15px;
            box-sizing: border-box;
            max-width: 900px;
            margin: 0 auto; /* Center content horizontally */
            text-align: center; /* Center text inside content */
            z-index: 1; /* Ensure this content is on top of the background */
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        /* Style for the portfolio content */
        .portfolio {
            padding: 20px;
            border-radius: 15px;
            background-color: white; /* Set background color to white */
            box-shadow: none; /* Remove shadow */
            border: none;
            color: black; /* Change text color to black */
        }

        /* Style for the name */
        h1 {
            font-size: 5em; /* Adjusted to a reasonable size */
            margin: 0;
            font-weight: bold;
            text-decoration: none;
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

        /* Fixed bottom space styling */
        .bottom-space {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }

        /* Copyright Styling */
        .copyright {
            position: fixed;
            bottom: 20px;
            right: 20px;
            color: white; /* Ensure visibility on dark background */
            font-size: 1em;
            background-color: rgba(0, 0, 0, 0.7); /* Darker background for copyright */
            padding: 5px 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <!-- White Background Content Section -->
    <div class="content-container">
        <!-- Portfolio Content -->
        <div class="portfolio">
            <h1>Vaishnavi Paruchuri</h1>
            <p>Data Science and Analytics Master's Student</p>
            <p>I hold an undergraduate degree in Computer Science and am currently pursuing a master's in Data Science and Analytics. My primary interest lies in uncovering valuable outcomes from data, driving insights that lead to informed decisions and innovation.</p>
            <p>Check out my repositories on <a href="https://github.com/vaish1710" target="_blank">GitHub</a>.</p>
        </div>

        <!-- Buttons -->
        <div class="bottom-space">
            <!-- Download Resume Button -->
            <a href="https://raw.githubusercontent.com/vaish1710/CS620/main/Resume.pdf" class="btn" download="Vaishnavi_Resume.pdf">Download Resume</a>

            <!-- Email Icon Button -->
            <div class="icon">
                <a href="mailto:vaish.paruchuri@gmail.com?subject=Portfolio Inquiry">
                    <img src="https://cdn.pixabay.com/photo/2016/06/13/17/30/mail-1454733_640.png" alt="Email Icon" />
                </a>
            </div>
        </div>
    </div>

    <!-- Copyright Text -->
    <div class="copyright">
        &copy; Vaishnavi Paruchuri
    </div>
</body>
</html>
