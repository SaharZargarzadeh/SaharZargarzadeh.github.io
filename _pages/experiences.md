---
layout: archive
title: ""
permalink: /experiences/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Experiences</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #ffffff;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header styles */
        h1, h2, h3, h4, h5, h6 {
            margin: 0 0 0.5em;
            line-height: 1.2;
            font-family: 'Georgia', serif;
            font-weight: bold;
        }

        /* Main content container */
        .content {
            width: 100%; 
            max-width: 1100px;
            margin: 30px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        /* Custom separator for the headline */
        .content h1::after {
            content: '';
            display: block;
            width: 60%;
            height: 2px;
            background-color: #1e3d8f;
            margin-top: 8px;
            margin-left: 0;
        }

        .content h2 {
            font-size: 20px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 15px;
            text-align: center;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        .content p, .content li {
            font-size: 15.5px; /* Ensures consistent font size for all text */
            font-family: 'Georgia', serif; /* Ensure the same font family */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Consistent spacing */
        }

        /* Bullet point formatting */
        ul {
            list-style: disc;
            margin-left: 1px;
        }

        ul li {
            text-align: justify;
            margin-bottom: 10px;
        }

        ul li::marker {
            font-weight: bold;
        }

        /* Experience card container without timeline */
        .experience-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            position: relative;
            padding-left: 0;
        }

        /* Experience card styling */
        .experience-card {
            background-color: #f9f9f9;
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-left: 5px solid #1e3d8f;
            position: relative;
        }

        .experience-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        .experience-card h3 {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 8px;
        }

        .experience-card h4 {
            font-size: 16px;
            font-weight: normal;
            margin-bottom: 8px;
            color: #666;
        }

        .experience-card h5 {
            font-size: 14px;
            color: #999;
            margin-bottom: 6px;
        }

        .experience-card img {
            width: 45px;
            height: 45px;
            object-fit: contain;
            float: right;
            margin-left: 15px;
        }

        .section-header {
            font-size: 16px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 6px;
            border-bottom: 2px solid #cccccc;
            padding-bottom: 3px;
        }

        .section-content {
            font-size: 14px;
            font-family: 'Georgia', serif; /* Ensure this is consistent */
            line-height: 1.6;
            color: #333;
            text-align: justify;
            margin-bottom: 13px; /* Moderate gap between list items */
        }

        /* Links styling */
        a {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:link, a:visited {
            color: #1e3d8f;
            text-decoration: none;
        }

        a:hover, a:active {
            color: #003399;
            text-decoration: none;
        }

        /* Footer styles */
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #333;
            font-family: 'Georgia', serif;
            background-color: #ffffff;
            padding: 20px 0;
            border-top: 1px solid #cccccc;
        }

        footer .separator {
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-bottom: 15px;
        }

        footer .separator::after {
            content: '';
            display: block;
            width: 40px;
            height: 2px;
            background-color: #1e3d8f;
            margin: 10px auto;
        }

        footer .links {
            margin-bottom: 15px;
        }

        footer .links a {
            margin: 0 15px;
            color: #1e3d8f;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }

        footer .links a:hover {
            text-decoration: underline;
        }

        footer .footer-note {
            color: #777;
            font-size: 14px;
        }

    </style>
</head>
<body>

<!-- Professional Experiences Section -->
<div class="content">
    <h2>Academic Experience</h2>
    <div class="separator"></div>

    <!-- Experience cards -->
    <div class="experience-container">

        <!-- Role 1: Design a Power Consumption ML Backdoor Attack in the Spirit of Mirai for IoT devices  -->
        <div class="experience-card">
            <h3>Design a Power Consumption ML Backdoor Attack in the Spirit of Mirai for IoT devices</h3>
            <h4><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a> · Aug 2023 – Present</h4>
            <h5>Texas, USA</h5>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="UTA Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Pioneered a neural adversarial attack strategy targeting AI model vulnerabilities in Deep Learning power side channel classifiers for IoT devices.</li>
                <li> Utilized GANs to generate variations of dummy code in Mirai-infected IoT devices, altering power consumption patterns to cause misclassification and enable a 96% efficient model hijacking process.</li>

                <li>Conducted time series analysis using deep learning models like autoencoders and AI explainability tools to recognize patterns and subsequently trained RNN models for anomaly detection in power consumption data.</li>
            </ul>
        </div>

        <!-- Role 2: Beamforming oriented topology control for mm-Wave networks -->
        <div class="experience-card">
            <h3>Beamforming oriented topology control for mm-Wave networks</h3>
            <h4><a href="https://www.odu.edu" target="_blank">Old Dominion University</a> · Jan 2022 – June 2023</h4> 
            <h5>Virginia, USA</h5>
            <img src="https://www.odu.edu/sites/default/files/logos/univ/png-72dpi/odu-secondary-noidea-fullcolor.png" alt="old dominion university Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li> Developed predictive models for RX throughput in mm-wave systems using supervised learning, simulating 64 Beamforming channels with advanced feature engineering techniques.</li>
        <li> Optimized base station power, reduced beam interference, and improved user grouping strategies, resulting in an 89% performance improvement compared to BOON topology control schemes.</li>
            </ul>
        </div>

        <!-- Role 3: Cooperative spectrum sensing technique CR-VANET -->
        <div class="experience-card">
            <h3>Cooperative spectrum sensing technique CR-VANET</h3>
            <h4><a href="https://www.ui.ac.ir/EN" target="_blank">University of Isfahan</a> May 2018 – Sep 2019</h4> 
            <h5>Isfahan, Iran</h5>
            <img src="/images/University_of_Isfahan_Logo.png" alt="university of Isfahan Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Designed a data-driven consensus algorithm leveraging advanced statistics and machine learning to enhance spectrum sensing accuracy by 98%, optimizing band detection and reducing spectrum handoffs.</li>
                <li>Implemented a consensus-based approach that considered neighboring nodes to further improve spectrum sensing accuracy, minimizing disruptions and enhancing network stability.</li>
            </ul>
        </div>

 <h2>Professional Experience</h2>
    <div class="separator"></div>

        <!-- Role 4: Data Science Developer- Online Registration (ideal for camps, and classes) -->
        <div class="experience-card">
            <h3>Data Science Developer- Online Registration (ideal for camps, and classes)</h3>
            <h4><a href="https://jumbula.com/" target="_blank">Jumbula</a> · Jul 2019 – Sep 2021</h4> 
            <h5>California, USA</h5>
            <img src="/images/jumbula.jpg" alt="Jumbula Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Designed a data-driven online registration system using ASP.NET Core and SQL Server, applying machine learning to analyze user behavior and forecast enrollment trends, enhancing reporting accuracy and resource planning.</li>
                <li>Developed a comprehensive registration system with an intuitive admin dashboard, managing classroom capacities, student rosters, and financial data through ASP.NET Core, integrated with SQL Server.</li>
            </ul>
        </div>

        <!-- Role 5: Software Developer- High-Speed Internet and communication -->
        <div class="experience-card">
            <h3>Software Developer- High-Speed Internet and Communication </h3>
            <h4><a href="http://shop.panaone.com/" target="_blank">Panaone</a> · Mar 2017 – Jul 2019</h4> 
            <h5>Isfahan, Iran</h5>
            <img src="/images/panaone.jpg" alt="panaone Logo">
            <div class="section-header">Responsibilities</div>
            <ul class="section-content">
                <li>Established customer internet service processes using Process Maker and Magento Deployment. Integrated these systems by 92% with a central C# and SQL Server-driven server.</li>
                <li>Developed a C# web application server using Asp.net 3 and SQL Server DB 2018 for an automated telephony system, executing diverse functions.</li>
            </ul>
            
        </div>

    </div>
</div>

<footer>
    <div class="separator"></div>
    <div class="links">
    </div>
    <div class="footer-note">
    </div>
</footer>

</body>
</html>
