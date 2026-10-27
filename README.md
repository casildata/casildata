# Hi, I'm Javier Casildo 👋

**Data Analyst and Data Scientist (M.S. Data Science) with a growing focus on security analytics.**
I work in Python, R, and SQL: cleaning and joining messy data, building models, and explaining results to people who need to act on them.

📍 Dallas, TX

---

## About Me

I earned an M.S. in Data Science from Texas Tech University and a B.B.A. in Management Information Systems from Angelo State University.

Most of my work experience is in operations, where I learned to use data to fix real problems. At Frito-Lay, I owned raw-material forecasting and site-wide ordering; I also managed inventory analytics and accounting. Before that, I spent nearly seven years in a regulated medical-device environment (Johnson & Johnson MedTech), where I conducted root-cause investigations, supported CAPA initiatives, and kept records audit-ready.

My projects cover the full range of data work: ETL pipelines, SQL data warehouses, statistics, machine learning, and simulation. I'm applying many of those skills to cybersecurity, through hands-on simulation and private home labs with virtual machines. My projects are highlighted below and each repo lists its results alongside limitations.

---

## Current Focus

- 📊 Open to data analyst and data scientist roles
- 📂 Publishing portfolio repos
- 🛡️ Completing a Cyber Security Specialist program
  - CompTIA Security+, Linux+, and Cybersecurity Analyst (CySA+)
  - EC-Council Certified Ethical Hacker (CEH)
  - Systems Security Certified Practitioner (SSCP)
- 🐍 Doing modeling work in Python and R

---

## Technical Skills

| Area | What I've actually used it for |
|---|---|
| **Python** | ETL with pandas, report automation, anomaly-flagging scripts at work, a mixed-integer optimization model |
| **SQL** | Star-schema data warehouse with CTEs and window functions (SQLite, MySQL) |
| **R** | ML classifiers (caret, glmnet, random forests), multivariate analysis, Monte Carlo and Bayesian models, simulation |
| **Data Analysis** | Exploratory analysis, data cleaning and validation, KPI reporting, dashboards for non-technical audiences |
| **Statistics** | Regression, hypothesis testing, PCA, clustering, factor analysis, Monte Carlo simulation |
| **Machine Learning** | Classification, feature engineering, cross-validation, catching data leakage, choosing metrics that fit the problem |
| **Cybersecurity** | VM labs with Nmap, Nessus, Wireshark, and DVWA; malware and malicious-domain detection; cyber risk quantification |
| **Git / GitHub** | Version control, releases, and GitHub Actions CI on my published repos |
| **Linux** | Shell basics and working with log files (Cisco Networking Academy) |
| **VS Code** | My main editor for Python work |

---

## Technologies & Tools

**Languages:** Python · SQL · R  
**Data & ML:** pandas · NumPy · SciPy · tidyverse · caret · Jupyter  
**Databases:** SQLite · MySQL  
**Visualization:** Tableau · Qlik · Power BI (working knowledge) · Excel · matplotlib · ggplot2  
**Security (course labs and training):** Nmap · Nessus · Wireshark · DVWA  
**Workflow:** Git · GitHub Actions · VS Code · Linux shell · pytest · testthat

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## Featured Projects

Some projects started as Texas Tech graduate coursework and were rebuilt to run from a clean clone. Each project comes with results, limitations, and improvement opportunities.

### Data Analysis & Data Modeling

<table>
  <thead>
    <tr>
      <th width="20%" align="left">Project</th>
      <th width="40%" align="left">What it does</th>
      <th width="40%" align="left">Key result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/casildata/covid-social-media-etl-pipeline"><b>covid-social-media-etl-pipeline</b></a></td>
      <td>Python ETL that joins four public datasets with mismatched keys, grains, and date formats; drops PII before aggregation</td>
      <td>Cases and reported anxiety moved together over 27 periods (r = 0.80, not causal); 2026 refactor matches the original outputs exactly</td>
    </tr>
    <tr>
      <td><b>nba-star-schema-data-warehouse</b></td>
      <td>Star-schema warehouse with an ETL pipeline, data-quality checks, and 8 analytic SQL queries</td>
      <td>Rejects all 3 planted corrupt rows; 8/8 tests pass</td>
    </tr>
  </tbody>
</table>

### Data Science & Machine Learning

<table>
  <thead>
    <tr>
      <th width="20%" align="left">Project</th>
      <th width="40%" align="left">What it does</th>
      <th width="40%" align="left">Key result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/casildata/malware-dns-threat-detection-ml"><b>malware-dns-threat-detection-ml</b></a></td>
      <td>Classifies malware from memory-forensics features and flags malicious domains from DNS name features</td>
      <td>Malware: 99.4–100% recall on families held out of training. Domains: 17–33% recall at a 1% false-positive budget, with a write-up of why</td>
    </tr>
    <tr>
      <td><a href="https://github.com/casildata/email-spam-detection-ml"><b>email-spam-detection-ml</b></a></td>
      <td>Compares five classifiers and an ensemble for spam filtering</td>
      <td>Random forest 94.95% accuracy; found and fixed a data-leakage bug in the kNN model</td>
    </tr>
    <tr>
      <td><a href="https://github.com/casildata/wine-quality-multivariate-analysis"><b>wine-quality-multivariate-analysis</b></a></td>
      <td>PCA, clustering, outlier detection, and discriminant analysis on 6,497 wines</td>
      <td>k-means separates red from white with 98.6% agreement; fixes an outlier-rule bug in the original coursework</td>
    </tr>
  </tbody>
</table>

### Applied AI & Tools

<table>
  <thead>
    <tr>
      <th width="20%" align="left">Project</th>
      <th width="40%" align="left">What it does</th>
      <th width="40%" align="left">Key result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/casildata/autoflashcards"><b>autoflashcards</b></a></td>
      <td>Python command-line tool that turns lecture PDFs and Markdown notes into Anki flashcard decks: layout-aware PDF parsing, five extraction rules, and an optional Claude or local Llama stage with prompt-injection defenses</td>
      <td>Rules alone: 100% precision, 80% recall on 35 hand-written gold cards. With Claude Haiku: 94% recall at 86% precision. No card obeyed a hidden prompt injection</td>
    </tr>
  </tbody>
</table>

### Simulation, Optimization, & Risk

<table>
  <thead>
    <tr>
      <th width="20%" align="left">Project</th>
      <th width="40%" align="left">What it does</th>
      <th width="40%" align="left">Key result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/casildata/cyber-risk-monte-carlo"><b>cyber-risk-monte-carlo</b></a></td>
      <td>Monte Carlo model of annual cyber losses, with control ROI and a Bayesian rate update</td>
      <td>Loss exceedance curve, ROI with uncertainty per control, one-page brief for leadership</td>
    </tr>
    <tr>
      <td><a href="https://github.com/casildata/soc-alert-triage-simulation"><b>soc-alert-triage-simulation</b></a></td>
      <td>Discrete-event simulation of a two-tier security operations team</td>
      <td>One more tier-2 analyst cuts confirmed-incident wait from 33.9 to 4.4 minutes</td>
    </tr>
    <tr>
      <td><a href="https://github.com/casildata/security-budget-optimizer"><b>security-budget-optimizer</b></a></td>
      <td>Mixed-integer program that chooses the security controls that remove the most expected loss for a budget</td>
      <td>Verified optimal against all 262,144 combinations</td>
    </tr>
  </tbody>
</table>

### Security Labs

<table>
  <thead>
    <tr>
      <th width="20%" align="left">Project</th>
      <th width="40%" align="left">What it does</th>
      <th width="40%" align="left">Key result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>security-labs-writeups</b></td>
      <td>Five course lab write-ups: vulnerability scanning, packet analysis, PKI, web attacks, and host hardening</td>
      <td><i>Coming soon</i></td>
    </tr>
  </tbody>
</table>

---

## Certifications & Training

<table width="100%">
  <thead>
    <tr>
      <th width="45%" align="left">Credential</th>
      <th width="40%" align="left">Issuer</th>
      <th width="15%" align="left">Date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Cyber Security Specialist Program</td>
      <td>TopTalent Learning</td>
      <td>In progress</td>
    </tr>
    <tr>
      <td>Operating Systems Basics</td>
      <td>Cisco Networking Academy</td>
      <td>Oct 2026</td>
    </tr>
    <tr>
      <td>Computer Hardware Basics</td>
      <td>Cisco Networking Academy</td>
      <td>Sep 2026</td>
    </tr>
    <tr>
      <td>Python for Data Science and AI</td>
      <td>IBM</td>
      <td>Jun 2023</td>
    </tr>
    <tr>
      <td>PCEP – Certified Entry-Level Python Programmer</td>
      <td>OpenEDG Python Institute</td>
      <td>Jul 2022</td>
    </tr>
    <tr>
      <td>QMS Internal Auditor training (ISO 9001 / ISO 13485)</td>
      <td>Exemplar Global-certified course</td>
      <td>Jan 2020</td>
    </tr>
    <tr>
      <td>Network Pro Certification</td>
      <td>TestOut</td>
      <td>May 2019</td>
    </tr>
  </tbody>
</table>

---

## Education

<table width="100%">
  <thead>
    <tr>
      <th width="45%" align="left">Study</th>
      <th width="40%" align="left">Institution</th>
      <th width="15%" align="left">Date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Master of Science, Data Science</td>
      <td>Texas Tech University, Lubbock, TX</td>
      <td>May 2022</td>
    </tr>
    <tr>
      <td>Certificate in Applied Statistics</td>
      <td>Angelo State University, San Angelo, TX</td>
      <td>Dec 2020</td>
    </tr>
    <tr>
      <td>Bachelor of Business Administration, Management Information Systems (Cum Laude)</td>
      <td>Angelo State University, San Angelo, TX</td>
      <td>Dec 2019</td>
    </tr>
  </tbody>
</table>

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-javiercasildo-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javiercasildo)
[![Email](https://img.shields.io/badge/Email-javier.casildo01%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:javier.casildo01@gmail.com)

<!--
  PROJECT LINKS (not shown on the page)
  When you publish a repo:
    1. Move its line from "Not published yet" up to "Published" (outside this comment).
    2. In the project table, wrap <b>repo-name</b> in <a href="https://github.com/casildata/repo-name">...</a>.
-->

<!-- Published -->
[malware-dns]:   https://github.com/casildata/malware-dns-threat-detection-ml
[cyber-risk]:    https://github.com/casildata/cyber-risk-monte-carlo
[soc-sim]:       https://github.com/casildata/soc-alert-triage-simulation
[budget-opt]:    https://github.com/casildata/security-budget-optimizer
[spam]:          https://github.com/casildata/email-spam-detection-ml
[wine]:          https://github.com/casildata/wine-quality-multivariate-analysis
[covid-etl]:     https://github.com/casildata/covid-social-media-etl-pipeline
[autoflashcards]: https://github.com/casildata/autoflashcards

<!-- Not published yet:
  [nba-dw]:        https://github.com/casildata/nba-star-schema-data-warehouse
  [security-labs]: https://github.com/casildata/security-labs-writeups
-->
