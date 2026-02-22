<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tanmay Raj | Data Scientist</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:'Inter',sans-serif;
background:#0b0f19;
color:#e6edf3;
scroll-behavior:smooth;
}

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
}

header h1{
font-size:60px;
margin:0;
font-weight:700;
}

header p{
font-size:20px;
opacity:0.9;
margin-top:10px;
}

.btn{
margin-top:25px;
padding:12px 28px;
background:#00c6ff;
color:#000;
border-radius:30px;
text-decoration:none;
font-weight:600;
transition:0.3s;
}

.btn:hover{
background:#00a2cc;
}

.section{
padding:80px 10%;
}

.section h2{
font-size:32px;
margin-bottom:40px;
border-bottom:2px solid #00c6ff;
display:inline-block;
padding-bottom:10px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.card{
background:#161b22;
padding:25px;
border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.5);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
border-radius:10px;
margin-bottom:15px;
}

.skills span{
display:inline-block;
background:#00c6ff;
color:#000;
padding:8px 18px;
margin:8px;
border-radius:25px;
font-size:14px;
font-weight:600;
}

footer{
text-align:center;
padding:40px;
background:#0a0d14;
font-size:14px;
opacity:0.7;
}
</style>
</head>

<body>

<header>
<h1>Tanmay Raj</h1>
<p>Data Analyst → Aspiring Data Scientist</p>
<p>SQL • Power BI • Python • Machine Learning</p>
<a href="#projects" class="btn">View My Work</a>
</header>

<section class="section">
<h2>About Me</h2>
<p>
Data professional with 4+ years of experience in Business Intelligence and dashboard development.
Designed Pan-India reporting systems and managed structured employee master datasets.
Currently building end-to-end Machine Learning solutions and deployment pipelines.
</p>

<br>

<strong>Impact Highlights:</strong>
<ul>
<li>Built CMPFO Pan-India Employee Dashboard</li>
<li>Automated reporting workflows using SQL</li>
<li>Improved data visibility & reporting efficiency</li>
</ul>
</section>

<section class="section">
<h2>Technical Expertise</h2>
<div class="skills">
<span>SQL</span>
<span>Power BI</span>
<span>Python</span>
<span>Machine Learning</span>
<span>Data Modeling</span>
<span>Pandas</span>
<span>MySQL</span>
<span>Excel Automation</span>
</div>
</section>

<section class="section" id="projects">
<h2>Featured Projects</h2>

<div class="grid">

<div class="card">
<h3>CMPFO Employee Dashboard</h3>
<img src="https://github.com/anonymous-tanmay/Employee_Master_Data_Dashboard/blob/master/EMD_Dashboard_Image.jpg?raw=true">
<p>Executive-level Power BI dashboard for HR analytics and workforce tracking.</p>
<a href="https://github.com/anonymous-tanmay/Employee_Master_Data_Dashboard" class="btn">GitHub</a>
</div>

<div class="card">
<h3>COVID-19 Global Analysis</h3>
<img src="https://github.com/anonymous-tanmay/Covid_Dashboard/blob/master/Covid_Dashboard_Project.jpg?raw=true">
<p>Interactive global data dashboard with time-series and mortality analysis.</p>
<a href="https://github.com/anonymous-tanmay/Covid_Dashboard" class="btn">GitHub</a>
</div>

<div class="card">
<h3>Upcoming: ML Prediction Model</h3>
<p>Regression & Classification models with full EDA, feature engineering and deployment using Streamlit.</p>
<a href="#" class="btn">Coming Soon</a>
</div>

</div>
</section>

<section class="section">
<h2>Career Objective</h2>
<p>
Seeking Data Analyst / Junior Data Scientist roles where I can apply advanced analytics,
SQL expertise, and machine learning techniques to drive measurable business impact.
</p>
</section>

<footer>
© 2026 Tanmay Raj | Data Scientist Portfolio
</footer>

</body>
</html>
