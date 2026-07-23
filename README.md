<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Chollangi Srilokesh | Resume</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(135deg,#0f172a,#1e3a8a,#2563eb);
background-size:400% 400%;
animation:bgAnimation 12s infinite alternate;
padding:40px;
}

@keyframes bgAnimation{
0%{background-position:left;}
100%{background-position:right;}
}

.container{
max-width:1000px;
margin:auto;
background:rgba(255,255,255,.12);
backdrop-filter:blur(15px);
border-radius:20px;
padding:40px;
color:white;
box-shadow:0 15px 40px rgba(0,0,0,.4);
animation:fadeUp 1.2s ease;
}

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(50px);
}
to{
opacity:1;
transform:translateY(0);
}
}

header{
text-align:center;
padding-bottom:25px;
border-bottom:2px solid rgba(255,255,255,.3);
}

header h1{
font-size:42px;
letter-spacing:2px;
color:#00e5ff;
text-shadow:0 0 15px cyan;
}

header h3{
margin-top:10px;
font-weight:400;
color:#ddd;
}

.contact{
margin-top:20px;
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
font-size:15px;
}

section{
margin-top:35px;
animation:slideIn 1s ease;
}

@keyframes slideIn{
from{
opacity:0;
transform:translateX(-40px);
}
to{
opacity:1;
transform:translateX(0);
}
}

h2{
display:inline-block;
padding-bottom:5px;
border-bottom:3px solid #00e5ff;
margin-bottom:15px;
color:#00e5ff;
}

p{
line-height:1.8;
}

ul{
padding-left:20px;
}

li{
margin-bottom:10px;
transition:.3s;
}

li:hover{
transform:translateX(10px);
color:#00e5ff;
}

.card{
background:rgba(255,255,255,.08);
padding:20px;
border-radius:15px;
margin-bottom:20px;
transition:.4s;
border:1px solid rgba(255,255,255,.2);
}

.card:hover{
transform:translateY(-8px) scale(1.02);
box-shadow:0 15px 30px rgba(0,229,255,.3);
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.skill{
background:rgba(255,255,255,.08);
padding:15px;
border-radius:12px;
transition:.4s;
}

.skill:hover{
background:#00e5ff;
color:#000;
transform:scale(1.05);
}

footer{
margin-top:40px;
text-align:center;
color:#ddd;
font-size:14px;
}

@media(max-width:700px){

header h1{
font-size:30px;
}

.contact{
flex-direction:column;
align-items:center;
}

}

</style>

</head>

<body>

<div class="container">

<header>

<h1>CHOLLANGI SRILOKESH</h1>

<h3>AI Engineer | Machine Learning Enthusiast</h3>

<div class="contact">

<div>📞 +91 6300852355</div>

<div>📧 srilokeshchollangi369@gmail.com</div>

<div>🔗 LinkedIn</div>

<div>🔗 GitHub</div>

</div>

</header>

<section>

<h2>Professional Summary</h2>

<p>

Aspiring AI Engineer with strong knowledge of Python, Machine Learning,
Deep Learning, Data Science and Generative AI. Passionate about building
intelligent applications using LLMs, RAG, NLP and Computer Vision to solve
real-world problems.

</p>

</section>

<section>

<h2>Technical Skills</h2>

<div class="skills">

<div class="skill"><b>Languages</b><br>Python, SQL, Java</div>

<div class="skill"><b>Machine Learning</b><br>ML, DL, NLP, Computer Vision</div>

<div class="skill"><b>Frameworks</b><br>TensorFlow, PyTorch, LangChain</div>

<div class="skill"><b>Libraries</b><br>NumPy, Pandas, Scikit-learn</div>

<div class="skill"><b>Database</b><br>MySQL, PostgreSQL</div>

<div class="skill"><b>Tools</b><br>Git, GitHub, Docker, VS Code</div>

</div>

</section>

<section>

<h2>Projects</h2>

<div class="card">

<h3>AI Resume Analyzer</h3>

<p><b>Tech:</b> Python, Streamlit, NLP</p>

<ul>

<li>Analyzed resumes using NLP.</li>

<li>Generated ATS recommendations.</li>

<li>Interactive Streamlit interface.</li>

</ul>

</div>

<div class="card">

<h3>Intelligent Chatbot using LLM</h3>

<p><b>Tech:</b> LangChain, Hugging Face, FAISS</p>

<ul>

<li>Built an LLM-powered chatbot.</li>

<li>Implemented RAG pipeline.</li>

<li>Semantic search using vector database.</li>

</ul>

</div>

<div class="card">

<h3>House Price Prediction</h3>

<p><b>Tech:</b> Python, Scikit-learn</p>

<ul>

<li>Regression model for price prediction.</li>

<li>Feature engineering and preprocessing.</li>

<li>Compared multiple ML algorithms.</li>

</ul>

</div>

</section>

<section>

<h2>Education</h2>

<div class="card">

<h3>B.Tech – Computer Science & Engineering</h3>

<p>Pragati Engineering College</p>

<p>CGPA: 8.6 | 2025–2028</p>

</div>

<div class="card">

<h3>Diploma – Computer Engineering</h3>

<p>Aditya Polytechnic College</p>

<p>95% | 2022–2025</p>

</div>

</section>

<section>

<h2>Certifications</h2>

<ul>

<li>Python for Data Science</li>

<li>Machine Learning with Python</li>

<li>Deep Learning Fundamentals</li>

<li>Generative AI & LLMs</li>

<li>SQL for Data Analytics</li>

</ul>

</section>

<section>

<h2>Achievements</h2>

<ul>

<li>Solved DSA problems on coding platforms.</li>

<li>Built AI & ML projects using Python.</li>

<li>Learning AI Agents, RAG and LLMs.</li>

</ul>

</section>

<footer>

Designed with ❤️ by Chollangi Srilokesh

</footer>

</div>

</body>
</html>
