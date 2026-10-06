<h1 align="center">Yahya Lababneh</h1>
<p align="center"><b>AI Engineer</b> · ML systems, MLOps & backend<br>Data Science & AI student, Al al-Bayt University (Jordan)</p>

<br>

<h2 align="center">I may not have every skill you need <ins>yet</ins>.</h2>
<p align="center">
  I'll <b>learn</b> it fast, <b>think</b> it through, and <b>deliver it right</b>, every time.
  <br><br>
  <code>learn → think → ship ↺</code>
</p>

<br>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Architecting+MLOps+Pipelines;Building+Ai-sourcing-hub;Tinkering+with+Arduino+%26+ESP32;Developing+Games+in+Godot;Learning+Mandarin+Chinese" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <!-- TODO: swap for your custom domain once it's live -->
  <a href="https://srv1436161.hstgr.cloud">
    <img src="https://img.shields.io/badge/Portfolio-1A1A16?style=for-the-badge&logo=googlechrome&logoColor=F2EFE6" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/yahia-lababenah-854b90293">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:yahyalababenah@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

I build ML systems end to end: from requirements and architecture to deployment, monitoring and documentation.
The full story behind each project lives on my [portfolio](https://srv1436161.hstgr.cloud); this page is where the code is.

---

### Projects

**🩺 OmniDiag** · Explainable clinical decision support
<!-- TODO: add repo link -->
[Live demo](https://omnidiag-delta.vercel.app)

Built around the full model lifecycle rather than a single trained model: every prediction carries its SHAP explanation, models are versioned in an MLflow registry, and the service logs predictions and exposes Prometheus metrics with drift monitoring.
`FastAPI` `PostgreSQL` `Celery` `Redis` `Docker` `MLflow` `SHAP` `XGBoost`

**📦 AI-Sourcing Hub** · B2B sourcing platform, China → MENA
<!-- TODO: add repo link -->
[Live demo](https://ai-sourcing-agent-sigma.vercel.app)

Backend and architecture for a sourcing platform that turns supplier files into structured catalogs. The LLM extraction chain uses fallback and circuit-breaker logic so one failing provider doesn't take the pipeline down.
`FastAPI` `PostgreSQL` `Celery` `Redis` `Docker` `PaddleOCR` `LLMs`

**💪 sEMG Gesture Classification** · Research toward prosthetic control
<!-- TODO: add repo link -->

Traced poor results back to a 20 Hz sampling rate below the EMG band and rebuilt acquisition at 500 Hz. Then audited my own pipeline, found leakage from overlapping windows and random splits, and moved to leave-one-subject-out evaluation. The repo documents what failed and why.
`Python` `XGBoost` `Optuna` `PyTorch` `Arduino`

---

### How I build

- **Explainability is part of the design**, not something added after the model works.
- **I audit my own results** before anyone else has to.
- **A model isn't done until it's deployed and observable**: logged, versioned, monitored.
- **Documentation is part of the work**, so the next person understands the decisions, not just the code.

---

### 🛠 Tech Stack

**🧠 Machine Learning, MLOps & Data Science**
<p align="left">
  <img src="https://skillicons.dev/icons?i=py,pytorch,r,sklearn,mysql" />
  <br>
  <img src="https://img.shields.io/badge/XGBoost-172B4D?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/TabNet-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Optuna-254A61?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SHAP_(XAI)-005571?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/PaddleOCR-0062B0?style=for-the-badge&logo=paddlepaddle&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/MLOps-FF8243?style=for-the-badge&logo=linux&logoColor=white" />
</p>

**⚙️ Backend & Infrastructure**
<p align="left">
  <img src="https://skillicons.dev/icons?i=fastapi,postgres,redis,docker,linux" />
  <br>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/YAML_Config-CB171E?style=for-the-badge&logo=yaml&logoColor=white" />
</p>

**🌐 Web & Automation**
<p align="left">
  <img src="https://skillicons.dev/icons?i=nextjs,ts,js,tailwind,git,github,vscode" />
  <br>
  <img src="https://img.shields.io/badge/RPA_UiPath-FA4616?style=for-the-badge&logo=uipath&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white" />
</p>

**🤖 Robotics, Embedded & Game Dev**
<p align="left">
  <img src="https://skillicons.dev/icons?i=cpp,arduino,ros,godot" />
  <br>
  <img src="https://img.shields.io/badge/Embedded_Systems-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Hardware_Tinkering-FFB900?style=for-the-badge&logo=microbit&logoColor=white" />
</p>

---

### 📊 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=yahyalababenah&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=F2EFE6&title_color=2C5F7C&text_color=1A1A16&icon_color=A8442A" alt="GitHub Stats" />
  <img height="165" src="./github-metrics.svg" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yahyalababenah&hide_border=true&background=F2EFE6&ring=2C5F7C&fire=A8442A&currStreakNum=1A1A16&sideNums=1A1A16&currStreakLabel=2C5F7C&sideLabels=1A1A16&dates=6B6B63&stroke=D8D3C4&cache_bypass=1" alt="GitHub Streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=yahyalababenah&bg_color=F2EFE6&color=1A1A16&line=2C5F7C&point=A8442A&area=true&area_color=2C5F7C&title_color=2C5F7C&hide_border=true" alt="Contribution Graph" />
</p>

### 🏆 Achievements

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=yahyalababenah&theme=flat&no-frame=true&no-bg=true&margin-w=8&column=7" alt="GitHub Trophies" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yahyalababenah&label=Profile+views&color=2C5F7C&style=flat-square" alt="Profile views" />
</p>
