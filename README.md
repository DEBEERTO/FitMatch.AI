<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FitMatch AI - AI-Powered Job Matching</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            color: white;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?technology,job') no-repeat center center/cover;
            height: 400px;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.5rem;
        }
        section {
            padding: 20px;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .feature {
            flex: 1 1 300px;
            margin: 10px;
            padding: 20px;
            background: #f9f9f9;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .cta {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            .hero p {
                font-size: 1rem;
            }
            .features {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>FitMatch AI</h1>
        <p>Your Future, Your Fit</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#features">Features</a>
        <a href="#how-it-works">How It Works</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h1>Find Jobs That Truly Fit You</h1>
        <p>Matching job seekers and employers based on skills and personality compatibility.</p>
        <a href="#signup" style="padding: 10px 20px; background: #4CAF50; color: white; text-decoration: none; border-radius: 5px;">Get Started</a>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>At FitMatch AI, we believe that finding the right job is more than just matching skills to job descriptions. Our platform uses advanced AI and psychometric tools to connect job seekers with employers who share their values and work styles.</p>
    </section>
    <section id="features" class="features">
        <div class="feature">
            <h3>AI-Driven Matches</h3>
            <p>Our algorithms combine skills, experiences, and personality traits for precise matches.</p>
        </div>
        <div class="feature">
            <h3>Personality Assessments</h3>
            <p>Job seekers take psychometric tests to uncover the roles where they will thrive.</p>
        </div>
        <div class="feature">
            <h3>Employer Dashboards</h3>
            <p>Employers get real-time insights into team compatibility and candidate fit.</p>
        </div>
        <div class="feature">
            <h3>Mobile Accessibility</h3>
            <p>Search for jobs and hire talent anywhere with our mobile-friendly platform.</p>
        </div>
    </section>
    <section id="how-it-works">
        <h2>How It Works</h2>
        <ol>
            <li>Sign up and create a profile.</li>
            <li>Take a quick personality and skill assessment.</li>
            <li>Get matched with jobs or candidates tailored to your needs.</li>
            <li>Communicate and schedule interviews directly on the platform.</li>
        </ol>
    </section>
    <div class="cta">
        <h2>Ready to Find Your Fit?</h2>
        <p>Join thousands of professionals and businesses transforming their hiring process.</p>
        <a href="#signup" style="padding: 10px 20px; background: white; color: #4CAF50; text-decoration: none; border-radius: 5px;">Sign Up Now</a>
    </div>
    <footer>
        <p>© 2024 FitMatch AI | All Rights Reserved</p>
    </footer>
</body>
</html>
