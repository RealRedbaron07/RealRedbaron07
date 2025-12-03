<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            color: #222;
        }

        h1, h2 {
            font-weight: 600;
        }

        #header {
            margin-bottom: 40px;
        }

        #projects, #featured-project {
            margin-top: 40px;
        }

        .icon-row {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 12px;
        }

        .section-box {
            border-left: 4px solid #444;
            padding-left: 12px;
            margin-top: 20px;
        }

        ul {
            margin-top: 10px;
        }

        .project-item {
            margin-bottom: 25px;
        }

        /* Ensures no fonts cause unsupported symbols */
        * {
            font-family: Arial, sans-serif;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header id="header">
        <h1>Mustafa Alp ARI</h1>
        <p>Computer Engineering Student | Java Developer | Trading Systems Enthusiast</p>
    </header>


    <!-- ABOUT SECTION -->
    <section id="about">
        <h2>About Me</h2>
        <div class="section-box">
            <p>
                I am a computer engineering student with experience in Java, Python-based trading systems,
                data processing, and API-driven automation. I enjoy working on real-world projects that
                require engineering thinking and measurable outcomes.
            </p>
        </div>
    </section>


    <!-- FEATURED PROJECT SECTION WITH SVG (NO EMOJI) -->
    <section id="featured-project">
        <h2>Featured Project</h2>

        <div class="icon-row">
            <!-- SVG ICON (SOLID, NEVER BREAKS) -->
            <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="black" stroke-width="2"
                stroke-linecap="round" stroke-linejoin="round">
                <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                <polyline points="2 17 12 22 22 17"></polyline>
                <polyline points="2 12 12 17 22 12"></polyline>
            </svg>

            <span style="font-size: 1.25rem; font-weight: 500;">Python Trading Bot</span>
        </div>

        <div class="section-box">
            <p>
                A Python-based automated trading bot using Streamlit, Yahoo Finance API, and Binance API.
                This project strengthened my applied algorithmic trading skills, API integration knowledge,
                and version control experience using Git.
            </p>

            <ul>
                <li>Built with Python 3</li>
                <li>Streamlit interface for live strategy monitoring</li>
                <li>Yahoo Finance + Binance real-time data feeds</li>
                <li>Automated buy/sell signal algorithm</li>
                <li>Git workflow experience (branching, PRs, versioning)</li>
            </ul>
        </div>
    </section>


    <!-- OTHER PROJECTS -->
    <section id="projects">
        <h2>Other Projects</h2>

        <div class="project-item section-box">
            <h3>Football Manager Transfer Market Analyzer (Java)</h3>
            <p>
                A Java-based analyzer that compares AI vs user transfer decisions using extracted save-file data.
                Focuses on parsing, aggregation, and trend scoring.
            </p>
        </div>

        <div class="project-item section-box">
            <h3>Java Algorithms Practice Suite</h3>
            <p>
                A collection of Java algorithm implementations, including sorting, searching,
                hashing, array and collection utilities, and interview-style problems.
            </p>
        </div>
    </section>


    <!-- CONTACT -->
    <section id="contact">
        <h2>Contact</h2>
        <div class="section-box">
            <p>Email: example@email.com</p>
            <p>GitHub: github.com/yourprofile</p>
        </div>
    </section>

</body>
</html>
