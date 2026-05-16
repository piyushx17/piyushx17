<div align="center">

```
██████╗ ██╗██╗   ██╗██╗   ██╗███████╗██╗  ██╗
██╔══██╗██║╚██╗ ██╔╝██║   ██║██╔════╝██║  ██║
██████╔╝██║ ╚████╔╝ ██║   ██║███████╗███████║
██╔═══╝ ██║  ╚██╔╝  ██║   ██║╚════██║██╔══██║
██║     ██║   ██║   ╚██████╔╝███████║██║  ██║
╚═╝     ╚═╝   ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝
```

# Piyush Pandey
### AI Full Stack Developer · Builder · Footballer

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=AI+Developer+%40+Antbox;Full+Stack+Engineer;ML+Pipeline+Builder;32%2C000+Users+%26+Zero+Crashes;RedBull+Four2Score+Finalist+⚽)](https://git.io/typing-svg)

<img src="https://komarev.com/ghpvc/?username=piyushx17&style=for-the-badge&color=0e75b6" alt="Profile Views"/>

</div>

---

## `> whoami`

```python
class Piyush:
    name        = "Piyush Pandey"
    location    = "Bhubaneswar, India 🇮🇳"
    university  = "KIIT University — B.Tech CSE (2023–2027)"
    gpa         = "7.8 / 10"
    current     = "AI Developer Intern @ Antbox"
    building    = ["LLM products", "RAG pipelines", "things that actually scale"]
    contact     = "piyushoffical.r@gmail.com"

    def life_philosophy(self):
        return "Ship fast. Think deep. Play harder. ⚽"
```

---

## `> tech_stack --all`

<div align="center">

**AI & LLM**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6B6B?style=for-the-badge)

**ML & Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Full Stack**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Data & BI**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

</div>

---

## `> ls projects/`

### 🏗️ CampusCore — Academic Management Platform
> *The infrastructure KIIT never had. So I built it.*

```
Scale: 32,000+ simultaneous users
Stack: React.js · Node.js · PostgreSQL · Socket.io
Status: 🟢 Production Live
```

**The Problem:** KIIT had no central system. Section swaps happened on WhatsApp. Attendance tracking was manual chaos. 32,000 students, zero tooling.

**What I Built:**
- 🤖 **AI-powered roll number parser** — automated what used to be done by hand
- 🔁 **Smart section-swap matchmaking** — paired students who wanted to swap sections, automatically
- ⚠️ **Real-time attendance risk calculator** — flags students before it's too late
- ⚡ **Queue-based atomic row-level DB locking** — 32,000 users hit the system simultaneously on allocation day. Zero race conditions. Zero crashes. Not once.

> The hardest part wasn't the features. It was making it not fall over when everyone showed up at once.

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/YOUR-USERNAME/campuscore)
[![Live](https://img.shields.io/badge/Live_Demo-00C853?style=for-the-badge&logo=vercel)](https://YOUR-CAMPUSCORE-LIVE-URL.com)

---

### ⚽ FIFA Player Market Value Predictor
> *Can a model scout better than a human? Let's find out.*

```
Dataset: 2,800 FIFA players · 6 value classes
Accuracy: 84.9% cross-validated
Stack: Python · scikit-learn · SMOTE · Streamlit
```

**What I did:**
- Built a 6-class market value classifier from scratch
- Solved class imbalance using **SMOTE** — expanded dataset from 2,240 → 6,012 samples
- Benchmarked **6 classifiers** via GridSearchCV (Random Forest, Gradient Boosting, SVM, and more)
- Deployed a **Streamlit scouting UI** — non-technical users can predict player value instantly
- Key predictors discovered: **Overall Rating, Age, Goals per Match**

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/YOUR-USERNAME/fifa-predictor)
[![Live App](https://img.shields.io/badge/Live_App-FF4B4B?style=for-the-badge&logo=streamlit)](https://YOUR-FIFA-APP.streamlit.app)

---

### 📺 Netflix Content Analysis Dashboard
> *8,000+ titles. One dashboard. Every answer.*

```
Dataset: 8,000+ Netflix titles
Stack: Power BI · DAX · Power Query
```

**What I built:**
- Interactive Power BI dashboard covering genre trends, country-wise production, rating distributions
- 10+ custom DAX measures with dynamic slicers for deep-dive filtering
- Designed for storytelling — every visual answers a real business question

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/YOUR-USERNAME/netflix-dashboard)

---

## `> cat experience.log`

### 🤖 Antbox — AI Developer Intern *(May 2026 – Present)*

Building LLM-integrated products at the frontier of what AI can do in production:
- Architecting **RAG pipelines** and agentic workflows using Claude, Claude Code, and Claude Cowork
- Automating code generation and intelligent task pipelines for real products
- Designing and shipping **AI pipeline architectures** in cross-functional team environments

### 📊 Deloitte Australia — Data Analytics Virtual Intern *(Nov 2025)*
*(via Forage)*
- Applied real analytical methods on enterprise datasets
- Performed anomaly detection and forensic business reporting
- The kind of work that actually shows up in boardrooms

---

## `> cat certifications.txt`

```
✅  100 Days of Code: Complete Python Pro Bootcamp         — Udemy
✅  Mastering DSA in C & C++                               — Udemy
✅  Data Analysis: SQL, Tableau, Power BI, Excel           — Udemy
```

---

## `> cat life_outside_the_terminal.sh`

```bash
#!/bin/bash
# Warning: this section is not optional. It's the most important part.

echo "Some people close the laptop and scroll. I lace up and run."
```

### ⚽ Football — Not a Hobby. A Discipline.

I don't just play football. I've **competed** — and earned it.

| Tournament | Achievement |
|---|---|
| 🏟️ Bhubaneswar League | Represented KIIT |
| 🎓 AIU Games | University-level national competition |
| 🇮🇳 Khelo India | National platform. Real stakes. |
| 🐂 **RedBull Four2Score** | **Finalist** — one of the most competitive street football tournaments in India |

> RedBull Four2Score isn't a college tournament. It draws serious players. Making the finals means something.

Football taught me what no classroom could:
- How to **perform under pressure** when it actually matters
- How to **read a system** and find gaps in it (sounds like debugging, right?)
- That **consistency beats talent** when talent doesn't show up

The same mindset I carry into code — stay calm, find the opening, execute.

---

### 🎙️ Model United Nations — From Delegate to Architect

MUN taught me to argue a position I might not agree with, with data, under time pressure, in front of a room. Sound familiar? That's basically every technical design meeting.

| Conference | Role / Award |
|---|---|
| KIITMUN 2023 | Verbal Mention |
| HITMUN 2024 | **Special Mention** |
| KIITMUN 2025 | **Team Academics Lead** — built the academic framework for the entire conference |

By 2025 I wasn't just competing. I was designing the system others competed in.

---

## `> cat github_stats.md`

<div align="center">

![Piyush's GitHub Stats](https://github-readme-stats.vercel.app/api?username=piyushx17&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=piyushx17&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=piyushx17&theme=tokyonight&hide_border=true)

</div>

---

## `> ping me`

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:piyushoffical.r@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/piyushx17)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://YOUR-PORTFOLIO.com)

---

*"I build things that hold under pressure — in code and on the pitch."*

**— Piyush Pandey**

</div>
