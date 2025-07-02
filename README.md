<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Top 100+ Websites to Learn to Code for Free</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #4361ee;
            --secondary: #3a0ca3;
            --accent: #4cc9f0;
            --dark: #14213d;
            --light: #f8f9fa;
            --gray: #6c757d;
            --success: #2ec4b6;
            --warning: #ff9f1c;
            --border-radius: 10px;
            --shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s ease;
        }

        body {
            background-color: #f0f2f5;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 1rem 0;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo i {
            color: var(--accent);
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 1.5rem;
        }

        nav a {
            color: rgba(255, 255, 255, 0.9);
            text-decoration: none;
            font-weight: 500;
            transition: var(--transition);
            padding: 5px 10px;
            border-radius: 5px;
        }

        nav a:hover {
            color: white;
            background: rgba(255, 255, 255, 0.1);
        }

        /* Article Header */
        .article-header {
            background: white;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            padding: 3rem;
            margin: 2rem auto;
            max-width: 900px;
            text-align: center;
        }

        .article-header h1 {
            font-size: 2.8rem;
            margin-bottom: 1.5rem;
            color: var(--dark);
            line-height: 1.2;
        }

        .meta {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 1.5rem;
            margin-bottom: 1.5rem;
            color: var(--gray);
            font-size: 0.95rem;
        }

        .author {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .author-img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .divider {
            width: 4px;
            height: 4px;
            border-radius: 50%;
            background: var(--gray);
        }

        .excerpt {
            font-size: 1.2rem;
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto 2rem;
            line-height: 1.7;
        }

        /* Main Content */
        .content-container {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 2rem;
            margin: 3rem auto;
        }

        .article-content {
            background: white;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            padding: 3rem;
        }

        .toc {
            background: white;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            padding: 1.5rem;
            align-self: start;
            position: sticky;
            top: 100px;
        }

        .toc h3 {
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent);
            color: var(--dark);
        }

        .toc ul {
            list-style: none;
        }

        .toc li {
            margin-bottom: 0.8rem;
        }

        .toc a {
            color: var(--gray);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .toc a:hover {
            color: var(--primary);
        }

        .toc a i {
            color: var(--accent);
            font-size: 0.8rem;
        }

        .section {
            margin-bottom: 3rem;
        }

        .section h2 {
            color: var(--primary);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #e9ecef;
            font-size: 1.8rem;
        }

        .websites-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .website-card {
            background: #f8f9fa;
            border-radius: var(--border-radius);
            padding: 1.5rem;
            transition: var(--transition);
            border: 1px solid #e9ecef;
        }

        .website-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow);
            border-color: var(--accent);
        }

        .website-card h3 {
            color: var(--dark);
            margin-bottom: 0.8rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .website-card h3 i {
            color: var(--accent);
        }

        .website-card p {
            color: var(--gray);
            margin-bottom: 1.2rem;
            font-size: 0.95rem;
        }

        .website-card a {
            display: inline-block;
            background: var(--primary);
            color: white;
            text-decoration: none;
            padding: 0.5rem 1.2rem;
            border-radius: 5px;
            font-weight: 500;
            transition: var(--transition);
        }

        .website-card a:hover {
            background: var(--secondary);
        }

        /* Call to Action */
        .cta {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: var(--border-radius);
            padding: 3rem;
            text-align: center;
            margin: 3rem auto;
            max-width: 900px;
        }

        .cta h2 {
            font-size: 2.2rem;
            margin-bottom: 1rem;
        }

        .cta p {
            max-width: 700px;
            margin: 0 auto 2rem;
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            background: white;
            color: var(--primary);
            text-decoration: none;
            padding: 1rem 2.5rem;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.1rem;
            transition: var(--transition);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 20px rgba(0, 0, 0, 0.2);
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 3rem 0;
            margin-top: 4rem;
        }

        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .footer-col h3 {
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }

        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background: var(--accent);
        }

        .footer-col ul {
            list-style: none;
        }

        .footer-col ul li {
            margin-bottom: 0.8rem;
        }

        .footer-col ul li a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .footer-col ul li a:hover {
            color: white;
            transform: translateX(5px);
        }

        .copyright {
            text-align: center;
            padding-top: 2rem;
            margin-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.6);
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 900px) {
            .content-container {
                grid-template-columns: 1fr;
            }
            
            .toc {
                position: static;
            }
            
            nav ul {
                display: none;
            }
        }

        @media (max-width: 768px) {
            .article-header {
                padding: 2rem;
            }
            
            .article-header h1 {
                font-size: 2.2rem;
            }
            
            .article-content {
                padding: 2rem;
            }
            
            .meta {
                flex-direction: column;
                gap: 0.5rem;
            }
        }

        @media (max-width: 480px) {
            .website-card {
                padding: 1.2rem;
            }
            
            .cta {
                padding: 2rem;
            }
            
            .cta h2 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <i class="fas fa-laptop-code"></i>
                <span>CodeMaster</span>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Tutorials</a></li>
                    <li><a href="#">Resources</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">About</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <!-- Article Header -->
    <div class="container">
        <div class="article-header">
            <h1>Top 100+ Websites to Learn to Code for Free</h1>
            <div class="meta">
                <div class="author">
                    <div class="author-img">TT</div>
                    <span>Tashia T.</span>
                </div>
                <div class="divider"></div>
                <div class="date">Jan 07, 2025</div>
                <div class="divider"></div>
                <div class="read-time">28min Read</div>
            </div>
            <p class="excerpt">
                As COVID-19 has boosted the growth of the global eCommerce and tech industries, 
                more and more people are learning to code to find or switch to tech jobs. 
                To do so, many rely on online learning resources, as there are fewer in-person coding bootcamps and workshops.
            </p>
        </div>
    </div>
    
    <!-- Main Content -->
    <div class="container content-container">
        <div class="article-content">
            <div class="section">
                <p>
                    However, some online coding classes may cost hundreds or even thousands of dollars. 
                    To address this concern, we have compiled an extensive list of coding websites for learning to code for free.
                </p>
                <p>
                    If you want to learn coding at zero cost or consider various options before committing to a premium course, 
                    this article may be right for you. We will provide 110 websites to learn programming for free, 
                    breaking down the list into several sections according to coding topics.
                </p>
                <p>
                    Without further ado, let's begin.
                </p>
            </div>
            
            <!-- Top 15 Websites Section -->
            <div class="section">
                <h2><i class="fas fa-star"></i> 15 Websites to Learn to Code For Free in 2025</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-free-code-camp"></i> freeCodeCamp</h3>
                        <p>Learn to code with free online courses, programming projects, and interview preparation.</p>
                        <a href="https://www.freecodecamp.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> Codecademy</h3>
                        <p>Interactive learning platform with courses in 12 programming languages.</p>
                        <a href="https://www.codecademy.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fab fa-khan-academy"></i> Khan Academy</h3>
                        <p>Non-profit educational organization with programming and computer science courses.</p>
                        <a href="https://www.khanacademy.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-university"></i> edX</h3>
                        <p>Massive open online course provider with university-level programming courses.</p>
                        <a href="https://www.edx.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-globe"></i> W3Schools</h3>
                        <p>Web development tutorials and references for HTML, CSS, JavaScript and more.</p>
                        <a href="https://www.w3schools.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fab fa-github"></i> GitHub Education</h3>
                        <p>Free access to developer tools and resources for students and teachers.</p>
                        <a href="https://education.github.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code-branch"></i> The Odin Project</h3>
                        <p>Full-stack curriculum with a focus on Ruby on Rails and JavaScript.</p>
                        <a href="https://www.theodinproject.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-laptop"></i> Udacity</h3>
                        <p>Free programming courses with a focus on cutting-edge technologies.</p>
                        <a href="https://www.udacity.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> SoloLearn</h3>
                        <p>Mobile-first platform with bite-sized coding lessons and a vibrant community.</p>
                        <a href="https://www.sololearn.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-network-wired"></i> MDN Web Docs</h3>
                        <p>Comprehensive resource for web developers by Mozilla.</p>
                        <a href="https://developer.mozilla.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-graduation-cap"></i> Harvard CS50</h3>
                        <p>Harvard's introduction to computer science course, available for free.</p>
                        <a href="https://cs50.harvard.edu/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-fire"></i> Code.org</h3>
                        <p>Non-profit dedicated to expanding access to computer science in schools.</p>
                        <a href="https://code.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-cubes"></i> freeCodeCamp YouTube</h3>
                        <p>Thousands of hours of free programming tutorials on YouTube.</p>
                        <a href="https://www.youtube.com/c/Freecodecamp" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-terminal"></i> Exercism</h3>
                        <p>Code practice and mentorship with exercises in 50+ languages.</p>
                        <a href="https://exercism.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-project-diagram"></i> Scrimba</h3>
                        <p>Interactive coding screencasts where you can edit the code.</p>
                        <a href="https://scrimba.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Online Courses Section -->
            <div class="section">
                <h2><i class="fas fa-graduation-cap"></i> Best Online Courses to Learn to Code for Free in 2025</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-google"></i> Google Developers</h3>
                        <p>Resources and tutorials for web technologies and Google developer products.</p>
                        <a href="https://developers.google.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-server"></i> MIT OpenCourseWare</h3>
                        <p>Free course materials from MIT's computer science curriculum.</p>
                        <a href="https://ocw.mit.edu/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-laptop-code"></i> Coursera</h3>
                        <p>Access free courses from top universities and companies worldwide.</p>
                        <a href="https://www.coursera.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-chalkboard-teacher"></i> Stanford Online</h3>
                        <p>Free computer science courses from Stanford University.</p>
                        <a href="https://online.stanford.edu/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-atom"></i> CS Dojo</h3>
                        <p>YouTube channel with beginner-friendly programming tutorials.</p>
                        <a href="https://www.youtube.com/c/CSDojo" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-database"></i> Kaggle Learn</h3>
                        <p>Free micro-courses on data science and machine learning.</p>
                        <a href="https://www.kaggle.com/learn" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-robot"></i> Fast.ai</h3>
                        <p>Practical deep learning courses for coders with free Jupyter notebooks.</p>
                        <a href="https://www.fast.ai/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-chart-line"></i> Udemy Free Courses</h3>
                        <p>Selection of free programming courses on the Udemy platform.</p>
                        <a href="https://www.udemy.com/courses/free/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-mobile-alt"></i> Android Developers</h3>
                        <p>Official Android development courses and documentation.</p>
                        <a href="https://developer.android.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fab fa-apple"></i> Apple Developer</h3>
                        <p>Resources for learning Swift and iOS/macOS development.</p>
                        <a href="https://developer.apple.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- WordPress Section -->
            <div class="section">
                <h2><i class="fab fa-wordpress"></i> Learn How to Code With WordPress Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-wordpress-simple"></i> WordPress.tv</h3>
                        <p>Official WordPress video resource with tutorials and conference talks.</p>
                        <a href="https://wordpress.tv/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> WPBeginner</h3>
                        <p>Beginner-friendly WordPress tutorials, guides, and resources.</p>
                        <a href="https://www.wpbeginner.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-wrench"></i> WordPress Codex</h3>
                        <p>Official documentation for WordPress developers.</p>
                        <a href="https://codex.wordpress.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-graduation-cap"></i> WP Apprentice</h3>
                        <p>Video tutorials for WordPress beginners.</p>
                        <a href="https://wpapprentice.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> WordPress Developer Resources</h3>
                        <p>Official developer handbook and coding standards.</p>
                        <a href="https://developer.wordpress.org/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- HTML/CSS Section -->
            <div class="section">
                <h2><i class="fab fa-html5"></i> Learn to Code With HTML and CSS Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-css3-alt"></i> CSS-Tricks</h3>
                        <p>Daily articles about CSS, HTML, JavaScript, and web design.</p>
                        <a href="https://css-tricks.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-paint-brush"></i> Frontend Masters</h3>
                        <p>In-depth courses on frontend development technologies.</p>
                        <a href="https://frontendmasters.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-palette"></i> Smashing Magazine</h3>
                        <p>Articles and tutorials on web design and development.</p>
                        <a href="https://www.smashingmagazine.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-laptop-code"></i> Jen Simmons' Lab</h3>
                        <p>CSS Grid and modern layout tutorials by Mozilla designer.</p>
                        <a href="https://labs.jensimmons.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-magic"></i> CSS Grid Garden</h3>
                        <p>Interactive game for learning CSS Grid layout.</p>
                        <a href="https://cssgridgarden.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-carrot"></i> Flexbox Froggy</h3>
                        <p>Game for learning CSS Flexbox properties.</p>
                        <a href="https://flexboxfroggy.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-flag"></i> CSS Battle</h3>
                        <p>Online CSS code-golfing game to test your skills.</p>
                        <a href="https://cssbattle.dev/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-vector-square"></i> Codrops CSS Reference</h3>
                        <p>Comprehensive CSS properties reference with examples.</p>
                        <a href="https://tympanus.net/codrops/css_reference/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- JavaScript Section -->
            <div class="section">
                <h2><i class="fab fa-js"></i> Learn to Code With JavaScript Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-node-js"></i> NodeSchool</h3>
                        <p>Open source workshops that teach web software skills.</p>
                        <a href="https://nodeschool.io/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book-open"></i> Eloquent JavaScript</h3>
                        <p>Free online book with exercises to learn JavaScript programming.</p>
                        <a href="https://eloquentjavascript.net/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-gamepad"></i> JavaScript30</h3>
                        <p>30 day vanilla JS coding challenge by Wes Bos.</p>
                        <a href="https://javascript30.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> You Don't Know JS</h3>
                        <p>Book series diving deep into JavaScript core mechanisms.</p>
                        <a href="https://github.com/getify/You-Dont-Know-JS" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-bug"></i> JavaScript.info</h3>
                        <p>Modern JavaScript tutorial from the basics to advanced topics.</p>
                        <a href="https://javascript.info/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-meteor"></i> Three.js Journey</h3>
                        <p>Free introduction to 3D graphics with JavaScript.</p>
                        <a href="https://threejs-journey.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-chart-bar"></i> D3.js Tutorials</h3>
                        <p>Learn data visualization with JavaScript's D3 library.</p>
                        <a href="https://www.d3indepth.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-mobile-alt"></i> React Documentation</h3>
                        <p>Official React learning resources and tutorials.</p>
                        <a href="https://reactjs.org/docs/getting-started.html" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Python Section -->
            <div class="section">
                <h2><i class="fab fa-python"></i> Learn to Code With Python Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> Real Python</h3>
                        <p>Tutorials, articles, and resources for Python developers.</p>
                        <a href="https://realpython.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-flask"></i> Full Stack Python</h3>
                        <p>Explanation of Python concepts from beginner to advanced.</p>
                        <a href="https://www.fullstackpython.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-snake"></i> Python.org Tutorial</h3>
                        <p>Official Python documentation and beginner's guide.</p>
                        <a href="https://docs.python.org/3/tutorial/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-brain"></i> Automate the Boring Stuff</h3>
                        <p>Practical Python programming book with free online version.</p>
                        <a href="https://automatetheboringstuff.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-database"></i> Python for Data Science</h3>
                        <p>Free curriculum for learning Python data analysis.</p>
                        <a href="https://www.datacamp.com/learn/python" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-robot"></i> Python Like You Mean It</h3>
                        <p>Quality Python tutorials with a focus on best practices.</p>
                        <a href="https://www.pythonlikeyoumeanit.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-chart-line"></i> Py4e</h3>
                        <p>Python for Everybody - beginner-friendly course by Dr. Chuck.</p>
                        <a href="https://www.py4e.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Java Section -->
            <div class="section">
                <h2><i class="fab fa-java"></i> Learn to Code With Java Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-coffee"></i> Java Tutorial for Beginners</h3>
                        <p>Comprehensive Java tutorial for absolute beginners.</p>
                        <a href="https://www.javatpoint.com/java-tutorial" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> Java Programming MOOC</h3>
                        <p>University of Helsinki's free massive open online course.</p>
                        <a href="https://java-programming.mooc.fi/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> Java Code Geeks</h3>
                        <p>Tutorials, examples, and articles for Java developers.</p>
                        <a href="https://www.javacodegeeks.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-graduation-cap"></i> Oracle Java Tutorials</h3>
                        <p>Official Java tutorials from Oracle.</p>
                        <a href="https://docs.oracle.com/javase/tutorial/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- C# Section -->
            <div class="section">
                <h2><i class="fas fa-code"></i> Learn to Code With C# Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-microsoft"></i> Microsoft Learn C#</h3>
                        <p>Official Microsoft C# learning path.</p>
                        <a href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> C# Station Tutorial</h3>
                        <p>Beginner-friendly C# tutorials and examples.</p>
                        <a href="https://www.csharp-station.com/Tutorial.aspx" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-gamepad"></i> Unity Learn</h3>
                        <p>Learn C# through game development with Unity.</p>
                        <a href="https://learn.unity.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- C++ Section -->
            <div class="section">
                <h2><i class="fas fa-file-code"></i> Learn to Code With C++ Online</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> Learn C++</h3>
                        <p>Modern C++ tutorial for complete beginners.</p>
                        <a href="https://www.learncpp.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> CPlusPlus.com</h3>
                        <p>Comprehensive C++ reference and tutorials.</p>
                        <a href="https://www.cplusplus.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-university"></i> Google C++ Course</h3>
                        <p>Google's free C++ class for beginners.</p>
                        <a href="https://developers.google.com/edu/c++/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Command Line Section -->
            <div class="section">
                <h2><i class="fas fa-terminal"></i> Learn Command Line Basics</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-window-maximize"></i> Command Line Crash Course</h3>
                        <p>Learn enough command line to be dangerous.</p>
                        <a href="https://learncodethehardway.org/unix/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-gamepad"></i> OverTheWire Bandit</h3>
                        <p>Game-like introduction to Linux command line.</p>
                        <a href="https://overthewire.org/wargames/bandit/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-laptop-code"></i> Linux Journey</h3>
                        <p>Learn Linux command line through interactive lessons.</p>
                        <a href="https://linuxjourney.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Git/GitHub Section -->
            <div class="section">
                <h2><i class="fab fa-git-alt"></i> Learn Git and GitHub</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-github"></i> GitHub Guides</h3>
                        <p>Official GitHub tutorials and guides.</p>
                        <a href="https://guides.github.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-book"></i> Learn Git Branching</h3>
                        <p>Interactive visual Git tutorial.</p>
                        <a href="https://learngitbranching.js.org/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code-branch"></i> Git Immersion</h3>
                        <p>Guided tour that walks through Git fundamentals.</p>
                        <a href="https://gitimmersion.com/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- UI/UX Design Section -->
            <div class="section">
                <h2><i class="fas fa-paint-brush"></i> Learn UI/UX Design</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-mobile-alt"></i> UX Design Institute</h3>
                        <p>Free UX design courses and resources.</p>
                        <a href="https://www.uxdesigninstitute.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-pencil-ruler"></i> Figma Learn</h3>
                        <p>Official Figma tutorials for UI/UX design.</p>
                        <a href="https://www.figma.com/resources/learn-design/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-palette"></i> Adobe XD Tutorials</h3>
                        <p>Learn UI/UX design with Adobe XD.</p>
                        <a href="https://helpx.adobe.com/xd/tutorials.html" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- DevOps Section -->
            <div class="section">
                <h2><i class="fas fa-server"></i> Learn DevOps</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-docker"></i> Docker Get Started</h3>
                        <p>Official Docker tutorials and documentation.</p>
                        <a href="https://docs.docker.com/get-started/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fab fa-aws"></i> AWS Training</h3>
                        <p>Free cloud computing courses from Amazon.</p>
                        <a href="https://aws.amazon.com/training/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-terminal"></i> Kubernetes Basics</h3>
                        <p>Official Kubernetes interactive tutorials.</p>
                        <a href="https://kubernetes.io/docs/tutorials/kubernetes-basics/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- QA Testing Section -->
            <div class="section">
                <h2><i class="fas fa-bug"></i> Learn QA Testing</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-vial"></i> Test Automation University</h3>
                        <p>Free test automation courses.</p>
                        <a href="https://testautomationu.applitools.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-check-circle"></i> Guru99</h3>
                        <p>Software testing tutorials for beginners.</p>
                        <a href="https://www.guru99.com/software-testing.html" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> Selenium WebDriver</h3>
                        <p>Official Selenium documentation and tutorials.</p>
                        <a href="https://www.selenium.dev/documentation/webdriver/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Mobile Development Section -->
            <div class="section">
                <h2><i class="fas fa-mobile-alt"></i> Learn Mobile App Development</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fab fa-android"></i> Android Basics</h3>
                        <p>Google's free course on Android development.</p>
                        <a href="https://developer.android.com/courses/android-basics-kotlin/course" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fab fa-apple"></i> Swift Playgrounds</h3>
                        <p>Apple's interactive way to learn Swift programming.</p>
                        <a href="https://www.apple.com/swift/playgrounds/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-code"></i> Flutter Docs</h3>
                        <p>Official Flutter documentation and tutorials.</p>
                        <a href="https://flutter.dev/docs" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- AI Section -->
            <div class="section">
                <h2><i class="fas fa-brain"></i> Learn Artificial Intelligence</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-robot"></i> Google AI</h3>
                        <p>Machine learning crash course from Google.</p>
                        <a href="https://ai.google/education/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-chart-line"></i> Fast.ai</h3>
                        <p>Practical deep learning for coders.</p>
                        <a href="https://course.fast.ai/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-university"></i> Stanford Machine Learning</h3>
                        <p>Andrew Ng's famous ML course.</p>
                        <a href="https://www.coursera.org/learn/machine-learning" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- Game Development Section -->
            <div class="section">
                <h2><i class="fas fa-gamepad"></i> Learn Game Development</h2>
                <div class="websites-grid">
                    <div class="website-card">
                        <h3><i class="fas fa-dice"></i> Unity Learn</h3>
                        <p>Official Unity tutorials and courses.</p>
                        <a href="https://learn.unity.com/" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-ghost"></i> Unreal Engine</h3>
                        <p>Official Unreal Engine learning resources.</p>
                        <a href="https://www.unrealengine.com/en-US/learn" target="_blank">Visit Website</a>
                    </div>
                    <div class="website-card">
                        <h3><i class="fas fa-laptop-code"></i> Godot Docs</h3>
                        <p>Official Godot Engine documentation.</p>
                        <a href="https://docs.godotengine.org/en/stable/" target="_blank">Visit Website</a>
                    </div>
                </div>
            </div>
            
            <!-- FAQ Section -->
            <div class="section">
                <h2><i class="fas fa-question-circle"></i> Learn to Code FAQ</h2>
                <div class="faq-item">
                    <h3>How do I choose which programming language to learn first?</h3>
                    <p>It depends on your goals. For web development, start with HTML/CSS then JavaScript. For data science, Python is ideal. For mobile apps, consider Swift (iOS) or Kotlin (Android). JavaScript and Python are generally the most beginner-friendly.</p>
                </div>
                <div class="faq-item">
                    <h3>How long does it take to learn to code?</h3>
                    <p>Basic proficiency can take 3-6 months of consistent study. Becoming job-ready typically takes 6-12 months. Remember that learning to code is a continuous journey - even experienced developers keep learning new technologies.</p>
                </div>
                <div class="faq-item">
                    <h3>Can I get a job just by learning from free resources?</h3>
                    <p>Absolutely! Many developers are self-taught using free resources. What matters most is your skill level and portfolio. Contribute to open source, build projects, and network to increase your chances.</p>
                </div>
            </div>
            
            <!-- Call to Action Section -->
            <div class="cta">
                <h2>Ready to Start Your Coding Journey?</h2>
                <p>Join over 2 million developers who have accelerated their careers with our free resources and community support.</p>
                <a href="#" class="btn">Get Started for Free</a>
            </div>
        </div>
        
        <!-- Table of Contents -->
        <div class="toc">
            <h3>Table of Contents</h3>
            <ul>
                <li><a href="#top-websites"><i class="fas fa-chevron-right"></i> 15 Websites to Learn to Code For Free</a></li>
                <li><a href="#online-courses"><i class="fas fa-chevron-right"></i> Best Online Courses</a></li>
                <li><a href="#wordpress"><i class="fas fa-chevron-right"></i> Learn WordPress</a></li>
                <li><a href="#html-css"><i class="fas fa-chevron-right"></i> HTML and CSS</a></li>
                <li><a href="#javascript"><i class="fas fa-chevron-right"></i> JavaScript</a></li>
                <li><a href="#python"><i class="fas fa-chevron-right"></i> Python</a></li>
                <li><a href="#java"><i class="fas fa-chevron-right"></i> Java</a></li>
                <li><a href="#csharp"><i class="fas fa-chevron-right"></i> C#</a></li>
                <li><a href="#cpp"><i class="fas fa-chevron-right"></i> C++</a></li>
                <li><a href="#command-line"><i class="fas fa-chevron-right"></i> Command Line</a></li>
                <li><a href="#git"><i class="fas fa-chevron-right"></i> Git and GitHub</a></li>
                <li><a href="#ui-ux"><i class="fas fa-chevron-right"></i> UI/UX Design</a></li>
                <li><a href="#devops"><i class="fas fa-chevron-right"></i> DevOps</a></li>
                <li><a href="#qa"><i class="fas fa-chevron-right"></i> QA Testing</a></li>
                <li><a href="#mobile"><i class="fas fa-chevron-right"></i> Mobile App Development</a></li>
                <li><a href="#ai"><i class="fas fa-chevron-right"></i> Artificial Intelligence</a></li>
                <li><a href="#game-dev"><i class="fas fa-chevron-right"></i> Game Development</a></li>
                <li><a href="#faq"><i class="fas fa-chevron-right"></i> Learn to Code FAQ</a></li>
            </ul>
        </div>
    </div>
    
    <!-- Footer -->
    <footer>
        <div class="container footer-container">
            <div class="footer-col">
                <h3>CodeMaster</h3>
                <p>Your ultimate resource for learning to code, with thousands of free tutorials and resources.</p>
            </div>
            <div class="footer-col">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Home</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Tutorials</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Resources</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Blog</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h3>Learning Paths</h3>
                <ul>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Web Development</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Data Science</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Mobile Development</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Game Development</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h3>Connect</h3>
                <ul>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Twitter</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> GitHub</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> Discord</a></li>
                    <li><a href="#"><i class="fas fa-chevron-right"></i> YouTube</a></li>
                </ul>
            </div>
        </div>
        <div class="container">
            <div class="copyright">
                &copy; 2025 CodeMaster. All rights reserved. | Designed for developers, by developers.
            </div>
        </div>
    </footer>
    
    <script>
        // Table of Contents smooth scrolling
        document.querySelectorAll('.toc a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if(targetId !== '#') {
                    document.querySelector(targetId).scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Website card animation
        const cards = document.querySelectorAll('.website-card');
        cards.forEach(card => {
            card.addEventListener('mouseenter', () => {
                card.style.transform = 'translateY(-5px)';
                card.style.boxShadow = '0 10px 30px rgba(0, 0, 0, 0.15)';
                card.style.borderColor = 'var(--accent)';
            });
            
            card.addEventListener('mouseleave', () => {
                card.style.transform = 'translateY(0)';
                card.style.boxShadow = 'none';
                card.style.borderColor = '#e9ecef';
            });
        });
    </script>
</body>
</html>![Screenshot 2024-11-17 212642](https://github.com/user-attachments/assets/365454f7-078f-4b95-a566-332d16995d46)
[Ahmad-code-tutor--main.zip](https://github.com/user-attachments/files/21009242/Ahmad-code-tutor--main.zip)
![518b09d5-14a6-4ed4-9c5a-5bfabddbae8e](https://github.com/user-attachments/assets/fe88433b-5efb-4f4e-ad21-007a50b2c0b2)
