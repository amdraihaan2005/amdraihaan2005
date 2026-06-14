<div align="center">

# <code>MOHAMMED RAIHAAN ARIF</code>
## <i>Full Stack Engineer | AWS, React, Node.js | Exploring AI Engineering</i>

Final-year Computer Science Engineering student focused on building and deploying full-stack web applications using React, Next.js, Node.js, PostgreSQL, and AWS. 
Interested in AI Engineering and cloud-native application development.

<p align="center">
  <a href="https://linkedin.com/in/mohammedraihaan2005" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/amdraihaan2005" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:amdraihaan@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>

---

### Deployed Project

<table width="100%" cellpadding="20" cellspacing="0" border="0">
  <tr>
    <td bgcolor="#0d1117" style="border: 1px solid #30363d; border-radius: 6px; padding: 24px;">
      <h3 style="margin-top: 0; margin-bottom: 12px; border-bottom: none;">
        📌 <a href="https://github.com/amdraihaan2005/workflo">WorkFlo — Project Management Platform</a>
      </h3>
      <p style="color: #8b949e; font-style: italic; margin-bottom: 16px;">
        A full-stack, lightweight project management workspace specifically built for small-scale teams to eliminate workflow friction and enhance collaborative efficiency.
      </p>
      <ul style="margin-bottom: 20px; padding-left: 20px; line-height: 1.6;">
        <li>Designed a cost-efficient AWS deployment architecture by co-hosting Express.js and PostgreSQL on a single EC2 instance, eliminating the need for AWS RDS costs. To operate reliably under single EC2 instance RAM constraints, migrated the backend runtime to Node.js v20 and set a baseline memory usage for API processes reducing memory consumption by 25%, preserving 150–200 MB for uninterrupted PostgreSQL and caching processes and preventing potential Linux OOM failures.
</li>
        <li>Optimized client-server data transfer and infrastructure load by integrating Redux Toolkit Query Caching, reducing redundant API requests traffic by ~40% (~20 to ~12) by implementing tag-based request invalidation and global state management, significantly reducing navigation latency and allowing a flicker-free UI experience for end-users.</li>
        <li>Improved application reliability by configuring PM2 process clustering and automated restart policies on AWS EC2, enabling failed backend processes to recover automatically after unexpected crashes, maintaining a 99.9% observed uptime during deployment, eliminating the need for manual intervention and reduced the risk of prolonged service interruptions for active users.</li>
        <li>Reduced operational burden on the primary AWS EC2 server by externalizing authentication through AWS Cognito and hosting the Next.js frontend on AWS Amplify. Established a Git-triggered CI/CD pipeline that accelerated release cycles by 86% (15 minutes to under 2 minutes), enabling faster feature delivery and bug-fix rollouts for end users.</li>
      </ul>
      <div style="margin-top: 20px;">
        <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=nextdotjs&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Node.js-green?style=for-the-badge&logo=node.js&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Express.js-black?style=for-the-badge&logo=express&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge&logo=postgresql&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/AWS_EC2-orange?style=for-the-badge&logo=aws&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/PM2-purple?style=for-the-badge&logo=pm2&logoColor=white" />
      </div>
    </td>
  </tr>
</table>

---

### Past Projects

<table width="100%" cellpadding="15" cellspacing="10" border="0">
  <tr>
    <td width="50%" valign="top" bgcolor="#0d1117" style="border: 1px solid #30363d; border-radius: 6px; padding: 20px;">
      <h4 style="margin-top: 0; margin-bottom: 10px; border-bottom: none; text-align: center;"> 🔷 Ethical Workload Admission Control System</h4>
      <p style="color: #8b949e; font-size: 14px; margin-bottom: 12px; min-height: 40px; text-align: center;">Developed a policy-driven cloud workload admission framework in Java using CloudSim to filter and regulate workloads before VM scheduling and execution.</p>
      <ul style="padding-left: 18px; font-size: 13px; line-height: 1.5; margin-bottom: 16px;">
        <li>Built a custom EthicalBroker to classify workloads and automatically reject restricted tasks (e.g., crypto-mining or surveillance) while scheduling legitimate jobs.</li>
        <li>Implemented configurable admission logic, audit logging, and real-time telemetry monitoring via a Java Swing analytical dashboard.</li>
      </ul>
      <div style="text-align: center; margin-top: auto;">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/CloudSim-gray?style=flat-square" />&nbsp;
        <img src="https://img.shields.io/badge/Swing-blue?style=flat-square" />&nbsp;
      </div>
    </td>
    <td width="50%" valign="top" bgcolor="#0d1117" style="border: 1px solid #30363d; border-radius: 6px; padding: 20px;">
      <h4 style="margin-top: 0; margin-bottom: 10px; border-bottom: none; text-align: center;">🔷 Plagiarism Detection Model — Research Project</h4>
      <p style="color: #8b949e; font-size: 14px; margin-bottom: 12px; min-height: 40px; text-align: center;">Developed a plagiarism detection system in Python to identify similar and duplicated textual content across documents.</p>
      <ul style="padding-left: 18px; font-size: 13px; line-height: 1.5; margin-bottom: 16px;">
        <li>Built a text-analysis pipeline using tokenization, n-gram comparison, and similarity scoring to detect overlapping sentence structures.</li>
        <li>Implemented text preprocessing and filtering modules, optimizing comparison routines to handle large text datasets efficiently.</li>
        <li>Evaluated the pipeline on academic datasets, demonstrating high detection accuracy for verbatim copies and paraphrased text.</li>
      </ul>
      <div style="text-align: center; margin-top: auto;">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/NLTK-blue?style=flat-square" />&nbsp;
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" bgcolor="#0d1117" style="border: 1px solid #30363d; border-radius: 6px; padding: 20px;">
      <h4 style="margin-top: 0; margin-bottom: 10px; border-bottom: none; text-align: center;">🔷 Stock Price Prediction & Analysis Dashboard</h4>
      <p style="color: #8b949e; font-size: 14px; margin-bottom: 12px; min-height: 40px; text-align: center;">Developed a web-based financial analytics dashboard in Python using Flask and Keras/TensorFlow to analyze historical market data and predict future stock price trends.</p>
      <ul style="padding-left: 18px; font-size: 13px; line-height: 1.5; margin-bottom: 16px;">
        <li>Built a Flask web app that downloads stock datasets via yfinance and displays historical statistics along with 20, 50, 100, and 200-day EMAs.</li>
        <li>Integrated a pre-trained Keras deep learning model (.h5) to predict price trends using a rolling 100-day sliding window.</li>
        <li>Generated dynamic visual charts using Matplotlib to overlay trend lines and predictions, enabling direct CSV data downloads.</li>
      </ul>
      <div style="text-align: center; margin-top: auto;">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" />&nbsp;
      </div>
    </td>
    <td width="50%" valign="top" bgcolor="#0d1117" style="border: 1px solid #30363d; border-radius: 6px; padding: 20px;">
      <h4 style="margin-top: 0; margin-bottom: 10px; border-bottom: none; text-align: center;">🔷 Travela - Hotel Recommendation App</h4>
      <p style="color: #8b949e; font-size: 14px; margin-bottom: 12px; min-height: 40px; text-align: center;">Developed a desktop hotel recommendation app focused on personalized travel discovery using dynamic user preference filtering.</p>
      <ul style="padding-left: 18px; font-size: 13px; line-height: 1.5; margin-bottom: 16px;">
        <li>Developed a recommendation engine in Python that filters hotel suggestions based on user budget, ratings, and location preferences.</li>
        <li>Integrated a relational SQL storage layer to maintain fast query execution during large-scale sorting and multi-parameter searches.</li>
        <li>Created an interactive desktop GUI using Tkinter, enabling seamless user inputs and easy navigation.</li>
      </ul>
      <div style="text-align: center; margin-top: auto;">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Tkinter-blue?style=flat-square" />&nbsp;
      </div>
    </td>
  </tr>
</table>

---

### Data Science & Analytics Case Studies

<table width="100%" cellpadding="20" cellspacing="0" border="0">
  <tr>
    <td bgcolor="#0d1117"
        style="border: 1px solid #30363d;
               border-radius: 6px;
               padding: 24px 24px 32px 24px;">
      <h3 style="margin-top: 0; margin-bottom: 12px; border-bottom: none;">
        🔷 Dynamic Pricing & Revenue Optimization for Hotels & Flights
      </h3>
      <p style="color: #8b949e; font-style: italic; margin-top: 0; margin-bottom: 16px;">
        Built a financial analytics system in Python using Machine Learning and SQL to optimize flight schedules, transport pricing datasets, and hospitality inventories.
      </p>
      <ul style="padding-left: 20px; line-height: 1.6; margin-top: 0; margin-bottom: 24px;">
        <li>Resolved class imbalance in booking datasets by applying SMOTE oversampling to improve data preprocessing quality.</li>
        <li>Trained Random Forest models to predict booking lead times and inventory constraints, achieving a 98% F1-score.</li>
        <li>Analyzed pricing trends using SQL and designed Tableau dashboards to deliver dynamic competitive pricing insights.</li>
      </ul>
      <div style="text-align: center; margin-top: 0;">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />&nbsp;
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
      </div>
    </td>
  </tr>
</table>

---

<div align="center">

### Core Competencies

#### Full Stack: Front-end
<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux Toolkit" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white" alt="Material UI" />
</p>

#### Full Stack: Back-end
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/REST_APIs-0052CC?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-123A50?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma ORM" />
</p>

#### Cloud and Deployment
<p align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS EC2" />
  <img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="AWS S3" />
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white" alt="AWS Lambda" />
  <img src="https://img.shields.io/badge/AWS_Amplify-FF9900?style=for-the-badge&logo=aws-amplify&logoColor=white" alt="AWS Amplify" />
  <img src="https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white" alt="AWS RDS" />
  <img src="https://img.shields.io/badge/AWS_Cognito-FF9900?style=for-the-badge" alt="AWS Cognito" />
  <img src="https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white" alt="PM2" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/pgAdmin-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgAdmin" />
</p>

#### AI and Data Science
<p align="center">
  <img src="https://img.shields.io/badge/ETL-blueviolet?style=for-the-badge" alt="ETL" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" alt="Matplotlib" />
</p>

</div>
