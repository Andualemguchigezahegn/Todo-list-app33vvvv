<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Andualem Guchi · Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,100..900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            overflow-x: hidden;
        }

        body {
            background: #f7f3ee;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            padding: 1.5rem;
            color: #1e1a16;
            display: flex;
            justify-content: center;
            min-height: 100vh;
            line-height: 1.6;
            overflow-x: hidden;
            width: 100%;
        }

        .portfolio-wrapper {
            max-width: 1200px;
            width: 100%;
            min-width: 0;
        }

        .main-card {
            background: #ffffff;
            border-radius: 2.5rem;
            padding: 2.8rem 3.2rem;
            box-shadow: 0 30px 60px -20px rgba(30, 26, 22, 0.15);
            width: 100%;
            min-width: 0;
            overflow: hidden;
        }

        @media (max-width: 768px) {
            .main-card {
                padding: 1.5rem 1.2rem;
                border-radius: 1.8rem;
            }
            body {
                padding: 0.8rem;
            }
        }

        @media (max-width: 480px) {
            .main-card {
                padding: 1rem 0.8rem;
                border-radius: 1.2rem;
            }
            body {
                padding: 0.5rem;
            }
        }

        /* ===== TOP BAR ===== */
        .top-bar {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            gap: 0.8rem;
            width: 100%;
        }

        .brand h1 {
            font-size: 1.8rem;
            font-weight: 700;
            color: #1e1a16;
            word-break: break-word;
        }
        .brand h1 i {
            color: #c47b4d;
            margin-right: 0.3rem;
        }
        .brand .sub {
            font-size: 0.95rem;
            color: #5a4d40;
            word-break: break-word;
        }

        .status-badge {
            background: #e8ddd0;
            padding: 0.3rem 1.2rem;
            border-radius: 40px;
            color: #4a3525;
            font-weight: 600;
            font-size: 0.8rem;
            border: 1px solid #d4c4b4;
            display: inline-flex;
            align-items: center;
            gap: 0.4rem;
            flex-shrink: 0;
        }
        .status-badge i {
            font-size: 0.5rem;
            color: #2b7a4b;
        }

        /* ===== HERO ===== */
        .hero {
            background: #faf6f1;
            border-radius: 2rem;
            padding: 2rem 2rem;
            margin-bottom: 2.5rem;
            border: 1px solid #e5dbd1;
            text-align: center;
            width: 100%;
            overflow: hidden;
        }
        .hero h2 {
            font-size: 1.8rem;
            font-weight: 700;
            color: #1e1a16;
            word-break: break-word;
        }
        .hero h2 i {
            color: #c47b4d;
            margin-right: 0.3rem;
        }
        .hero p {
            font-size: 1rem;
            color: #4a3f35;
            max-width: 650px;
            margin: 0.5rem auto 0;
            word-break: break-word;
        }
        .hero .location {
            font-size: 0.9rem;
            color: #6b5d4e;
            margin-top: 0.4rem;
            word-break: break-word;
        }
        .hero .location i {
            color: #c47b4d;
            width: 1.4rem;
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 0.6rem 1rem;
            margin-top: 1.2rem;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 0.4rem;
            padding: 0.5rem 1.4rem;
            border-radius: 60px;
            font-weight: 600;
            font-size: 0.85rem;
            text-decoration: none;
            transition: 0.15s;
            border: none;
            cursor: pointer;
            white-space: nowrap;
        }
        @media (max-width: 480px) {
            .btn {
                font-size: 0.75rem;
                padding: 0.4rem 1rem;
            }
        }
        .btn-primary {
            background: #1e1a16;
            color: white;
        }
        .btn-primary:hover {
            background: #3d3228;
            transform: translateY(-2px);
        }
        .btn-outline {
            background: transparent;
            color: #1e1a16;
            border: 1.5px solid #d4c4b4;
        }
        .btn-outline:hover {
            background: #f1ece6;
        }
        .btn-cta {
            background: #c47b4d;
            color: white;
        }
        .btn-cta:hover {
            background: #a8663d;
            transform: translateY(-2px);
        }

        /* ===== SECTION TITLES ===== */
        .section-title {
            font-size: 1.4rem;
            font-weight: 700;
            margin: 2rem 0 1rem 0;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            border-bottom: 2px solid #ece3da;
            padding-bottom: 0.5rem;
            color: #1e1a16;
            flex-wrap: wrap;
        }
        .section-title i {
            color: #c47b4d;
            font-size: 1.3rem;
        }

        /* ===== GRID ===== */
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.2rem;
            width: 100%;
        }
        @media (max-width: 650px) {
            .grid-2col {
                grid-template-columns: 1fr;
                gap: 1rem;
            }
        }

        .expertise-card {
            background: #faf6f1;
            padding: 1rem 1.2rem;
            border-radius: 20px;
            border: 1px solid #e5dbd1;
            transition: 0.2s;
            width: 100%;
            overflow: hidden;
        }
        .expertise-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 28px rgba(30, 26, 22, 0.06);
            border-color: #c47b4d;
        }
        .expertise-card h3 {
            font-size: 1rem;
            margin-bottom: 0.2rem;
            display: flex;
            align-items: center;
            gap: 0.3rem;
            word-break: break-word;
        }
        .expertise-card h3 i {
            color: #c47b4d;
            width: 1.4rem;
            flex-shrink: 0;
        }
        .expertise-card p {
            color: #4a3f35;
            font-size: 0.9rem;
            word-break: break-word;
        }

        /* ===== PROJECT CARDS ===== */
        .project-card {
            background: #faf6f1;
            border-radius: 20px;
            padding: 1.2rem 1.5rem;
            border: 1px solid #e5dbd1;
            margin-bottom: 1.2rem;
            transition: 0.2s;
            width: 100%;
            overflow: hidden;
        }
        .project-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 28px rgba(30, 26, 22, 0.06);
            border-color: #c47b4d;
        }
        .project-card h3 {
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            color: #1e1a16;
            word-break: break-word;
        }
        .project-card h3 i {
            color: #c47b4d;
            flex-shrink: 0;
        }
        .project-card .label {
            font-weight: 600;
            color: #c47b4d;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            margin-top: 0.4rem;
        }
        .project-card ul {
            padding-left: 1.2rem;
            list-style-type: '▹ ';
            color: #4a3f35;
            margin-top: 0.2rem;
        }
        .project-card ul li {
            padding-left: 0.3rem;
            margin-bottom: 0.15rem;
            word-break: break-word;
        }
        .project-card p {
            color: #4a3f35;
            word-break: break-word;
        }

        /* ===== CERTIFICATES ===== */
        .cert-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1.2rem;
            margin: 0.8rem 0 0.3rem;
            width: 100%;
        }

        .cert-card {
            background: #faf6f1;
            border-radius: 20px;
            padding: 0.8rem 0.8rem 1rem;
            border: 1px solid #e5dbd1;
            text-align: center;
            transition: 0.2s;
            overflow: hidden;
        }
        .cert-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 28px rgba(30, 26, 22, 0.06);
            border-color: #c47b4d;
        }
        .cert-card img {
            width: 100%;
            height: auto;
            border-radius: 12px;
            border: 1px solid #dccfc2;
            background: white;
            max-height: 100px;
            object-fit: cover;
            margin-bottom: 0.4rem;
        }
        .cert-card .cert-name {
            font-weight: 600;
            font-size: 0.85rem;
            color: #1e1a16;
            word-break: break-word;
        }
        .cert-card .cert-issuer {
            font-size: 0.75rem;
            color: #5a4d40;
            word-break: break-word;
        }
        .cert-card .cert-id {
            font-size: 0.65rem;
            color: #8a7a68;
            background: #ece3da;
            padding: 0.05rem 0.6rem;
            border-radius: 30px;
            display: inline-block;
            margin-top: 0.2rem;
            word-break: break-word;
        }

        /* ===== CREDENTIALS PILLS ===== */
        .credential-pills {
            display: flex;
            flex-wrap: wrap;
            gap: 0.4rem 0.8rem;
            background: #faf6f1;
            padding: 0.8rem 1.2rem;
            border-radius: 40px;
            margin: 0.3rem 0 0.2rem;
            border: 1px solid #e5dbd1;
            width: 100%;
        }
        .credential-pills span {
            display: flex;
            align-items: center;
            gap: 0.3rem;
            font-size: 0.85rem;
            color: #1e1a16;
            word-break: break-word;
        }
        .credential-pills i {
            color: #c47b4d;
            width: 1rem;
            flex-shrink: 0;
        }

        /* ===== CONTACT ===== */
        .contact-section {
            background: #faf6f1;
            border-radius: 2rem;
            padding: 1.8rem 2rem;
            margin-top: 2rem;
            border: 1px solid #e5dbd1;
            width: 100%;
            overflow: hidden;
        }
        .contact-section h2 {
            font-size: 1.4rem;
            color: #1e1a16;
            word-break: break-word;
        }
        .contact-section h2 i {
            color: #c47b4d;
            margin-right: 0.4rem;
        }
        .contact-section > p {
            color: #4a3f35;
            margin-bottom: 1rem;
            word-break: break-word;
        }

        .social-row {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem 1.2rem;
            margin: 0.6rem 0 1rem;
        }
        .social-row a {
            display: inline-flex;
            align-items: center;
            gap: 0.4rem;
            background: white;
            padding: 0.25rem 1rem 0.25rem 0.6rem;
            border-radius: 60px;
            border: 1px solid #dccfc2;
            text-decoration: none;
            color: #1e1a16;
            font-weight: 500;
            font-size: 0.85rem;
            transition: 0.15s;
            word-break: break-word;
        }
        .social-row a i {
            color: #c47b4d;
            font-size: 1rem;
            flex-shrink: 0;
        }
        .social-row a:hover {
            background: #f1ece6;
            transform: translateY(-2px);
        }

        .contact-form {
            max-width: 500px;
            margin-top: 0.8rem;
            width: 100%;
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 0.6rem 1.2rem;
            border-radius: 40px;
            border: 1px solid #dccfc2;
            font-size: 0.95rem;
            margin-bottom: 0.6rem;
            font-family: inherit;
            background: white;
        }
        .contact-form input:focus,
        .contact-form textarea:focus {
            outline: none;
            border-color: #c47b4d;
            box-shadow: 0 0 0 3px rgba(196, 123, 77, 0.15);
        }
        .contact-form textarea {
            border-radius: 24px;
            resize: vertical;
            min-height: 90px;
        }
        .contact-form button {
            width: 100%;
            justify-content: center;
        }

        .signature-box {
            background: #ece3da;
            border-radius: 18px;
            padding: 1rem 1.5rem;
            margin-top: 1.2rem;
            border-left: 4px solid #c47b4d;
            font-size: 0.9rem;
            line-height: 1.6;
            color: #1e1a16;
            width: 100%;
            overflow: hidden;
            word-break: break-word;
        }
        .signature-box strong {
            color: #1e1a16;
        }
        .signature-box i {
            color: #c47b4d;
            width: 1.4rem;
            flex-shrink: 0;
        }
        .signature-box a {
            color: #c47b4d;
            text-decoration: none;
            word-break: break-all;
        }
        .signature-box a:hover {
            text-decoration: underline;
        }

        /* ===== FOOTER ===== */
        .footer-note {
            text-align: center;
            color: #8a7a68;
            font-size: 0.75rem;
            margin-top: 1.8rem;
            border-top: 1px solid #ece3da;
            padding-top: 1rem;
            width: 100%;
            word-break: break-word;
        }

        @media (max-width: 600px) {
            .hero {
                padding: 1.2rem 1rem;
            }
            .hero h2 {
                font-size: 1.3rem;
            }
            .section-title {
                font-size: 1.2rem;
            }
            .contact-section {
                padding: 1.2rem 1rem;
            }
            .credential-pills {
                border-radius: 28px;
                padding: 0.6rem 1rem;
                gap: 0.3rem 0.6rem;
            }
            .credential-pills span {
                font-size: 0.75rem;
            }
            .main-card {
                padding: 1rem 0.8rem;
            }
            .cert-grid {
                grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
                gap: 0.8rem;
            }
            .cert-card img {
                max-height: 80px;
            }
            .signature-box {
                font-size: 0.8rem;
                padding: 0.8rem 1rem;
            }
        }

        @media (max-width: 400px) {
            .top-bar {
                flex-direction: column;
                align-items: flex-start;
                gap: 0.5rem;
            }
            .brand h1 {
                font-size: 1.4rem;
            }
            .hero-actions {
                flex-direction: column;
                align-items: center;
            }
            .btn {
                white-space: normal;
                width: 100%;
                justify-content: center;
            }
            .social-row {
                flex-direction: column;
                align-items: stretch;
            }
            .social-row a {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
<div class="portfolio-wrapper">
    <div class="main-card">

        <!-- ===== TOP BAR ===== -->
        <div class="top-bar">
            <div class="brand">
                <h1><i class="fas fa-code"></i> Andualem Guchi</h1>
                <div class="sub">Digital Specialist · Developer · Creative</div>
            </div>
            <div class="status-badge">
                <i class="fas fa-circle"></i> open for work
            </div>
        </div>

        <!-- ===== HERO ===== -->
        <div class="hero">
            <h2><i class="fas fa-rocket"></i> Code · Design · Localize</h2>
            <p>From Python automation to mobile UI and bilingual content — helping businesses connect with Ethiopian and global audiences.</p>
            <div class="location">
                <i class="fas fa-map-pin"></i> Addis Ababa, Ethiopia · <i class="fas fa-globe"></i> Global reach
            </div>
            <div class="hero-actions">
                <a href="#" class="btn btn-primary" download><i class="fas fa-file-pdf"></i> Download CV</a>
                <a href="#contact" class="btn btn-cta"><i class="fas fa-paper-plane"></i> Hire me</a>
                <a href="https://t.me/Andualem_digital" target="_blank" class="btn btn-outline"><i class="fab fa-telegram"></i> Telegram</a>
            </div>
        </div>

        <!-- ===== CORE EXPERTISE ===== -->
        <h2 class="section-title"><i class="fas fa-th-large"></i> Core Expertise</h2>
        <div class="grid-2col">
            <div class="expertise-card">
                <h3><i class="fas fa-code"></i> Software Development</h3>
                <p>Python scripting, C++ logic design, data structures, automation.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-mobile-alt"></i> Mobile & UI Design</h3>
                <p>Responsive Android layouts, user flow mapping, visual asset design.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-video"></i> Creative Content</h3>
                <p>Video editing, social media assets, persuasive copywriting.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-globe"></i> Digital Operations</h3>
                <p>Cybersecurity, AI prompt literacy, translation & localization.</p>
            </div>
        </div>

        <!-- ===== PROJECTS ===== -->
        <h2 class="section-title"><i class="fas fa-folder-open"></i> Project Case Studies</h2>

        <div class="project-card">
            <h3><i class="fas fa-robot"></i> Automated Data Management & Scripts</h3>
            <div class="label">Objective</div>
            <p>Streamline repetitive corporate tasks and workflows using optimized code.</p>
            <div class="label">Execution</div>
            <ul>
                <li>Built custom Python automation scripts aligned with university structures.</li>
                <li>Automates bulk spreadsheet parsing, data sorting, and file management.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Drastically reduces manual data-entry errors and cuts processing time.</p>
        </div>

        <div class="project-card">
            <h3><i class="fas fa-paint-brush"></i> Mobile Interface Design & Assets</h3>
            <div class="label">Objective</div>
            <p>Craft clean, professional user experiences for digital products.</p>
            <div class="label">Execution</div>
            <ul>
                <li>High-fidelity mobile interfaces using Udacity's Android Fundamentals.</li>
                <li>Original vector icon sets optimized across screens.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Stunning, intuitive mockups ready for engineering deployment.</p>
        </div>

        <div class="project-card">
            <h3><i class="fas fa-pen-fancy"></i> Tech Copywriting, Video & Localization</h3>
            <div class="label">Objective</div>
            <p>Produce accessible digital guides and media to scale engagement.</p>
            <div class="label">Execution</div>
            <ul>
                <li>Authored tech explainers, localized copy, and short-form videos.</li>
                <li>Applied Meta's digital communication framework.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Drives consumer reach with high-converting, readable technical content.</p>
        </div>

        <!-- ===== CERTIFICATES ===== -->
        <h2 class="section-title"><i class="fas fa-certificate"></i> Certificates & Credentials</h2>
        <div class="cert-grid">
            <div class="cert-card">
                <img src="20260823_d0aae0.png" alt="Digital Literacy" />
                <div class="cert-name">Digital Literacy</div>
                <div class="cert-issuer">Zega Digital · OMNI</div>
                <div class="cert-id">ZEGA-958BYQ4B</div>
            </div>
            <div class="cert-card">
                <img src="20260823_df15e5.png" alt="Python Essentials" />
                <div class="cert-name">Python Programming</div>
                <div class="cert-issuer">HU · CS Dept.</div>
                <div class="cert-id">May 25–26, 2026</div>
            </div>
            <div class="cert-card">
                <img src="20260823_7c823c.png" alt="Android Fundamentals" />
                <div class="cert-name">Android Fundamentals</div>
                <div class="cert-issuer">Udacity</div>
                <div class="cert-id">job-ready</div>
            </div>
            <div class="cert-card">
                <img src="20260823_9a719e.png" alt="C++ for Beginners" />
                <div class="cert-name">C++ for Beginners</div>
                <div class="cert-issuer">Bishal Khadka</div>
                <div class="cert-id">completion</div>
            </div>
            <div class="cert-card">
                <img src="20260823_113459.png" alt="Additional Certificate" />
                <div class="cert-name">Additional Credential</div>
                <div class="cert-issuer">Verified</div>
                <div class="cert-id">2026</div>
            </div>
        </div>

        <!-- ===== ACADEMIC ===== -->
        <div class="credential-pills">
            <span><i class="fas fa-university"></i> B.Sc. Natural Science (ongoing) · Haramaya Univ. · CGPA 3.92 · GD</span>
            <span><i class="fas fa-file-alt"></i> Year I Sem I: A, A, A+, A-, A- · SGPA 3.91</span>
        </div>

        <!-- ===== CONTACT ===== -->
        <div class="contact-section" id="contact">
            <h2><i class="fas fa-paper-plane"></i> Work With Me</h2>
            <p>Have a project in mind? Let's connect directly.</p>

            <div class="social-row">
                <a href="https://t.me/Andualem_digital" target="_blank"><i class="fab fa-telegram"></i> @Andualem_digital</a>
                <a href="mailto:andualemandualem25@gmail.com"><i class="fas fa-envelope"></i> andualemandualem25</a>
                <a href="#" target="_blank"><i class="fab fa-upwork"></i> Upwork</a>
            </div>

            <form class="contact-form" action="https://formspreet.com" method="post">
                <input type="text" name="name" placeholder="Your name" required />
                <input type="email" name="email" placeholder="Email address" required />
                <textarea name="message" placeholder="Tell me about your project..." rows="3" required></textarea>
                <button type="submit" class="btn btn-cta"><i class="fas fa-rocket"></i> Send message</button>
            </form>

            <div class="signature-box">
                <strong>Andualem Guchi Gezahegn</strong><br />
                <i class="fas fa-briefcase"></i> Digital Specialist &amp; Developer<br />
                <i class="fas fa-phone"></i> +251 983693486<br />
                <i class="fab fa-telegram"></i> @Andualem_digital<br />
                <i class="fas fa-link"></i> Interactive Resume &amp; Case Studies: <a href="https://andualemguchigezahegn.github.io/-Andualem-_portfolio_page/" target="_blank">https://andualemguchigezahegn.github.io/-Andualem-_portfolio_page/</a><br />
                <span style="font-size:0.85rem; color:#5a4d40;">
                    <i class="fas fa-graduation-cap"></i> Haramaya University Natural Science | CGPA: 3.9<br />
                    <i class="fas fa-certificate"></i> Certified by Meta (Digital Literacy) &amp; Udacity
                </span>
            </div>
        </div>

        <!-- ===== FOOTER ===== -->
        <div class="footer-note">
            <i class="fas fa-code"></i> Andualem Guchi · built with <i class="fas fa-heart" style="color:#c47b4d;"></i> · portfolio
        </div>

    </div>
</div>
</body>
</html>
