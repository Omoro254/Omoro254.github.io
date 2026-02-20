<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dalmas Osuri | Network & System Administrator</title>

<style>
:root {
    --bg:#0a192f;
    --card:#112240;
    --text:#ccd6f6;
    --accent:#64ffda;
}

body.light {
    --bg:#f4f6f9;
    --card:#ffffff;
    --text:#333;
    --accent:#0077b6;
}

html {
    scroll-behavior:smooth;
}

body {
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background:var(--bg);
    color:var(--text);
    transition:0.3s ease;
}

nav {
    position:fixed;
    width:100%;
    background:var(--card);
    padding:15px;
    text-align:center;
    z-index:1000;
}

nav a {
    color:var(--accent);
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}

.theme-toggle {
    position:absolute;
    right:20px;
    top:15px;
    cursor:pointer;
    color:var(--accent);
}

header {
    padding:120px 20px 60px;
    text-align:center;
}

header img {
    width:160px;
    border-radius:50%;
    border:3px solid var(--accent);
}

section {
    padding:60px 20px;
    max-width:1000px;
    margin:auto;
}

h2 {
    border-bottom:2px solid var(--accent);
    padding-bottom:10px;
}

.card {
    background:var(--card);
    padding:20px;
    margin:20px 0;
    border-radius:10px;
    transition:transform 0.3s ease;
}

.card:hover {
    transform:translateY(-5px);
}

.skills span {
    display:inline-block;
    background:var(--accent);
    color:#000;
    padding:5px 10px;
    margin:5px;
    border-radius:5px;
    font-size:14px;
}

footer {
    text-align:center;
    padding:20px;
    background:var(--card);
}

.fade-in {
    opacity:0;
    transform:translateY(20px);
    transition:all 0.8s ease-out;
}

.fade-in.visible {
    opacity:1;
    transform:translateY(0);
}
</style>
</head>

<body>

<nav>
<a href="#home">Home</a>
<a href="#resume">Resume</a>
<a href="#projects">Projects</a>
<a href="#labs">Lab Challenges</a>
<a href="#contact">Contact</a>
<span class="theme-toggle" onclick="toggleTheme()">🌗</span>
</nav>

<header id="home" class="fade-in">
<img src="your-photo.jpg" alt="Profile Photo">
<h1>Dalmas Osuri</h1>
<p><strong>NETWORK ADMIN | SYSTEM ADMIN | ICT TECHNICIAN</strong></p>
<p>Dedicated IT professional with over 3 years of experience in system administration, network security, and information security management.</p>
</header>

<section id="resume" class="fade-in">
<h2>Resume</h2>

<div class="card">
<h3>Education</h3>
<p><strong>BSc Computer Science</strong><br>Maseno University – Kenya</p>
</div>

<div class="card">
<h3>Professional Experience</h3>

<h4>Information Security Specialist Intern – GIZ Kenya/Somalia (2025–Present)</h4>
<ul>
<li>Information asset classification and risk assessment documentation</li>
<li>Internal audit & penetration testing coordination</li>
<li>Security policy development and ISMS support</li>
</ul>

<h4>System/Network Admin Intern – Kenya Revenue Authority (2023–2024)</h4>
<ul>
<li>Level 1 & 2 technical support</li>
<li>Network monitoring and configuration</li>
<li>Disaster recovery planning & backups</li>
</ul>

<h4>ICT Technician Intern – Nyanza Reproductive Health Society (2020–2021)</h4>
<ul>
<li>Technical troubleshooting</li>
<li>IT documentation & inventory management</li>
</ul>

</div>

<div class="card skills">
<h3>Key Skills</h3>
<span>Network Security</span>
<span>System Administration</span>
<span>Risk Assessment</span>
<span>Firewall Configuration</span>
<span>Monitoring</span>
<span>Troubleshooting</span>
<span>Technical Support</span>
<span>Team Collaboration</span>
</div>

<div class="card">
<h3>Certifications</h3>
<ul>
<li>CCNA 1</li>
<li>Wireshark Ninja</li>
<li>Digital Forensics</li>
<li>Real Ethical Hacking</li>
<li>Cybersecurity Essentials</li>
<li>Data Protection</li>
</ul>
</div>

</section>

<section id="projects" class="fade-in">
<h2>Projects</h2>

<div class="card">
<h3>Network Security Monitoring System</h3>
<p>Implemented network traffic analysis using Wireshark and log monitoring to detect suspicious activity.</p>
</div>

<div class="card">
<h3>Disaster Recovery & Backup Plan</h3>
<p>Developed structured backup strategies and tested restoration processes to ensure business continuity.</p>
</div>

<div class="card">
<h3>Security Awareness Training Program</h3>
<p>Designed phishing awareness and cyber hygiene training materials for employees.</p>
</div>

</section>

<section id="labs" class="fade-in">
<h2>Lab Challenges</h2>

<div class="card">
<h3>SQL Injection Lab</h3>
<p><strong>Problem:</strong> Exploit vulnerable login form.</p>
<p><strong>Approach:</strong> Identified unsanitized inputs and tested injection payloads.</p>
<p><strong>Tools:</strong> Burp Suite, Browser DevTools</p>
<p><strong>Key Lesson:</strong> Always use parameterized queries.</p>
</div>

<div class="card">
<h3>Linux Privilege Escalation</h3>
<p><strong>Problem:</strong> Escalate privileges from user to root.</p>
<p><strong>Approach:</strong> Enumerated SUID files and exploited misconfigurations.</p>
<p><strong>Tools:</strong> LinPEAS, Linux CLI</p>
<p><strong>Key Lesson:</strong> Proper permissions prevent exploitation.</p>
</div>

</section>

<section id="contact" class="fade-in">
<h2>Contact</h2>

<div class="card">
<p><strong>Address:</strong> 42-40118</p>
<p><strong>Tel:</strong> +254741037755</p>
<p><strong>Email:</strong> dalmasosuri@gmail.com</p>
<p><strong>LinkedIn:</strong> Add your LinkedIn link</p>
<p><strong>GitHub:</strong> Add your GitHub link</p>
</div>

</section>

<footer>
© 2026 Dalmas Osuri | Professional Portfolio
</footer>

<script>
function toggleTheme() {
    document.body.classList.toggle("light");
}

const faders = document.querySelectorAll('.fade-in');
const appearOptions = { threshold: 0.2 };

const appearOnScroll = new IntersectionObserver(function(entries, observer) {
    entries.forEach(entry => {
        if (!entry.isIntersecting) return;
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
    });
}, appearOptions);

faders.forEach(fader => {
    appearOnScroll.observe(fader);
});
</script>

</body>
</html>
