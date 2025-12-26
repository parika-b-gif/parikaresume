<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parika - Resume</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
            padding: 20px;
        }

        .container {
            max-width: 850px;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 40px 50px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        /* Header Section */
        header {
            text-align: center;
            border-bottom: 3px solid #2c3e50;
            padding-bottom: 20px;
            margin-bottom: 25px;
        }

        h1 {
            font-size: 32px;
            color: #2c3e50;
            margin-bottom: 8px;
            font-weight: 600;
        }

        .contact-info {
            font-size: 14px;
            color: #555;
            margin-top: 10px;
        }

        .contact-info a {
            color: #2c3e50;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .contact-info span {
            margin: 0 8px;
        }

        /* Section Styling */
        section {
            margin-bottom: 20px;
        }

        h2 {
            font-size: 18px;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
            margin-bottom: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        /* Summary */
        .summary p {
            text-align: justify;
            font-size: 14px;
            line-height: 1.7;
            color: #444;
        }

        /* Education */
        .education-item {
            margin-bottom: 15px;
        }

        .education-item h3 {
            font-size: 15px;
            color: #2c3e50;
            font-weight: 600;
        }

        .education-item .institution {
            font-size: 14px;
            color: #555;
            font-style: italic;
        }

        .education-item .year {
            font-size: 13px;
            color: #777;
        }

        /* Skills */
        .skills-category {
            margin-bottom: 12px;
        }

        .skills-category h3 {
            font-size: 14px;
            color: #2c3e50;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .skills-list {
            font-size: 14px;
            color: #555;
            line-height: 1.8;
        }

        /* Languages & Interests */
        .simple-list {
            font-size: 14px;
            color: #555;
            line-height: 1.8;
        }

        /* Print Styles */
        @media print {
            body {
                background-color: #fff;
                padding: 0;
            }
            
            .container {
                box-shadow: none;
                padding: 20px;
            }
        }

        @page {
            margin: 0.5in;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header>
            <h1>PARIKA</h1>
            <div class="contact-info">
                <span>📍 Village Khedki Bhood Khalsa, Uttar Pradesh, India</span><br>
                <span>📧 <a href="mailto:parika176@gmail.com">parika176@gmail.com</a></span>
                <span>|</span>
                <span>📱 8477829451</span><br>
                <span>🔗 <a href="https://github.com/parika-b-gif" target="_blank">GitHub</a></span>
                <span>|</span>
                <span>🔗 <a href="https://www.linkedin.com/in/parika-sandhu-735273a24/" target="_blank">LinkedIn</a></span>
            </div>
        </header>

        <!-- Summary -->
        <section class="summary">
            <h2>Professional Summary</h2>
            <p>
                Motivated BCA student and aspiring Full-Stack Web Developer with a strong foundation in frontend and backend technologies. Skilled in HTML, CSS, JavaScript, React, Node.js, and Express.js. Focused on building responsive, user-friendly web applications and continuously improving technical and problem-solving skills.
            </p>
        </section>

        <!-- Education -->
        <section class="education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Bachelor of Computer Applications (BCA)</h3>
                <div class="institution">Eternal University, Baru Sahib, Sirmour</div>
                <div class="year">2024 – Present</div>
            </div>
            <div class="education-item">
                <h3>12th Pass –  Mathematics</h3>
                <div class="year">2023 – 2024</div>
            </div>
        </section>

        <!-- Skills -->
        <section class="skills">
            <h2>Technical Skills</h2>
            
            <div class="skills-category">
                <h3>Frontend & Backend:</h3>
                <div class="skills-list">
                    HTML5, CSS3, JavaScript (ES6+), React.js, Node.js, Express.js, MongoDB (Basic), REST APIs, JSON, Responsive Web Design, Full-Stack Development Fundamentals
                </div>
            </div>

            <div class="skills-category">
                <h3>Soft Skills:</h3>
                <div class="skills-list">
                    Problem Solving, Communication, Teamwork, Time Management, Adaptability, Continuous Learning
                </div>
            </div>
        </section>

        <!-- Certifications -->
        <section class="certifications">
            <h2>Certifications</h2>
            <div class="education-item">
                <h3><a href="https://www.coursera.org/account/accomplishments/certificate/GE30BMPL3F6L" target="_blank" style="color: #2c3e50; text-decoration: none;">Prompt Engineering for ChatGPT</a></h3>
            </div>
            <div class="education-item">
                <h3><a href="https://www.coursera.org/account/accomplishments/certificate/HLZJRRTHPKM8" target="_blank" style="color: #2c3e50; text-decoration: none;">Introduction to Git and GitHub</a></h3>
            </div>
            <div class="education-item">
                <h3><a href="https://www.coursera.org/account/accomplishments/certificate/BSZNDNBOQV51" target="_blank" style="color: #2c3e50; text-decoration: none;">Version Control</a></h3>
            </div>
        </section>

        <!-- Languages -->
        <section class="languages">
            <h2>Languages</h2>
            <div class="simple-list">
                English, Hindi
            </div>
        </section>

    </div>
</body>
</html>






