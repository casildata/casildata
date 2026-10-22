# Hi, I'm Javier Casildo 👋

**Data Analyst and Data Scientist (M.S. Data Science) with a growing focus on security analytics.**
I work in Python, R, and SQL: cleaning and joining messy data, building models, and explaining results to people who need to act on them.

📍 Dallas, TX &nbsp;·&nbsp; 🎯 Seeking analytics, machine learning, and cybersecurity roles

---

## About Me

I earned an M.S. in Data Science from Texas Tech University and a B.B.A. in Management Information Systems from Angelo State University.

Most of my work experience is in operations, where I learned to use data to fix real problems. At Frito-Lay I owned raw-material forecasting and managed inventory control. Before that, I spent nearly seven years in a regulated medical-device environment (Johnson & Johnson MedTech), where I ran root-cause investigations, supported CAPA initiatives, and kept records audit-ready.

My projects cover the full range of data work: ETL pipelines, SQL data warehouses, statistics, machine learning, and simulation. I'm applying many of those skills to cybersecurity, an area I'm growing into through hands-on training. I'm not an expert in any of these areas yet, and each repo lists its limitations alongside its results.

---

## Current Focus

- 📊 Open to data analyst and data scientist roles
- 📂 Publishing the rest of my portfolio repos
- 🛡️ Completing a Cyber Security Specialist training program, with CompTIA Security+ and CySA+ as my next goals
- 🐍 Doing more of my modeling work in Python, alongside R

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
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## Featured Projects

Each project started as Texas Tech graduate coursework and was rebuilt to run from a clean clone, with results and limitations written down.

### Data Analysis & Engineering

| Project | What it does | Key result | Status |
|---|---|---|---|
| **covid-social-media-etl-pipeline** | Python ETL that joins four public datasets with mismatched keys, grains, and date formats; drops PII before aggregation | Cases and reported anxiety moved together over 27 periods (r = 0.80, not causal); 2026 refactor matches the original outputs exactly | *Coming soon* |
| **nba-star-schema-data-warehouse** | Star-schema warehouse with an ETL pipeline, data-quality checks, and 8 analytic SQL queries | Rejects all 3 planted corrupt rows; 8/8 tests pass | *Coming soon* |

### Data Science & Machine Learning

| Project | What it does | Key result | Status |
|---|---|---|---|
| [**malware-dns-threat-detection-ml**][malware-dns] | Classifies malware from memory-forensics features and flags malicious domains from DNS name features | Malware: 99.4–100% recall on families held out of training. Domains: 17–33% recall at a 1% false-positive budget, with a write-up of why | Public |
| [**email-spam-detection-ml**][spam] | Compares five classifiers and an ensemble for spam filtering | Random forest 94.95% accuracy; found and fixed a data-leakage bug in the kNN model | Public |
| **wine-quality-multivariate-analysis** | PCA, clustering, outlier detection, and discriminant analysis on 6,497 wines | k-means separates red from white with 98.6% agreement; fixes an outlier-rule bug in the original coursework | *Coming soon* |

### Simulation, Optimization & Risk

| Project | What it does | Key result | Status |
|---|---|---|---|
| [**cyber-risk-monte-carlo**][cyber-risk] | Monte Carlo model of annual cyber losses, with control ROI and a Bayesian rate update | Loss exceedance curve, ROI with uncertainty per control, one-page brief for leadership | Public |
| [**soc-alert-triage-simulation**][soc-sim] | Discrete-event simulation of a two-tier security operations team | One more tier-2 analyst cuts confirmed-incident wait from 33.9 to 4.4 minutes | Public |
| [**security-budget-optimizer**][budget-opt] | Mixed-integer program that chooses the security controls that remove the most expected loss for a budget | Verified optimal against all 262,144 combinations | *Coming soon* |

### Security Labs

| Project | What it does | Status |
|---|---|---|
| **security-labs-writeups** | Five course lab write-ups: vulnerability scanning, packet analysis, PKI, web attacks, and host hardening | *Coming soon* |

---

## Certifications & Training

| Credential | Issuer | Date |
|---|---|---|
| Cyber Security Specialist Program | TopTalent Learning | In progress |
| Operating Systems Basics | Cisco Networking Academy | Oct 2026 |
| Computer Hardware Basics | Cisco Networking Academy | Sep 2026 |
| Python for Data Science and AI | IBM | Jun 2023 |
| PCEP – Certified Entry-Level Python Programmer | OpenEDG Python Institute | Jul 2022 |
| QMS Internal Auditor training (ISO 9001 / ISO 13485) | Exemplar Global-certified course | Jan 2020 |
| Network Pro Certification | TestOut | May 2019 |

---

## Education

| Study | Institution | Date |
|---|---|---|
| Master of Science, Data Science | Texas Tech University, Lubbock, TX | May 2022 |
| Certificate in Applied Statistics | Angelo State University, San Angelo, TX | Dec 2020 |
| Bachelor of Business Administration, Management Information Systems (Cum Laude) | Angelo State University, San Angelo, TX | Dec 2019 |

---

## Let's Connect

I'm open to data analyst, data scientist, and entry-level security roles, and I'm glad to talk with people working in any of those areas.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-javiercasildo-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javiercasildo)
[![Email](https://img.shields.io/badge/Email-javier.casildo01%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:javier.casildo01@gmail.com)

<!--
  PROJECT LINKS (not shown on the page)
  When you publish a repo:
    1. Move its line from "Not published yet" up to "Published" (outside this comment).
    2. In the project table, change **repo-name** to [**repo-name**][ref].
    3. Change its Status from "Publishing soon" to "Public".
-->

<!-- Published -->
[malware-dns]:   https://github.com/casildata/malware-dns-threat-detection-ml
[cyber-risk]:    https://github.com/casildata/cyber-risk-monte-carlo
[soc-sim]:       https://github.com/casildata/soc-alert-triage-simulation
[budget-opt]:    https://github.com/casildata/security-budget-optimizer
[spam]:          https://github.com/casildata/email-spam-detection-ml

<!-- Not published yet:
  [covid-etl]:     https://github.com/casildata/covid-social-media-etl-pipeline
  [nba-dw]:        https://github.com/casildata/nba-star-schema-data-warehouse
  [wine]:          https://github.com/casildata/wine-quality-multivariate-analysis
  [security-labs]: https://github.com/casildata/security-labs-writeups
-->
