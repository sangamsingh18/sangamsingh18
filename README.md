<div align="center">

<img src="./hero.svg?v=1" width="100%" alt="Sangam Singh animated hero"/>

<img src="./about-life.svg?v=1" width="100%" alt="About Sangam Singh"/>

<img src="./stack.svg?v=1" width="100%" alt="Sangam Singh technology stack"/>

<img src="./id-dashboard.svg?v=1" width="100%" alt="Developer dashboard"/>

</div>

## 🚀 Featured Projects

| Project | Description | Stack |
|---|---|---|
| **Datalytics AI** | Intelligent analytics and AutoML platform with scalable ingestion, model selection and AI-generated insights. | React, FastAPI, Python, Scikit-learn, Groq, MongoDB, Docker |
| **ApnaCoach** | AI mock interviews, ATS resume scoring, assessments, PDF reports and personalized study schedules. | React, Node.js, Groq AI, Firebase, Razorpay |
| **InsightRAG** | Multi-source RAG assistant for GitHub repositories, YouTube transcripts and PDFs with ChromaDB + Supabase. | Python, LangChain, ChromaDB, Supabase, Streamlit, LLaMA 3.3 |
| **SyncTYPE** | Chrome extension that auto-fills college, job and registration forms using rule-based field matching. | JavaScript, Manifest V3, HTML, CSS |

### 🎓 Education & Experience

- **B.Tech — Computer Science & Engineering**, Parul University, 2023–2027 expected, **CGPA 8.15/10**.
- **Admission Assistant & Marketing Intern — Parul University**, Mar 2025–Nov 2025. Processed 100+ applications, built enrollment dashboards and supported outreach.

### 🏆 Certifications

Deloitte Australia Data Analytics Virtual Experience • AWS Academy Cloud Foundations • SQL Intermediate (HackerRank) • Computer Networks and Internet Protocol (NPTEL) • Salesforce Administrator (ADM-201)

### 📊 Coding

**600+ DSA problems** • **1700+ peak LeetCode Contest Rating**

<div align="center">
<img src="./connect.svg?v=1" width="100%" alt="Connect with Sangam"/>

</div>

## 🌃 3D Contribution City

<div align="center">
<img src="./profile-3d-contrib/profile-night-view.svg?v=1" width="100%" alt="3D contribution city"/>
</div>

> **Note:** The supplied resumes do not specify personal hobbies, so the “Beyond Code” panel uses documented interests—problem solving, AI experimentation and developer tooling—instead of inventing hobbies.

### Links

[GitHub](https://github.com/sangamsingh18) · [LinkedIn](https://www.linkedin.com/in/sangam-singh-94a52633b) · [Portfolio](https://sangam18.in) · [Codolio](https://codolio.com/profile/sangam_singh_) · [LeetCode](https://leetcode.com/u/sangam__singh_/) · [Email](mailto:singhsangam1800@gmail.com)

### Automated contribution city

```yaml
# .github/workflows/profile-3d.yml
name: 3D contribution city

on:
  schedule:
    - cron: "0 18 * * *"
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v5
      - uses: yoshi389111/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: sangamsingh18
      - name: Commit generated city
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A
          git commit -m "generated 3d contribution city" || exit 0
          git push
```