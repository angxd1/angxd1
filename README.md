<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:ff9900,100:0d1117&height=140&section=header&text=angad%20singh&fontSize=44&fontColor=ffffff&fontAlignY=62&animation=fadeIn" width="100%" />

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=800&color=FF9900&center=true&vCenter=true&width=620&height=45&lines=cs+%40+mcmaster;president+%E2%80%A2+aws+student+builder+group;real-time+systems+%C2%B7+applied+ai+%C2%B7+cloud;i+ship+things+that+have+a+demo" alt="Typing SVG" />
</a>

<a href="https://angad-portfolio1.vercel.app/"><img src="https://img.shields.io/badge/portfolio-0d1117?style=for-the-badge&logo=safari&logoColor=ff9900" /></a>
<a href="https://www.linkedin.com/in/angad-singh23/"><img src="https://img.shields.io/badge/linkedin-0d1117?style=for-the-badge&logo=linkedin&logoColor=ff9900" /></a>
<a href="mailto:singa401@mcmaster.ca"><img src="https://img.shields.io/badge/email-0d1117?style=for-the-badge&logo=gmail&logoColor=ff9900" /></a>

</div>

---

### `> whoami`

```ts
const angad = {
  program:  "BASc Computer Science @ McMaster University",
  leading:  "President, AWS Student Builder Group @ McMaster",
  before:   "Cloud Engineer, AWS Cloud Club @ McMaster",
  focus:    ["real-time systems", "applied AI", "cloud + data tooling"],
  based_in: "Hamilton, ON",
  status:   "open to Summer 2027 internships",
};
```

I like the part of software where a hard system has to feel simple — a glove that streams
sensor data into a clinician's dashboard, an inbox that quietly reorganizes itself, a CSV that
tells you why it can't be trusted. Latency and failure modes are the interesting part.

---

### `> projects`

Most of these were built with a team. The **Role** column says exactly what I owned — the repo
history backs it up.

<!-- NOTE: Data Health Console has a live Streamlit demo, but as of the last check it 303s to a
     Streamlit sign-in wall for logged-out visitors. Make the app public, then add this to its
     Project cell: · **[live ↗](https://data-analyzer-s6jcpxygphyuv5rwxcmozt.streamlit.app/)**
     A live demo link is the single highest-value thing on this table — worth fixing first. -->

| Project | Role | Stack | What it is |
|---|---|---|---|
| **[Dextera](https://github.com/athravseruwam07/dextera)** | Team of 4 · joint-top contributor | ESP32 · Node · Express · Postgres · WS · React · R3F | Smart-glove stroke-rehab platform. Five flex sensors stream 12-bit ADC over serial; a Node bridge normalizes them into per-patient calibrated 0–100 bend values and broadcasts gestures to a live clinician dashboard over WebSockets. Four MediaPipe + React Three Fiber rehab games score reps, accuracy, and weakest finger. |
| **[ApplyPulse](https://github.com/angxd1/Autonomous-Job-Search-OS)** | Solo · MIT | Next.js 15 · Prisma · Supabase · Inngest · Chrome MV3 | Open-source job-search OS. A Chrome extension captures postings from any board, forwarded application emails get classified (OA / interview / rejection / offer) by an Inngest pipeline, and the pipeline updates itself. Shipped v0.1 → v0.4. |
| **[MemoLens](https://github.com/athravseruwam07/memolens)** | Team of 2 | FastAPI · Next.js · Postgres · Redis · Docker | Real-time assistive system for dementia care. Recognizes familiar faces, tracks where daily items were last seen, fires contextual reminders, and streams a live event feed to caregivers. Ships with deploy-check and end-to-end smoke scripts. |
| **[Doceo](https://github.com/athravseruwam07/doceo)** | Team of 3 | Next.js 15 · FastAPI · Gemini · SSE · Framer Motion | AI STEM tutor that teaches on an animated whiteboard. Gemini generates a structured lesson streamed step-by-step over SSE, TTS narration stays synced to KaTeX animations, and you can interrupt mid-lesson to ask why. |
| **[Data Health Console](https://github.com/angxd1/Data-Analyzer)** | Solo | Python · Streamlit · Pandas · SQLite · pytest | Dataset triage before you model anything. Heuristic checks for ID-like columns, near-constant fields, unparsed dates, and runaway cardinality, folded into a 0–100 quality score. SQLite persistence, pytest suite, GitHub Actions CI. |
| **[OpenClaw Workshop](https://github.com/Jasiri-w/aws-cc-mac-openclaw-workshop)** | Co-author · AWS Cloud Club | AWS EC2 · S3 · FastAPI · Whisper · Ollama | The workshop I helped write and run for McMaster students: build a local Whisper + Ollama note-taker, then deploy an AI agent to EC2 and wire it to Discord and S3. ~1 hour, start to working deploy. |

---

### `> stack`

**Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=ff9900)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=ff9900)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=ff9900)
![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=ff9900)
![C](https://img.shields.io/badge/C-0d1117?style=flat-square&logo=c&logoColor=ff9900)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=postgresql&logoColor=ff9900)

**Frameworks**

![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=ff9900)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=ff9900)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=ff9900)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=ff9900)
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=flat-square&logo=streamlit&logoColor=ff9900)
![Tailwind](https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=ff9900)

**Infra & Data**

![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=ff9900)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=ff9900)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=ff9900)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=ff9900)
![Prisma](https://img.shields.io/badge/Prisma-0d1117?style=flat-square&logo=prisma&logoColor=ff9900)
![Vercel](https://img.shields.io/badge/Vercel-0d1117?style=flat-square&logo=vercel&logoColor=ff9900)

---

### `> now`

- Leading the **AWS Student Builder Group** at McMaster — workshops, cloud labs, and project nights.
- Growing **[ApplyPulse](https://github.com/angxd1/Autonomous-Job-Search-OS)** toward a v1.0 launch.
- Grinding **[NeetCode](https://github.com/angxd1/neetcode-submissions)** on the side.

<!-- STATS CARDS: deliberately omitted, for two reasons.
     1. github-readme-stats.vercel.app is returning 503 on every request right now
        (the shared public instance is chronically rate-limited). A broken image
        icon on your profile is worse than no card at all. If you want these, fork
        github-readme-stats and deploy your own instance with your own PAT, then
        swap the hostname below.
     2. A contributions card advertising a thin commit year undersells you more
        than the project table above does. Turn it on once the graph earns it.

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=angxd1&layout=compact&hide_border=true&bg_color=0d1117&title_color=ff9900&text_color=c9d1d9&langs_count=6" height="150" />
<img src="https://github-readme-stats.vercel.app/api?username=angxd1&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ff9900&icon_color=ff9900&text_color=c9d1d9&include_all_commits=true&count_private=true" height="150" />
<img src="https://github-readme-activity-graph.vercel.app/graph?username=angxd1&bg_color=0d1117&color=ff9900&line=ff9900&point=ffffff&area=true&area_color=ff9900&hide_border=true" width="100%" />
-->

---

<div align="center">

**[portfolio](https://angad-portfolio1.vercel.app/)** · **[linkedin](https://www.linkedin.com/in/angad-singh23/)** · **[email](mailto:singa401@mcmaster.ca)**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:ff9900,100:0d1117&height=90&section=footer" width="100%" />
