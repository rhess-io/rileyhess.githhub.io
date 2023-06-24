
<html>
<head>
  <title>Riley Hess, M.S., Doctoral Candidate</title>
  <style>
    body {
      font-family: Helvetica, sans-serif;
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
      <button class="tab-button active" onclick="openTab(event, 'education')">Education</button>
      <button class="tab-button" onclick="openTab(event, 'skills')">Skills</button>
      <button class="tab-button" onclick="openTab(event, 'workexperience')">Work Experience</button>
      <button class="tab-button" onclick="openTab(event, 'projects')">Publications</button>
    </div>
    <div id="about" class="tab active">
      <h2>About Me</h2>
      <p>Hello, my name is .</p>
    </div>

 <div id="education" class="tab active">
      <h2>Education</h2>
     <ul>
    <li>
      <h3>Ph.D., Industrial-Organizational Psychology</h3>
      <p>University of Georgia</p>
      <p> Fall 2018 - Spring 2024 (anticipated)</p>
    </li>
        <li>
      <h4>M.S., Industrial-Organizational Psychology</h3>
      <p>University of Georgia</p>
      <p> Fall 2018 - Spring 2022</p>
    </li>
  <li>
      <h5>B.A., Psychology, with Honors, Certificate in Research Experience</h3>
      <p>University of Kansas</p>
      <p> Fall 2014 - Fall 2017</p>
    </li>
      </ul>
    </div>
    <div id="skills" class="tab">
      <h2>Skills</h2>
      <ul>
        <li>Statistical Coding Languages and Software (R, R Markdown, SPSS, Tableau)</li>
        <li>Data and Code Storage and Management Systems (Gitlab, Github, Jupyterlab, AWS)</li>
        <li>Quantitative and Qualitative Research Methods</li>
        <li>Psychometrics</li>
        <li>IRT</li>
        <li>Advanced Statistics</li>
        <li>Consulting and Stakeholder Analysis</li>
        <li>People Analytics</li>
        <li>Job Analysis and Competency Modeling</li>
        <li>Data Visualization</li>
        <li>Experimental Design</li>
        <li>Survey Research and Crowdsourcing (MTurk, Prolific)</li>
        <li>Qualtrics</li>
        <li>Data Visualization</li>
      </ul>
    </div>
    <div id="projects" class="tab">
      <h2>Publications</h2>
      <ul>
        <li>Hess, R. A., Erickson, O. A., Cole, R. B., Isaacs, J. M., Alvarez-Clare, S., Arnold, J., ... & Dolan, E. L. (2023). Virtually the same? Evaluating the effectivenessof remote undergraduate research experiences. CBE—Life Sciences Education, 22(2).</li>
        <li>Hess, R. (Co-chair), Outland, N. (Co-Chair), & Behrend, T. (Discussant). (2023, April).
Can (A)I be on your team? Evaluating uses of AI in organizationalteams
[Symposium]. SIOP Annual Conference: Boston, MA.</li>
       <li> Hess, R. A., & Carter, N. T. (2022, February). Human-Technology Social Perception: Examining Emotions and Behaviors Toward AI at Work. Poster presented at the Society for Personality and Social Psychology 2022 Annual Convention: San Francisco, CA.</li>
        <li>Hess, R. A., Kang, B., Richardson, J., Stryker, S. R., & Outland, N. (2022, April).
A Qualitative Investigation of Fear and Acceptance of AI at Work.
SIOPAnnual Conference: Seattle, WA.
[Received top 10 poster award]</li>
      <li>Hess, R. A., & Carter, N. T. (2020, May). Job Applicant Reactions to AI-Based Selection: A Double-Edged Sword. Poster presented at the 32nd Association for Psychological Science Annual Convention: Chicago, IL. (Online)</li>
      <li>Hess, R. A., & Carter, N. T. (2020, April). Assessing Warmth and Competence in Artificial Intelligence Assistants. In R. A. Hess & K. Nolan (chairs), Trust and the Artificial Intelligence-Human Interface at Work. Symposium presented at the 34th annual Society for Industrial and Organizational Psychology Conference: Austin, TX. (Online)</li>
      <li>Hess, R. A., & Carter, N. T. (2020, February). Developing a Scale for Human-AI Interaction. Poster presented at the Society for Personality and Social Psychology 2020 Annual Convention: New Orleans, LA.</li>
      <li>Hess, R. A., & Carter, N. T. (2019, May). Revisiting the Genetic Correlation of Job Satisfaction and Personality. Poster presented at the European Association of Work and Organizational Psychology 2019 Congress: Turin, Italy.</li>
      <li>Hess, R. A., Landau, M. J., & Carter, N. T. (2019, May). Conscientiousness and performance: Regulatory focus as a moderator of curvilinearity. Poster presented at the European Association of Work and Organizational Psychology 2019 Congress: Turin, Italy.</li>
    <li>Hess, R. A., & Carter, N. T. (2019, April). Revisiting the genetic correlation of job satisfaction and personality. Poster presented at the Society for Industrial and Organizational Psychology Annual Conference: Washington, D.C.</li>
    <li>Hess, R. A., Landau, M. J., & Carter, N. T. (2019, April). Conscientiousness and performance: Regulatory focus as a moderator of curvilinearity. In Xiaoyuan (Susan) Zhu (Chair), Understanding Curvilinear Relationships in Selection Research and Practice. In Zhu, X. & Impelman, K. (co-chairs), Understanding Curvilinear Relationships in Selection Research and Practice. Symposium presented at the 2019 Meeting of the Society for Industrial and Organizational Psychology: National Harbor, MD.</li>
   <li>Atakere, D., Naemi, P., Kuofie, A., & Hess, R. (2019). General well-being in adult Black males with chronic illness. Gerontology and Geriatric Medicine’s special issue on diverse race and ethnic populations and aging.</li>
    <li>Hess, R. A., & Landau, M. J. (2018, March). The influence of motivation on personality: Exploring the psychological basis of conscientiousness. Poster presented at the Society for Personality and Social Psychology 2018 Annual Convention: Atlanta, GA.</li>
    <li>Hess, R. A., Landau, M. J. (2018, April). The influence of motivation on personality: Exploring the psychological basis of conscientiousness. Poster presented at the Midwestern Psychological Association Annual Meeting: Chicago, IL.</li>
  <li>Hess, R. A., Zayyad, T.N., Schneider, A. M., Miller, J. M., Landau, M. J., (2018, April). Why Does Time Fly? Exploring Whether Interpersonal Power Biases Time Perception. Poster presented at the Midwestern Psychological Association 90th Annual Meeting: Chicago, IL.</li>
  <li>Hess, R. A., & Baker, T. A., (2016, April). Understanding what Black Men Want in a Chronic Disease Self-Management Program. Poster presented at the University of Kansas Undergraduate Symposium, Lawrence, KS.</li>
    <li>Nordhem, L., Hess, R. A., & Baker, T. A., (2016, April). Chronic Disease Intervention Programs for Black Men: What Works? Poster presented at the University of Kansas Undergraduate Psychology Symposium, Lawrence, KS.</li>
      </ul>
    </div>
    
<div id="workexperience" class="tab">
  <h2>Work Experience</h2>
  <ul>
    <li>
      <h3>State Farm</h3>
      <p>Position: I/O Psychology PhD Intern</p>
      <p>Duration: May 2022 - May 2023</p>
    </li>
    <li>
      <h3>Coachability Consultants Inc.</h3>
      <p>Position: Data Science Consultant (Contract)</p>
      <p>Duration: August - December 2022</p>
    </li>
    <li>
      <h3>The Predictive Index</h3>
      <p>Position: Psychometrics Consultant (Contract)</p>
      <p>Duration: December 2021 - April 2022</p>
    </li>
  </ul>
</div>



  
  <footer>
    <p>&copy; 2023. All rights reserved.</p>
  </footer>
