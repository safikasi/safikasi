<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Safwan Kasi</title>
  <style>
    @keyframes blink {
      50% {
        opacity: 0;
      }
    }

    .blinking-text {
      font-size: 1.5rem;
      font-weight: bold;
      animation: blink 1s steps(1, end) infinite;
      color: #1db9d5;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e1e;
      color: #e0e0e0;
      margin: 0;
      padding: 0;
    }

    h1, h3, h4 {
      margin: 0;
    }

    h1, h3 {
      text-align: center;
    }

    h4 {
      margin: 20px;
      line-height: 1.8;
    }

    .bold {
      font-weight: bold;
    }

    .container {
      text-align: center;
      margin: 20px 0;
    }

    .icon {
      margin: 10px;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      justify-items: center;
      align-items: center;
      margin: 20px;
    }

    .stats-grid img {
      max-width: 100%;
      height: auto;
    }

    .divider {
      margin: 20px 0;
      border: none;
      border-top: 2px solid #444;
      width: 90%;
      margin-left: auto;
      margin-right: auto;
    }

    a {
      color: #1db9d5;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1 align="center">Hi 👋, I'm Safwan Kasi</h1>
  <hr class="divider">

  <h3 class="blinking-text" id="header"></h3>
  <hr class="divider">

  <h4>
    <span class="bold">About Me:</span><br><br>
    🎓 <span class="bold">Computer Science Student</span> at <a href="#">NUST</a>.<br>
    🧠 Currently pursuing a <span class="bold">BS in Computer Science</span>.<br>
    🌱 Just dipping my toes into <span class="bold">machine learning</span> and <span class="bold">deep learning</span>.<br>
    💼 Open to <span class="bold">internship</span> and <span class="bold">job opportunities</span>.<br>
  </h4>
  <hr class="divider">

  <h3 align="center">💻 Programming & Markup Languages:</h3>
  <div class="container">
    <img src="https://cdn.simpleicons.org/c++/00599C" height="40" alt="C++ logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5 logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3 logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="C logo" class="icon" />
  </div>
  <hr class="divider">

  <h3 align="center">🛠️ Frameworks & Libraries:</h3>
  <div class="container">
    <img src="https://cdn.simpleicons.org/pandas/150458" height="40" alt="Pandas logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pycharm/000000" height="40" alt="PyCharm logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pytest/0A9EDC" height="40" alt="Pytest logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" height="40" alt="PyTorch logo" class="icon" />
    <img src="https://cdn.simpleicons.org/numpy/013243" height="40" alt="NumPy logo" class="icon" />
  </div>
  <hr class="divider">

  <h3 align="center">📂 Databases:</h3>
  <div class="container">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="MySQL logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="MongoDB logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neo4j/neo4j-original.svg" height="40" alt="Neo4j logo" class="icon" />
    <img src="https://cdn.simpleicons.org/apachecassandra/1287B1" height="40" alt="Apache Cassandra logo" class="icon" />
  </div>
  <hr class="divider">

  <h3 align="center">🔧 Tools & Technologies:</h3>
  <div class="container">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="Git logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="GitHub logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="Figma logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="40" alt="Flutter logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="VS Code logo" class="icon" />
  </div>
  <hr class="divider">

  <h3 align="center">📊 GitHub Stats:</h3>
  <div class="stats-grid">
    <img src="https://github-readme-stats.vercel.app/api?username=safikasi&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" alt="Stats graph" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=safikasi&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" alt="Languages graph" />
    <img src="https://streak-stats.demolab.com?user=safikasi&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" alt="Streak graph" />
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=safikasi&radius=16&theme=react&area=true&order=5" alt="Activity graph" />
  </div>
  <hr class="divider">

  <script>
    const header = document.getElementById('header');
    const texts = ['Python Enthusiast', 'Aspiring AI Innovator'];
    let index = 0;

    setInterval(() => {
      header.textContent = texts[index];
      index = (index + 1) % texts.length;
    }, 1000);
  </script>
</body>
</html>
