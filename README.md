# Hi, I'm Samrat BN 👋 <img src="https://media.giphy.com/media/12PA1eI8FBqEUM/giphy.gif" width="30">

<p align="left">
  <a href="https://linkedin.com/in/samratnaarnav">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=36BCF7&vCenter=true&width=600&lines=Co-Founder+%26+Full-Stack+Engineer;Java+%26+Spring+Boot+Specialist;Building+Scalable+SaaS+Solutions" alt="Typing SVG" />
  </a>
</p>

I am an entrepreneurial full-stack software engineer who designs, builds, and deploys scalable web applications[cite: 1]. From architecting robust REST APIs with Spring Boot to configuring secure, on-premise Linux server environments[cite: 1], I enjoy bridging the gap between clean backend code and real-world system infrastructure[cite: 1].

---

### 🎮 Contribution Snake Game (Live Grid Animation)

<!-- This animates your actual GitHub contribution graph into an arcade game -->
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *" # Runs every 12 hours
  workflow_dispatch:
  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: samrat177
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

### 🛠️ Technical Ecosystem

<b style="color: #36BCF7;">Backend Core & Frameworks</b>
<p align="left">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" alt="Hibernate" />
</p>

<b style="color: #36BCF7;">Frontend & UI</b>
<p align="left">
  <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<b style="color: #36BCF7;">Databases, Cloud & Systems</b>
<p align="left">
  <img src="https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

### 🚀 Featured Venture & Impact

🚀 **Co-Founder & Full Stack Developer @ SAMNOX** *(Feb 2026 - Present)*[cite: 1]
* **SaaS Delivery:** Leading a 5-member team engineering localized retail applications (*Namma-Invetro*, *Namma-Angadi*, *Namma-Lekka*) using a Spring Boot backend and React frontend[cite: 1].
* **Edge Deployment:** Architected and maintained an on-premise Linux production environment on a Raspberry Pi, utilizing Cloudflare Tunnels to securely expose web traffic[cite: 1].
* **Scalability:** Optimized server resource allocation using database caching and connection pooling to seamlessly support 50+ concurrent corporate business clients on minimal local hardware[cite: 1].

---

### 🏆 Key Highlights & Metrics

* 💡 **Problem Solving:** Successfully solved **350+ DSA challenges** across LeetCode (200+) and GeeksforGeeks (150+) using Java[cite: 1].
* 🥇 **Awards:** Awarded 1st Prize for developing an **AI-Based Automated Defect Detection System** utilizing Python, OpenCV, and NumPy to automate quality checks with a 92% accuracy rate[cite: 1].
* ☁️ **Certifications:** Completed the **AWS APAC Solutions Architecture** Virtual Experience Program[cite: 1].

---

### 📊 Performance Analytics & Live Activity Graphs

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=samrat177&theme=react-dark&bg_color=0d1117&hide_border=true&area=true" alt="Samrat's Activity Graph" width="100%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=samrat177&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" alt="Samrat's GitHub Stats" height="195px" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=samrat177&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="195px" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=samrat177&theme=tokyonight&hide_border=true" alt="Samrat's GitHub Streak" width="100%" />
</p>

---

### 🌐 Connect With Me

<p align="left">
  <a href="https://linkedin.com/in/samratnaarnav" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:samratnaarnav@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>


