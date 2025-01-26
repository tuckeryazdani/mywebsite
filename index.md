<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects</title>
  <link href="main.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f9;
      color: #333;
    }
    .topnav {
      background-color: #333;
      overflow: hidden;
      padding: 0.5rem 1rem;
    }
    .topnav a {
      color: #f4f4f9;
      text-decoration: none;
      padding: 0.5rem 1rem;
      display: inline-block;
    }
    .topnav a:hover {
      background-color: #575757;
    }
    .topnav a.active {
      background-color: #0078d4;
    }
    .bio {
      font-size: 1rem;
      line-height: 1.8;
      margin-top: 1rem;
    }
    .social {
      margin: 0 10px;
    }
    h2, h3 {
      color: #0078d4;
    }
    ul {
      padding-left: 1.5rem;
    }
    li {
      margin-bottom: 0.5rem;
    }
    .content {
      max-width: 800px;
      margin: 0 auto;
      padding: 1rem;
    }
    p {
      margin: 0.5rem 0;
    }
  </style>
</head>
<body>
  <div class="topnav"> 
    <a href="https://tuckeryazdani.github.io/">Home</a>
    <a href="about.html">About</a>
    <a class="active" href="projects.html">Projects</a>
    <a href="twitter.html">Twitter</a>
  </div>

  <div class="content">
    <div align="left">
      <p class="bio">
        <strong>Software Engineer</strong><br>
        B.S. Mathematics (Concentration in Statistics)
      </p>
    </div>
    <h1>Projects</h1>
    <a href="https://github.com/tuckeryazdani/wsb_journal">
      <h3>The Wall Street Bets Journal (04/2022)</h3>
    </a>
    <ul>
      <li>Created a Python script that returns frequencies of popular stocks mentioned in the WallStreetBets Reddit community and gets stock updates from Yahoo Finance.</li>
      <li>Created a Twitter account that uses the Twitter API to automatically post weekly updates based on these insights.</li>
      <li>Updated the script to automatically update the website with tweets and handle Git commands.</li>
      <li>Added error logging for Twitter-related issues.</li>
      <li>Now pulls data from NASDAQ to analyze seasonal stock trends.</li>
      <li>More features coming soon.</li>
      <li>Twitter URL: <a href="https://twitter.com/WSB_Journal">Wall Street Bets Journal Twitter</a></li>
    </ul>
    <a href="https://github.com/tuckeryazdani/tuckeryazdani.github.io" target="_blank">
      <h3>Portfolio: Personal Website (04/2022)</h3>
    </a>
    <ul>
      <li>Built a website outlining my education, experience, and projects.</li>
      <li>Added a Twitter page that gets updated with posts from "The Wall Street Bets Journal".</li>
      <li>More features coming soon.</li>
    </ul>
    <a href="https://github.com/tuckeryazdani/SeniorProject2019">
      <h3>Senior Project: “Autonomizing Affine Digraph Ciphers” (12/2019)</h3>
    </a>
    <ul>
      <li>Built a program in Python to decode Affine Digraph Ciphers using linear algebra and number theory.</li>
      <li>Wrote a research paper outlining the project.</li>
      <li>Presented the project to an audience of peers and professors.</li>
    </ul>
    <a href="https://github.com/tuckeryazdani/xlwings/blob/main/xlwings.py">
      <h3>xlwings Financial Spreadsheet Creation</h3>
    </a>
    <ul>
      <li>Created a Python script to populate a financial spreadsheet using the xlwings library.</li>
    </ul>
    <a href="https://github.com/tuckeryazdani/ChessEngineAASpr2022" target="_blank">
      <h3>Advanced Algorithms Project: Kennesaw State University (03/2022)</h3>
    </a>
    <h2>Contact Information</h2>
    <p>Personal Email: <a href="mailto:tuckeryazdani@gmail.com">tuckeryazdani@gmail.com</a></p>
    <h2>Links</h2>
    <p>
      <a href="https://www.linkedin.com/in/tuckeryazdani/" target="_blank">
        <img src="https://user-images.githubusercontent.com/84822334/148589136-9acd742f-e004-4d54-b1b4-181f8bc7dc98.png" class="social" width="20" height="20" title="LinkedIn" alt="LinkedIn">
      </a>
      <a href="https://github.com/tuckeryazdani/" target="_blank">
        <img src="https://user-images.githubusercontent.com/84822334/148658020-ae86cfb7-f259-4503-93fc-156a168d2a9d.png" class="social" width="20" height="20" title="GitHub" alt="GitHub">
      </a>
    </p>
  </div>
</body>
</html>
