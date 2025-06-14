<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #87CEEB, #E0F7FA);
            line-height: 1.6;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h1 {
            color: #333;
        }
        nav {
            background-color: #ffd700;
            padding: 10px;
            margin-bottom: 20px;
        }
        nav a {
            margin-right: 15px;
            text-decoration: none;
        }
        .scrolling-text {
            width: 100%;
            overflow: hidden;
            white-space: nowrap;
            box-sizing: border-box;
        }
        .scrolling-text span {
            display: inline-block;
            padding-left: 100%;
            animation: scroll-left 15s linear infinite;
        }
        @keyframes scroll-left {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>KASHIF KASHMEER</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <main>
        <section>
            <h2>About This Page</h2>
            <p>This is a basic HTML template to help you get started with web development.</p>
            <p>You can edit this code and add your own content.</p>
        </section>

        <section>
            <h2>Basic HTML Elements</h2>
            <ul>
                <li>Headings (h1-h6)</li>
                <li>Paragraphs (p)</li>
                <li>Links (a)</li>
                <li>Images (img)</li>
                <li>Lists (ul, ol, li)</li>
            </ul>
        </section>

        <div class="scrolling-text">
            <span>This is a basic scrolling text - MUJEEB: The marquee tag is obsolete in HTML5</span>
        </div>
    </main>

    <footer>
        <p>&copy; 2023 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
