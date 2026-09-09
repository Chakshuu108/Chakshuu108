<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:2575fc&height=220&section=header&text=Chakshu%20Gupta&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Turning%20data%20into%20decisions%2C%20one%20model%20at%20a%20time&descAlignY=55&descSize=18" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&duration=2500&pause=800&color=2575FC&center=true&vCenter=true&multiline=true&width=650&height=90&lines=Computer+Engineering+%40+Thapar+Institute;AI%2FML+%C2%B7+Generative+AI+%C2%B7+Data+Science;Currently+training+GANs+to+erase+watermarks+%F0%9F%8E%A8" />

<br/>

<a href="https://linkedin.com/in/YOUR-LINKEDIN">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000"/>
</a>
<a href="https://github.com/Chakshuu108">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=000000"/>
</a>
<a href="https://your-portfolio-link.com">
  <img src="https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=vercel&logoColor=white&labelColor=000000"/>
</a>
<a href="mailto:cgupta_be23@thapar.edu">
  <img src="https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Chakshuu108&label=Profile%20Views&color=6a11cb&style=for-the-badge" />

</div>

<br/>

## 🧬 A Bit About Me

<img align="right" width="320" src="https://raw.githubusercontent.com/aritraroy/aritraroy/master/code.gif" />

- 🎓 B.Tech Computer Engineering, **Thapar Institute of Engineering & Technology** — CGPA `8.40`
- 🔬 Researching **GAN-based watermark removal** under Prof. Deep Maan — paper submitted for peer review, `44.29 dB PSNR` beating baselines
- 📊 Interned as a **Data Scientist @ Evoastra Ventures** — built churn prediction models at `89%` accuracy
- 🧠 Deep into **RAG pipelines, LLMs, and multi-agent systems**
- 🧩 Solved **400+ problems** on LeetCode
- ⚡ Fun fact: I've spent more hours debugging tensors than sleeping

<br clear="right"/>

---

## 🛠️ Tech Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,java,html,css,sql&theme=dark" /><br/><br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" /><br/><br/>
<img src="https://skillicons.dev/icons?i=fastapi,postgres,git,github,vscode,docker&theme=dark" />

</div>

<br/>

<div align="center">

| Domain | Stack |
|---|---|
| 🤖 **AI / ML** | LangChain · LangGraph · Transformers · Feature Engineering · Model Evaluation |
| 📈 **Data Science** | pandas · NumPy · SciPy · EDA · Gradient Boosting |
| 🧵 **Core CS** | DSA · OOP · DBMS · Operating Systems · Computer Networks |
| ⚙️ **Dev Tools** | REST APIs · CI/CD · Streamlit · Jupyter · Google Colab |

</div>

---

## 🚀 Projects Worth a Look

<table>
<tr>
<td width="50%" valign="top">

### 🩺 MediCure-AI
Multi-agent healthcare platform — symptom analysis, risk assessment, real-time clinical alerts, SSE-based streaming.

`FastAPI` `PostgreSQL` `LangGraph` `LangChain`

</td>
<td width="50%" valign="top">

### 🔎 AI Codebase Assistant
RAG pipeline over GitHub repos with semantic code search + automated issue triage using vector similarity.

`n8n` `Gemini Embeddings` `Qdrant`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📉 TrendyFire
End-to-end AI demand forecasting platform — from raw data to automated business reporting.

`Gen AI` `NLP` `Business Intelligence`

</td>
<td width="50%" valign="top">

### 📚 Contextual Doc Search Engine
Custom search engine built on the KMP algorithm — `O(m+n)` pattern matching for blazing-fast queries.

`C++` `Algorithms`

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Chakshuu108&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Chakshuu108&theme=radical&hide_border=true" width="42%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chakshuu108&layout=compact&theme=radical&hide_border=true" width="45%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Chakshuu108&theme=react-dark&hide_border=true" width="90%" />

</div>

---

## 🐍 Live Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Chakshuu108/Chakshuu108/output/github-contribution-grid-snake-dark.svg" width="90%" />

</div>

> ⬆️ This animates automatically once you add the workflow below — it "eats" your contribution graph in real time.

<details>
<summary><b>⚙️ Click to set up the animated snake (one-time, 2 minutes)</b></summary>

<br/>

1. In this repo, go to **Actions → New workflow → set up a workflow yourself**
2. Name the file `snake.yml` and paste:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Chakshuu108
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Commit it, then run it manually once from the **Actions** tab (`Run workflow`)
4. Wait ~30 seconds — the snake SVG above will start rendering and update daily

</details>

---

<div align="center">

### 💭 "Every failed experiment is just a data point I hadn't collected yet."

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2575fc,100:6a11cb&height=150&section=footer" />

</div>
