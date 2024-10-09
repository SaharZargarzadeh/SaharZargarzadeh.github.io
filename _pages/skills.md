---
layout: archive
title: ""
permalink: /skills/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Ensure content has enough padding at the bottom */
        .content {
            flex: 1;
            padding-bottom: 50px; /* Added bottom padding */
        }
        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
            position: relative; /* Ensure the footer is positioned relative to the content */
            clear: both; /* Clear any floating elements */
            padding: 20px 0; /* Add padding to the footer */
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 24px;
            font-family: 'Georgia', serif;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 20px;
            margin-bottom: 20px;
            position: relative;
        }

        .separator::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        .skills-section {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(4, auto);
            gap: 20px;
            padding: 30px 20px;
            max-width: 1200px;
            margin: auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .item img {
            width: 60px;
            margin-bottom: 15px;
        }

        .item p {
            font-size: 16px;
            margin: 5px 0;
            color: #333;
        }

        .subtext {
            font-size: 14px;
            color: #888;
        }

        /* Footer styling */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #f1f1f1;
            color: #666;
            width: 100%;
            margin-top: auto;
        }

        footer a {
            text-decoration: none;
            color: #1e3d8f;
            font-weight: bold;
        }

        footer a:hover {
            color: #333;
        }

    </style>

<div class="content">
   <!-- Skills Section -->
<div class="separator">Skills</div>
<div class="skills-section">

    

    <div class="item">
        <span>
        <img src="https://img.icons8.com/color/96/000000/python.png" alt="Python Icon">
        <img src=" https://e7.pngegg.com/pngimages/656/766/png-clipart-computer-terminal-computer-icons-bash-others-miscellaneous-angle.png" alt="Python Icon">
        </span>       
        <p>Python, C#, SQL, Bas, Java, MySQL, jQuery, AngularJS</p>
        <p class="subtext">Programming Languages</p>
    </div>

    <div class="item">
        <img src="/images/visual.png" alt="deployment">
        <p>.NET 8, Visual Studio, Google Collab</p>
        <p class="subtext">Deployment</p>
    </div>

    <div class="item">
        <img src="https://w7.pngwing.com/pngs/977/12/png-transparent-responsive-web-design-web-development-bootstrap-html-javascript-world-wide-web-text-trademark-logo.png" alt="Web Development">
        <p>HTML, CSS, Bootstrap, MERN, MEAN</p>
        <p class="subtext">Web Development</p>
    </div>
    
    <div class="item">
        <img src="https://hoffstech.com/wp-content/uploads/2021/08/dockerkubernetes.jpg" alt="Docker Icon">
        <p>Docker, Kubernetes</p>
        <p class="subtext">Container Orchestration</p>
    </div>

    <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/4319/4319147.png" alt="Cloud Icon">
        <p>AWS, AzureDevOps</p>
        <p class="subtext">Cloud Computing</p>
    </div>

    <div class="item">
        <span>
        <img src="\images\ml.jpg" alt="Linux Icon">
        
        </span>
        <p>Nueral Network, Deep learning, NLP, Transformers, LLM</p>
        <p class="subtext">AI Algorithm</p>
    </div>

   

    <div class="item">
        <img src="https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/204141243/original/d11ae65c36ac8119f6969a414afd1462ff16713d/a-database-design-and-integration-using-the-mysql-and-mongodb-database.png" alt="Database Icon">
        <p>MySQL, MongoDB</p>
        <p class="subtext">Databases</p>
    </div>

    <div class="item">
        <img src="https://www.shutterstock.com/image-vector/dlp-data-loss-prevention-acronym-260nw-2401819555.jpg" alt="DLP">
        <p>DLP, MDM</p>
        <p class="subtext">Data Privacy Tools</p>
    </div>

</div>
<footer>
</footer>

