<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qawi's Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #fff;
            color: #24292e;
        }
      .container {
            max-width: 1000px;
            margin: 0 auto;
        }
        h1 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 30px;
        }
        h2 {
            font-size: 1.5rem;
            margin-top: 30px;
            margin-bottom: 15px;
            font-weight: 600;
        }
        ul {
            padding-left: 0;
            list-style: none;
        }
        li {
            margin-bottom: 8px;
        }
        /* Tech Stack Images */
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            align-items: center;
        }
        .tech-stack img {
            height: 28px;
            margin: 2px;
        }
        /* Contact Links */
        .contact-links {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        .contact-links img {
            height: 28px;
        }
        /* Stats Section */
        .stats {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            align-items: flex-start;
        }
        .stats img {
            max-width: 100%;
            height: auto;
        }
        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            body {
                padding: 15px;
            }
            h1 {
                font-size: 1.8rem;
                margin-bottom: 25px;
            }
            h2 {
                font-size: 1.3rem;
                margin-top: 25px;
            }
            .tech-stack {
                justify-content: center;
            }
            .contact-links {
                justify-content: center;
            }
            .stats {
                flex-direction: column;
                align-items: center;
                gap: 15px;
            }
            .stats img {
                width: 100%;
                max-width: 400px;
            }
        }
        @media (max-width: 480px) {
            body {
                padding: 10px;
            }
            h1 {
                font-size: 1.5rem;
                margin-bottom: 20px;
            }
            h2 {
                font-size: 1.2rem;
                margin-top: 20px;
            }
            .tech-stack img,
            .contact-links img {
                height: 24px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hey there I'm Qawi 👋🏿👋🏿👋🏿</h1>
        <h2>About Me</h2>
        <ul>
            <li>🐱‍👤I'm a teen Front-end developer from Nigeria</li>
            <li>🔭 I'm currently working on developing my skills further and connecting with other devs</li>
            <li>🌱 I'm currently learning JavaScript and it's frameworks</li>
            <li>🎮 I love playing mobile games and watching animes.</li>
            <li>📫 You can connect with me on Twitter, LinkedIn and here on github</li>
        </ul>
        <h2>Tech Stack</h2>
        <div class="tech-stack">
            <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
            <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
            <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" /> 
            <img src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
            <img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
            <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
            <img src="https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white" alt="WordPress" />
            <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
            <img src="https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white" alt="SASS" />
            <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
            <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
        </div>
        <h2>Contact Me</h2>
        <div class="contact-links">
            <a href="https://www.linkedin.com/in/abdul-qawi-laniyan-173355248/">
                <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
            </a>
            <a href="https://twitter.com/Devdotun">
                <img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white" alt="Twitter" />
            </a>
        </div>
        <h2>Stats</h2>
        <div class="stats">
            <img src="https://github-readme-stats.vercel.app/api?username=Oladotunlaniyan&show_icons=true&theme=radical" alt="GitHub Stats" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Oladotunlaniyan&layout=compact" alt="Top Languages" />
        </div>
    </div>
</body>
</html>
