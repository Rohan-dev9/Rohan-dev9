 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77b5fe 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #showcase {
            min-height: 400px;
            background: url('https://via.placeholder.com/1200x400') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        #main {
            padding: 20px;
        }
        .dark {
            padding: 15px;
            background: #333;
            color: #fff;
            margin-top: 10px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>My GitHub Portfolio</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="showcase">
        <div class="container">
            <h1>Welcome to My GitHub Portfolio</h1>
            <p>Discover my projects and skills</p>
        </div>
    </section>
    <section id="main" class="container">
        <div id="projects" class="dark">
            <h2>Projects</h2>
            <p>Here you can add details about your projects.</p>
        </div>
        <div id="about" class="dark">
            <h2>About Me</h2>
            <p>Share some information about yourself here.</p>
        </div>
        <div id="contact" class="dark">
            <h2>Contact</h2>
            <p>Include your contact information here.</p>
        </div>
    </section>
</body>
</html>
