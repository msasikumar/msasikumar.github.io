---
layout: default
title: Home
---
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>{{ page.title | default: site.title }}</title>
<link rel="stylesheet" href="/assets/css/styles.css">
<header>
        <h1>Sasikumar Manickam</h1>
        <p>Senior Manager | Senior Data Engineer | ML | AI | Data Science</p>
</header>
<div class="container">
<nav>
    <a href="#summary">Summary</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#education">Education</a>
    <a href="#certifications">Certifications</a>
    <a href="#contact">Contact</a>
</nav>
        <section id="summary">
            <h2>Summary</h2>
            <p>Welcome to my professional portfolio. I am a Senior Data Engineer with a passion for leveraging data to drive innovation and solve complex challenges.</p>
            <p>Senior Data Engineer with over 15 years of experience architecting and delivering highly scalable and reliable data platforms and products for global organizations like Blue Origin, PepsiCo, and Follett. Expert in Python, Spark, AWS, Snowflake, and Databricks, optimizing ETL/ELT pipelines for web-scale data, improving data processing speeds by up to 10x, and saving millions in costs. Complemented by a Master’s in Predictive Data Analytics and expertise in AI/ML, enabling data-driven insights through predictive modeling.</p>
        </section>
        <section id="skills">
            <h2>Technical Skills</h2>
            <ul>
                <li><strong>Programming:</strong> Python, SQL, Java, R</li>
                <li><strong>Data Engineering:</strong> ETL/ELT, Data Modeling, Data Integration, CI/CD, DBT</li>
                <li><strong>Cloud & Data Platforms:</strong> AWS (Lambda, Kinesis, API Gateway), Kafka, Azure, Snowflake, Databricks, Redshift</li>
                <li><strong>Tools & Methodologies:</strong> Spark, Kubernetes, Informatica, Agile, DevOps</li>
                <li><strong>AI/ML:</strong> Predictive Analytics, Machine Learning, Feature Engineering</li>
            </ul>
        </section>
        <section id="experience">
            <h2>Professional Experience</h2>
            <div class="job">
                <h3>Senior ML/DS/Data Engineer</h3>
                <img src="images/logo_blue_origin.png" width="70px">
                <strong>&nbsp;&nbsp;&nbsp;BLUE ORIGIN, Kent, WA</strong> | DEC 2022 - Present
                <ul>
                    <li>Architected a high-performance data platform using AWS API Gateway, Kinesis, ECS, and Databricks, achieving 99.99% uptime and 5x faster data processing for large-scale hotfire engine datasets, processing 1-2 TB daily.</li>
                    <li>Migrated applications from PostgreSQL to Databricks, optimizing ETL pipelines (Python, Spark, SQL) to improve processing speed by 3x–10x and reduce downtime by 80%.</li>
                    <li>Developed CI/CD pipelines using Python, SQL, and DBT, enabling seamless data integration and real-time analytics.</li>
                    <li>Applied predictive analytics expertise to build a workflow optimization model, reducing inefficiencies by 25% from traditional whitelisting.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Principal, Senior Data and Solutions Architect. AI and Data Platform</h3>
                <img src="images/kinandcarta_logo.jpeg" width="50px">
                <strong>Kin and Carta (Valtech)</strong> | MAR 2021 – DEC 2022
                <p><em>&nbsp;&nbsp;&nbsp;BKin + Carta is a global digital transformation business. As a senior data and solutions architect, I have developed and executed projects for the following clients.</em></p>
                <ul>
                    <li><strong>Northern Trust:</strong> Designed conceptual, logical, and physical data models using ER/Studio, enabling scalable data architectures for the Private Passport program.</li>
                    <li><strong>Herbalife:</strong> Built a self-service data platform on Azure, optimizing data pipelines for high-volume, high-velocity datasets, improving processing efficiency by 40%.</li>
                    <li><strong>PepsiCo:</strong> Architected a real-time data integration system for inventory and order tracking, enhancing data visibility by 30% through robust ETL processes.</li>
                    <li><strong>Corteva:</strong> Re-engineered invoice data workflows by migrating from Kubernetes to AWS Lambda, ensuring real-time data syncing across AWS and Azure.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Senior Manager, Enterprise Data Services</h3>
                <img src="images/adtalemglobaleducation_logo.jpeg" width="50px">
                <strong>&nbsp;&nbsp;&nbsp;ADTALEM Global Education Group, Chicago, IL</strong> | JAN 2018 – FEB 2021
                <ul>
                    <li>Led migration of legacy data warehouse to Snowflake, streamlining ETL processes to save $500K annually and improve data processing efficiency by 60%.</li>
                    <li>Developed data integration services for 50+ sources (e.g., ERP, marketing), leveraging Informatica IICS and Python, with predictive NPS models enhancing student engagement.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Consultant, Development Manager/Architect</h3>
                <img src="images/fresche_solutions_logo.jpeg" width="40px">
                <strong>&nbsp;&nbsp;&nbsp;FRESCHE Solutions Inc., Montreal, Québec (Remote)</strong> | JAN 2017 - JAN 2018
                <ul>
                    <li>As an Architect and Manager of the Development team, I was responsible for completing, modernizing, and digitizing branch operations for ABC Supply Inc. I designed and led a team of eight. Tasks include replacing the legacy fax system and batch EDI with secure web services.</li>
                    <li>Provided a solution for B2B order integration between ABC and retail customers like Home Depot and Lowe's using the Anypoint Platform.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Manager, Application Development (2012–2016); Team Leader, Technical (2010–2012); Senior Programmer Analyst (2004–2010)</h3>
                <img src="images/follett_higher_education_logo.jpeg" width="50px">
                <strong>Follett Corporation, Westchester, IL</strong> | Mar 2004 – Dec 2016
                <ul>
                    <li>Architected a scalable data integration platform for inventory management across 1,400 stores, streamlining ETL processes to save $18M annually in operational costs.</li>
                    <li>Led modernization of legacy systems to web-based data services using SOA, reducing data processing times by 95% for e-commerce and inventory workflows.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Senior Programmer Analyst/Consultant</h3>
                <p><strong>Rapidigm, Inc., Seattle, WA</strong> | 2001 – 2004</p>
                <ul>
                    <li>Designed and implemented data integration solutions for retail and supply chain systems at Starbucks and Boeing, optimizing JDA inventory data pipelines for real-time accuracy.</li>
                </ul>
            </div>

            <div class="job">
                <h3>Programmer Analyst</h3>
                <p><strong>Friendly Advanced Software Technology, Hauppauge, NY</strong> | 1999 – 2001</p>
                <ul>
                    <li>Developed data processing and reporting systems for Schering-Plough, enhancing MRP II data workflows for manufacturing efficiency.</li>
                </ul>
            </div>

            <div class="job">
                <h3>BPCS Analyst/Programmer</h3>
                <p><strong>LINC Software Services, Bangalore, India</strong> | 1996 – 1998</p>
                <ul>
                    <li>Led modernization of legacy systems to web-based data services using SOA, reducing data processing times by 95% for e-commerce and inventory workflows.</li>
                </ul>
            </div>
        </section>
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li><strong><img src="images/depaul_university_logo.jpeg" width="25px">DEPAUL UNIVERSITY, Chicago, Illinois</strong> – Master’s In Predictive Data Analytics (MS)</li>
                <li><img src="images/devry_university_logo.jpeg" width="25px"><strong>DEVRY UNIVERSITY, KELLER SCHOOL OF MANAGEMENT, Chicago, Illinois</strong> – Master Of Business Administration (MBA)</li>
                <li><img src="images/University-of-Chicago-Seal.png" width="50px"><strong>UNIVERSITY OF CHICAGO, GRAHAM/BOOTH SCHOOL OF BUSINESS, Chicago, Illinois</strong> – Graduate Student At Large (GSAL)</li>
                <li><img src="images/RASMUSSEN.jpeg" width="25Px"><strong>RASMUSSEN COLLEGE, Chicago, Illinois</strong> – Business Systems (BS)</li>
                <li><img src="images/PSGCAS.jpg" width="25px"><strong>PSG COLLEGE OF ARTS AND SCIENCE, COIMBATORE, INDIA</strong> – Physics (BS)</li>
            </ul>
        </section>
        <section id="certifications">
            <h2>Certifications & Professional Development</h2>
            <ul>
                <li>Information Technology Executive Development (ITED), 2014</li>
                <li>Certified SCRUM Master, 2015</li>
                <li>Certified Java Developer</li>
                <li>Information Technology Executive Development, 2015</li>
                <li>Diploma in Computing, National Institute of Information Technology (High School Diploma)</li>
            </ul>
            <p><strong>Affiliation:</strong> Toastmasters International</p>
        </section>
        <section id="contact" class="contact-info">
            <h2>Contact</h2>
            <p>You can reach me via email or connect with me on LinkedIn and GitHub:</p>
            <ul>
                <li><strong>Email:</strong> <a href="mailto:msasikumar@gmail.com">msasikumar@gmail.com</a></li>
                <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sasikumarmanickam" target="_blank">linkedin.com/in/sasikumarmanickam</a></li>
                <li><strong>GitHub:</strong> <a href="https://github.com/msasikumar" target="_blank">github.com/msasikumar</a></li>
            </ul>
            <p><strong>Please feel free to reach out via email or connect with me on LinkedIn.</strong></p>
        </section>
    </div>
