# my_portfolio
My Portfolio Repo
[portfolionew.html](https://github.com/user-attachments/files/23151069/portfolionew.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>portfolio</title>
</head>
<style>
  body{
    background-color: #0f172a;
    color: white;
    font-family: Arial, sans-serif;
    padding: 5px;
  }
  header {
    background-color: #1e293b;
    padding: 20px;
    text-align: center;
    color: #38bdf8;
    text-shadow: 0px 0px 20px rgba(56,189,248,0.8);
    font-size: 35px;
    font-weight: bolder;
  }
  header p{
    font-size: 20px;
    color: #94a3b8;
    font-weight: normal;
  }
 nav {
  background-color: #1e293b;
  padding: 20px;
 }
  .anav {
  display: flex;
  gap: 20px;
  margin-left: 480px;
  margin-right: 150px;
}

  .anav a {
  color: white;
  font-size: 15px;
  font-weight: bolder;
  text-decoration: none;
  transition: 0.3s;
}

  h2{
    color: #38bdf8;
    font-size: 30px;
    margin-top: 50px;
  }
  .section{
     
      /* max-width: 1000px; */
      /* margin: auto; */
      line-height: 30px;
      margin-right: 350px;
      margin-left: 100px;
  }
  ul{
    list-style-type: none;
    padding: 0;
  }
  .projectsdiv{
    background-color: #1e293b;
    padding: 10px;
    border-radius: 10px;
    margin-bottom: 15px;
    
  }
  .a{
    color: #38bdf8;
    text-decoration: none;
    margin-right: 50px;
  }
 
 img {
    border-radius: 5%;
    height: 300px;
    width: 300px;
    /* object-fit: cover;  */
    float: right;
    margin-left: 20px;
    margin-top: 60px;
    margin-right: 60px;
    border: 5px solid #38bdf8  ;
    box-shadow: 0 0 40px rgba(56,189,248,0.6);
    border-style: groove;
  }
   .about {
    line-height: 30px;
    overflow: auto;
    margin-left: 100px;
    
  }
  .h21 {
    color: #38bdf8;
    font-size: 30px;
    margin-bottom: 15px;
    margin-left: 100px;
  }
</style>
<body>
  <header>Sai Charan Chebrolu!!
    <p>Data Science Enthusiast</p>
  </header>
  <br>
  <nav>
    <div class="anav">
    <a href="#About Me">About Me</a>
    <a href="#Skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#Education">Education</a>
    <a href="#Achievements">Achievements</a>
    <a href="#contact">contact</a></div>
  </nav>
  <img src="2312.jpg" alt="sai charan">
  <h2 class="h21" id="About Me">About Me</h2>
  
  <p class="about">I’m a passionate Data Science student who enjoys solving real-world problems through programming, data analysis, and design. With experience in Python, SQL, Java, and data science libraries like Pandas,NumPy, and Scikit-Learn, I love building projects that blend creativity with logic. My interests includemachine learning, AI, and data visualization, and I’m always eager to learn new technologies and apply themto impactful projects.</p>
    
  <div class="section">
    <h2 id="Skills">Skills</h2>
    <ul>
      <li><b>Programming Languages:</b> Python, SQL, Java</li>
      <li><b>Data Science Libraries:</b> Pandas, NumPy, Matplotlib</li>
      <li><b>Data Visualization:</b> Matplotlib, Seaborn</li>
    </ul>
  </div>
  <div class="section">
    <h2 id="Projects">Projects</h2>
    <div class="projectsdiv">
      <h3>Fake News Detection ( Python ,LSTM)</h3>
      <p>A deep learning model that classifies news articles as real or fake using NLP techniques.</p>
    </div>
    <div class="projectsdiv">
      <h3> College Fest Management System (DBMS Project)</h3>
      <p>Database-driven project for managing events, participants, and sponsors efficiently.</p>
    </div>
    <div class="projectsdiv">
      <h3>Network Simulation (Cisco Packet Tracer)</h3>
      <p>Designed and configured a small-scale computer network with routers, switches, and PCs.</p>
    </div>
  </div>
  
  <div class="section">
    <h2 id="Education">Education</h2>
    <h3>B.Tech in Computer Science (Data Science)</h3>
    <p>Relavant Courses: DBMS ,DSA, Java, Python, Computer Networks, HTML, CSS</p>

  </div>
  <div class="section">
    <h2 id="Achievements">Achievements & Certifications</h2>
    <ul>
      
      <li>📜 Completed "Python Data Analytics" certification on Coursera.</li>
      <li>📜 Completed "Meta Data Analyst" certification by coursera</li>
      
  </div>
  <div class="section">
    <h2 id="contact">contact</h2>
    <a href="mailto:saicharan240506@gmail.com" class="a" target="_blank">Email</a>
    <a href="https://www.linkedin.com/in/sai-charan-chebrolu" class="a" target="_blank">Linkedin</a>
    <a href="https://github.com/SaiCharanChebrolu" class="a" target="_blank">Github</a>
  </div>
</body>
</html>
