<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Apilash Balasingham – Big Data Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #003266;
      --accent: #0086ff;
      --background: #f9fafb;
      --text: #111827;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--background);
      color: var(--text);
      line-height: 1.6;
      padding: 20px;
    }
    header {
      background-color: var(--primary);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    nav a {
      margin: 0 15px;
      color: #cbd5e1;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover { color: white; }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    h2 { margin-bottom: 15px; color: var(--accent); }
    ul { list-style: disc; margin-left: 20px; }
    footer {
      text-align: center;
      margin-top: 60px;
      color: #6b7280;
      font-size: 0.9rem;
    }
    a.button {
      display: inline-block;
      margin-top: 10px;
      background: var(--accent);
      color: white;
      padding: 10px 16px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    a.button:hover { background-color: #2563eb; }
    @media (max-width: 600px) {
      header h1 { font-size: 1.8rem; }
      nav a { display: block; margin: 10px 0; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Apilash Balasingham</h1>
    <p>CRM & Data Analyst | Python • Spark • SQL • GCP • AI</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#tools">Tools</a>
      <a href="#resume">Resume</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a data-driven professional at Deutsche Bank and a Master's student in Business Analytics & Data Science at IE University (Madrid). I specialize in CRM systems, real-time data pipelines, cloud infrastructure, and AI solutions. I enjoy building things that connect business and technology – and making data work for people.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Programming: Python, SQL, PHP</li>
      <li>Big Data: Apache Spark (Structured Streaming), Apache NiFi, Kafka</li>
      <li>Analytics: Pandas, NumPy, Tableau, Matplotlib</li>
      <li>CRM & Cloud: Salesforce (BlueSpace), Google Cloud (GCP Certified)</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Crypto Dashboard</strong> – Live BTC/ETH tracking with Kafka, Spark Streaming & Matplotlib</li>
      <li><strong>AI Sales Assistant</strong> – GPT-powered chatbot for CRM support in banking</li>
      <li><strong>GCP BigQuery Pipeline</strong> – Covid-19 analysis using SQL on cloud data warehouse</li>
    </ul>
  </section>

  <section id="tools">
    <h2>Tools & Platforms</h2>
    <ul>
      <li>Apache Spark, NiFi, Kafka, Hadoop</li>
      <li>Git, Docker, DBeaver, VS Code</li>
      <li>GCP (BigQuery, Firestore), MinIO, Tableau</li>
    </ul>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p>You can view or download my resume below:</p>
    <a href="resume.pdf" class="button" target="_blank">Download Resume</a>
  </section>

  <footer>
    <p>© 2025 Apilash Balasingham | Built with ❤️ on GitHub Pages</p>
  </footer>
</body>
</html>
