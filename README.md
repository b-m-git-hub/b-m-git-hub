# Hi 👋 I'm Bryan McMahon
### CS Student @ UMass Boston 🧑‍💻 | Paramedic 🚑 |  Saltwater Angler 🎣

## Overview

- Check out <a href="https://bryan-mcmahon.com" target="_blank">my portfolio website</a>. Hosted on DigitalOcean with VPS provisioning by **Terraform** and configuration management by **Ansible**.
- I recently built a **Saltwater Fishing Recommendation Web App:** <a href="https://castgrade.com" target="_blank">CastGrade</a>. Learn more about it down below!
- Connect with me on <a href="https://www.linkedin.com/in/bryan-mcmahon1/" target="_blank">LinkedIn</a>

## 🧑‍💻 Tech Stack
   **Languages:** Python • Java • C • JavaScript • SQL • Bash  
   **DevOps & Cloud:** Docker • Terraform • Ansible • GitHub Actions • Nginx • Linux • DigitalOcean • AWS  
   **Frameworks & Databases:** FastAPI • PostgreSQL/PostGIS • Plotly • Dash • Astro

## My Projects

### 🎣 Saltwater Fishing Spot Recommendation Web App: CastGrade
*A mobile-first web app that ranks your saltwater fishing spots based on real-time tides, weather, wind, and lunar data.*

<a href="https://castgrade.com" target="_blank">🌐 **Live Site: CastGrade.com**</a>

- 🧠 **How it Works:** Users input their fishing spot with preferred tides and wind direction. The system pulls live data from multiple APIs and scores each spot for the times you plan to go fishing. Eliminates the need to check multiple different websites for tide and weather information while simultaneously recommending the spots with the best conditions.
- 🛠️ **Infrastructure:** Self-hosted on **DigitalOcean** using **Terraform** and **Ansible** for automated, reproducible deployments.
- ⚙️ **Multi-API Data Pipeline:** Aggregates NOAA tides, Open-Meteo weather, and astral calculations. Weather is updated every 4 hours to ensure it is up to date and accurate. Tide and lunar are updated every 30 days.
- 🐳 **Containerized Deployment:** Multi-container orchestration via **Docker Compose** (FastAPI app, PostgreSQL, Nginx) for isolated, reproducible environments and seamless updates.

**Stack:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/-PostGIS-336791?logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/-Ansible-EE0000?logo=ansible&logoColor=white) ![Nginx](https://img.shields.io/badge/-Nginx-009639?logo=nginx&logoColor=white) ![HTMX](https://img.shields.io/badge/-HTMX-3366CC?logo=htmx&logoColor=white)

### 📝 Portfolio Website — Self-Hosted
*My personal portfolio website hosted on DigitalOcean. Learn more about me and my hobbies.*

<a href="https://bryan-mcmahon.com" target="_blank">🌐 **Live Site: bryan-mcmahon.com**</a>

- 🧑‍🦱 **Infrastructure as Code:** VPS provisioned by **Terraform**, configured via **Ansible** playbooks for reproducible, idempotent deployments on **DigitalOcean**.
- 🤖 **CI/CD Pipeline:** Automated builds and deployments via **GitHub Actions** on every merge.
- 🔒 **Security:** Automated SSL/TLS renewal via **Certbot** as well as security headers to maintain A+ ratings.

**Stack:** ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/-Ansible-EE0000?logo=ansible&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/-DigitalOcean-0080FF?logo=digitalocean&logoColor=white) ![Nginx](https://img.shields.io/badge/-Nginx-009639?logo=nginx&logoColor=white) ![Astro](https://img.shields.io/badge/-Astro-FF5D01?logo=astro&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)

### 📈 S&P 500 Stock Trading Simulator
*A historical S&P 500 stock trading simulator with minute-interval data. Adjust the speed at which data is displayed and pause to analyze more in depth. Get accurate ROI % and total profit.*

<a href="https://bryanm-stock-sim-fcb66641afb1.herokuapp.com/" target="_blank">🌐 **Hosted on Heroku**</a>

- 📊 **Data Pipeline:** Engineered a scraper to process minute-interval stock data for high-frequency candlestick rendering using **pandas**.
- 🐳 **Containerized Application:** **Docker** eliminated environment discrepancies between local development and **Heroku** production hosting.

**Stack:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Dash](https://img.shields.io/badge/-Dash-008AFB?logo=plotly&logoColor=white) ![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?logo=plotly&logoColor=white) ![pandas](https://img.shields.io/badge/-pandas-150458?logo=pandas&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Heroku](https://img.shields.io/badge/-Heroku-430098?logo=heroku&logoColor=white)