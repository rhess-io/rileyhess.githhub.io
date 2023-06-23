# rileyhess.githhub.io

<!DOCTYPE html>
<html>
<head>
  <title>Riley Hess, M.S., Doctoral Candidate</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 20px;
    }
    .tab {
      display: none;
    }
    .tab.active {
      display: block;
    }
    .tab-button {
      background-color: #333;
      color: #fff;
      padding: 10px;
      border: none;
      cursor: pointer;
    }
    .tab-button.active {
      background-color: #555;
    }
  </style>
  <script>
    function openTab(evt, tabName) {
      var i, tabContent, tabButtons;
      tabContent = document.getElementsByClassName("tab");
      for (i = 0; i < tabContent.length; i++) {
        tabContent[i].style.display = "none";
      }
      tabButtons = document.getElementsByClassName("tab-button");
      for (i = 0; i < tabButtons.length; i++) {
        tabButtons[i].className = tabButtons[i].className.replace(" active", "");
      }
      document.getElementById(tabName).style.display = "block";
      evt.currentTarget.className += " active";
    }
  </script>
</head>
<body>
  <header>
    <h1>Welcome to My Personal Website</h1>
  </header>
  <main>
    <div class="tab-button-container">
      <button class="tab-button active" onclick="openTab(event, 'about')">About Me</button>
      <button class="tab-button" onclick="openTab(event, 'skills')">Skills</button>
      <button class="tab-button" onclick="openTab(event, 'projects')">Publications</button>
      <button class="tab-button" onclick="openTab(event, 'projects')">Work Experience</button>

    </div>
    <div id="about" class="tab active">
      <h2>About Me</h2>
      <p>Hello, my name is .</p>
    </div>
    <div id="skills" class="tab">
      <h2>Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
      </ul>
    </div>
    <div id="projects" class="tab">
      <h2>Projects</h2>
      <ul>
        <li>Project 1</li>
        <li>Project 2</li>
        <li>Project 3</li>
      </ul>
    </div>
  </main>
  <footer>
    <p>&copy; 2023. All rights reserved.</p>
  </footer>
</body>
</html>
