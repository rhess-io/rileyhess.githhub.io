# rileyhess.githhub.io

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
      background-color: #577590;
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
      background-color: #4d908e;
      color: #fff;
      padding: 10px;
      border: none;
      cursor: pointer;
    }
    .tab-button.active {
      background-color: #43aa8b;
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
    <h1>Riley Hess, M.S., Doctoral Candidate</h1>
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
      <h2>Publications</h2>
      <ul>
        <li>Hess, R. A., Erickson, O. A., Cole, R. B., Isaacs, J. M., Alvarez-Clare, S., Arnold, J., ... & Dolan, E. L. (2023). Virtually the same? Evaluating the effectivenessof remote undergraduate research experiences. CBE—Life Sciences Education, 22(2).</li>
        <li>Hess, R. (Co-chair), Outland, N. (Co-Chair), & Behrend, T. (Discussant). (2023, April).
Can (A)I be on your team? Evaluating uses of AI in organizationalteams
[Symposium]. SIOP Annual Conference: Boston, MA.</li>
        <li>Hess, R. A., Kang, B., Richardson, J., Stryker, S. R., & Outland, N. (2022, April).
A Qualitative Investigation of Fear and Acceptance of AI at Work.
SIOPAnnual Conference: Seattle, WA.
[Received top 10 poster award]</li>
      </ul>
    </div>
  </main>
  <footer>
    <p>&copy; 2023. All rights reserved.</p>
  </footer>
</body>
</html>
