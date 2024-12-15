<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Osama Shaikh - GitHub Profile</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            padding-left: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .typing-container {
            text-align: center;
            margin-bottom: 40px;
        }
        canvas {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="typing-container">
            <h1>
                <span id="typed"></span>
            </h1>
        </div>

        <div class="section">
            <h2>🚀 About Me</h2>
            <ul>
                <li><strong>Education:</strong> Bachelor of Engineering in Computer Engineering, Thakur College of Engineering Technology (CGPA: 9.87)</li>
                <li><strong>Location:</strong> Mumbai, India</li>
                <li><strong>Current Role:</strong> Consultant - Package Implementation at LTIMindtree Limited</li>
                <li><strong>Achievements:</strong> Winner of JPMorgan Code for Good Hackathon 2022</li>
            </ul>
        </div>

        <div class="section">
            <h2>🛠️ Skills</h2>
            <canvas id="skillsChart"></canvas>
        </div>

        <div class="section">
            <h2>🌟 Projects & Experience</h2>
            <ul>
                <li><strong>XploRE:</strong> Automated interview management tool improving recruitment efficiency by 40%.</li>
                <li><strong>ICICI Disbursement Hub:</strong> Streamlined loan processing, reducing manual interventions by 30%.</li>
                <li><strong>Angular Enquiry UI:</strong> Enhanced task tracking efficiency by 40% with modernized UI components.</li>
            </ul>
        </div>

        <div class="section">
            <h2>🏅 Achievements</h2>
            <ul>
                <li>Secured <strong>1st position</strong> in Academics (Thakur College of Engineering)</li>
                <li><strong>Runner-up</strong> at JPMorgan Code for Good Hackathon 2022</li>
                <li>Published and presented papers at <strong>MULTICON-W 2022</strong></li>
            </ul>
        </div>

        <div class="section">
            <h2>🔗 Let's Connect</h2>
            <ul>
                <li><strong>GitHub:</strong> <a href="https://github.com/usamashaikh13">usamashaikh13</a></li>
                <li><strong>LeetCode:</strong> <a href="https://leetcode.com/u/shaikhusama745/">shaikhusama745</a></li>
                <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/osama-shaikh-103b941a6/">Osama Shaikh</a></li>
            </ul>
        </div>
    </div>

    <script>
        // Typing animation
        new Typed('#typed', {
            strings: [
                "Hi there 👋, I'm Usama Shaikh!",
                "Welcome to my GitHub Profile!",
                "Full Stack Developer | Open Source Contributor",
                "Building scalable and efficient apps! 💻"
            ],
            typeSpeed: 50,
            backSpeed: 25,
            loop: true
        });

        // Skills chart
        const ctx = document.getElementById('skillsChart').getContext('2d');
        new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['JavaScript', 'TypeScript', 'React', 'Angular', 'Node.js', 'Spring Boot', 'MongoDB'],
                datasets: [{
                    label: 'Proficiency',
                    data: [90, 85, 80, 85, 75, 70, 80],
                    backgroundColor: 'rgba(52, 152, 219, 0.2)',
                    borderColor: 'rgba(52, 152, 219, 1)',
                    borderWidth: 2,
                }]
            },
            options: {
                scale: {
                    ticks: {
                        beginAtZero: true
                    }
                }
            }
        });
    </script>
</body>
</html>
