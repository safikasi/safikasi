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
    }

    body {
      font-family: Arial, sans-serif;
    }

    h1, h3, h4 {
      margin: 0;
    }

    h1, h3 {
      text-align: center;
    }

    h4 {
      margin-top: 10px;
    }

    .bold {
      font-weight: bold;
    }

    .container {
      text-align: center;
      margin: 20px;
    }

    .icon {
      margin: 10px;
    }
  </style>
</head>
<body>
  <h1 align="center">Hi 👋, I'm Safwan Kasi</h1>

  <h3 class="blinking-text" id="header"></h3>

  <h4 align="left">
    <span class="bold">About Me:</span><br><br>
    🎓 Computer Science Student at NUST.<br>
    🧠 Currently pursuing a BS in Computer Science.<br>
    🌱 Just dipping my toes into machine learning and deep learning<br>
    💼 Open to internship and job opportunities.
  </h4>

  <h3 align="center">💻 Programming & Markup Languages:</h3>
  <div class="container">
    <img src="https://cdn.simpleicons.org/c++/00599C" height="40" alt="cplusplus logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo" class="icon" />
  </div>

  <h3 align="center">🛠️ Frameworks & Libraries:</h3>
  <div class="container">
    <img src="https://cdn.simpleicons.org/pandas/150458" height="40" alt="pandas logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pycharm/000000" height="40" alt="pycharm logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pytest/0A9EDC" height="40" alt="pytest logo" class="icon" />
    <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" height="40" alt="pytorch logo" class="icon" />
    <img src="https://cdn.simpleicons.org/numpy/013243" height="40" alt="numpy logo" class="icon" />
  </div>

  <h3 align="center">📂 Databases:</h3>
  <div class="container">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neo4j/neo4j-original.svg" height="40" alt="neo4j logo" class="icon" />
    <img src="https://cdn.simpleicons.org/apachecassandra/1287B1" height="40" alt="apachecassandra logo" class="icon" />
  </div>

  <h3 align="center">🔧 Tools & Technologies:</h3>
  <div class="container">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="40" alt="flutter logo" class="icon" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo" class="icon" />
  </div>

  <h3 align="center">📊 GitHub Stats:</h3>
  <div class="container">
    <img src="https://github-readme-stats.vercel.app/api?username=safikasi&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=safikasi&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph" />
    <img src="https://streak-stats.demolab.com?user=safikasi&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" height="150" alt="streak graph" />
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=safikasi&radius=16&theme=react&area=true&order=5" height="300" alt="activity-graph graph" />
  </div>

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
