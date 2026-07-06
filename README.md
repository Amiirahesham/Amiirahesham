<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:1E293B&height=220&section=header&text=Amira%20Hesham&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=React%20Front-End%20Developer%20%7C%20AI%20Graduate&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?lines=Building+interfaces+that+feel+inevitable;Frontend+engineer+with+an+AI+background;React+%2B+TypeScript+%2B+a+RAG+chatbot+in+production;Faculty+of+Artificial+Intelligence%2C+Class+of+2026&font=Fira+Code&center=true&width=650&height=45&color=38BDF8&vCenter=true&size=20&pause=1800" />
</a>

</div>

<br>

<table align="center">
<tr>
<td>

## Who I Am

I'm a Front-End Developer who graduated from the Faculty of Artificial Intelligence at Kafrelsheikh University in 2026. That combination shapes how I work: I write React the way an engineer trained on systems thinks about data — as something with structure, state, and failure modes — not just as boxes on a screen.

My final year was spent building a full university portal from the ground up: a bilingual Arabic/English platform with role-based dashboards for students, professors, and admins, wired to an AI chatbot running Retrieval-Augmented Generation over Arabic academic documents. I owned the entire front-end — architecture, components, internationalization, performance — while integrating a FastAPI backend built by the rest of the team.

I'm looking for a front-end or full-stack role where interface work and applied AI aren't treated as separate departments.

</td>
</tr>
</table>

<br>

## Developer Snapshot

<table align="center">
<tr>
<td width="50%" valign="top">

**Currently**
```yaml
role: React Front-End Developer
graduated: Faculty of Artificial Intelligence, 2026
university: Kafrelsheikh University
based_in: Egypt
languages: Arabic (native), English (professional)
```

</td>
<td width="50%" valign="top">

**Training Programs**
```yaml
- DEPI
- NTI
- Microsoft Machine Learning Engineer Program
```

</td>
</tr>
</table>

<br>

## What I Care About

<table align="center">
<tr>
<td align="center" width="16%"><b>Architecture</b><br/><sub>Systems that survive scope creep</sub></td>
<td align="center" width="16%"><b>Performance</b><br/><sub>Every millisecond is a decision</sub></td>
<td align="center" width="16%"><b>Accessibility</b><br/><sub>Not an afterthought</sub></td>
<td align="center" width="16%"><b>Responsive UI</b><br/><sub>One codebase, every screen</sub></td>
</tr>
<tr>
<td align="center"><b>Component Design</b><br/><sub>Reusable, not repeated</sub></td>
<td align="center"><b>UX Detail</b><br/><sub>The 5% that's felt, not seen</sub></td>
<td align="center"><b>Debugging</b><br/><sub>Root cause over quick patch</sub></td>
<td align="center"><b>Readable Code</b><br/><sub>Written for the next person</sub></td>
</tr>
</table>

<br>

---

## Featured Project — Smart Integrated University Portal

<table align="center">
<tr>
<td>

**A complete digital ecosystem for the Faculty of Artificial Intelligence**, spanning a public bilingual website, a student portal, a professor portal, an admin dashboard, and an AI-powered Arabic assistant — all shipped and deployed on Vercel.

I built and owned the front-end in its entirety.

</td>
</tr>
</table>

**Stack I used:**

<div align="center">

![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![React Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![i18next](https://img.shields.io/badge/i18next-26A69A?style=for-the-badge&logo=i18next&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

**What I actually built:**

| Area | What it involved |
|---|---|
| **Bilingual System** | Full Arabic/English localization with i18next, including a `HomeCarousel` that had to correctly reverse `translateX` math and swap the `dir` attribute between RTL and LTR without breaking animation timing |
| **AI Chatbot Interface** | A custom `Chatbot.tsx` with a hand-drawn `RobotIcon` SVG, fullscreen toggle, scroll-locking, and careful z-index layering so it never fights with the rest of the UI |
| **Navigation** | A scroll-aware, animated `Navbar.tsx` that's session-aware, resolves role-based dashboard links, and truncates long names gracefully instead of breaking layout |
| **Dashboards** | A persistent `DashboardLayout.tsx` serving distinct student, professor, and admin views, backed by role-based routing |
| **Live Content** | A `NewsSection` pulling real scraped university news through Swiper.js |
| **Data Layer** | Axios + TanStack Query for server state, Zod for runtime validation, React Context for session/theme state |

**Performance work:**

```
Initial Load Time
3.4s ████████████████████████████████████████
1.1s ████████████████
                → via code splitting + lazy loading
```

**On the backend side**, I also worked directly in the Arabic RAG pipeline (Qwen-based) to fix language mixing between Arabic and Chinese tokens in generated responses, added Arabic letter normalization across common variants (`ة`/`ه`, `أ`/`إ`/`آ`/`ا`, `ى`/`ي`) to make retrieval more forgiving of real-world spelling, and reworked greeting-handling so casual openers skip the RAG pipeline entirely instead of triggering an unnecessary retrieval call.

Built with a team of eight under the supervision of Dr. Mohamed Abdo — my slice of it was the entire client experience, from first paint to final API call.

<br>

---

## Featured Repositories

<table align="center">
<tr>
<td width="50%">

### University Portal — Front-End
Bilingual RTL/LTR platform with role-based dashboards and a streaming AI chatbot.
<br>
`React` `TypeScript` `Vite` `Tailwind` `FastAPI`
<br>
**[View Repository →](#)**

</td>
<td width="50%">

### Arabic RAG Chatbot
Retrieval-augmented assistant answering university queries in Arabic, with normalization-aware retrieval.
<br>
`Python` `FastAPI` `RAG` `Qwen`
<br>
**[View Repository →](#)**

</td>
</tr>
<tr>
<td width="50%">

### Environment Monitoring Dashboard
Real-time sensor visualization with responsive charting and live data streams.
<br>
`React` `Recharts` `WebSockets`
<br>
**[View Repository →](#)**

</td>
<td width="50%">

### Plant Store
E-commerce front-end with cart state, filtering, and a component library built for reuse.
<br>
`React` `TypeScript` `Tailwind`
<br>
**[View Repository →](#)**

</td>
</tr>
<tr>
<td width="50%" colspan="2" align="center">

### Family Bank System
A ledger-style application for shared household finances — accounts, transactions, and running balances.
<br>
`React` `Node.js` `MongoDB`
<br>
**[View Repository →](#)**

</td>
</tr>
</table>

<br>

---

## Tech Arsenal

**Languages**

![Python](https://skillicons.dev/icons?i=py) ![JavaScript](https://skillicons.dev/icons?i=js) ![TypeScript](https://skillicons.dev/icons?i=ts) ![HTML](https://skillicons.dev/icons?i=html) ![CSS](https://skillicons.dev/icons?i=css) ![SQL](https://skillicons.dev/icons?i=mysql)

**Front-End**

![React](https://skillicons.dev/icons?i=react) ![Next.js](https://skillicons.dev/icons?i=nextjs) ![Vite](https://skillicons.dev/icons?i=vite) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![Materal UI](https://skillicons.dev/icons?i=materialui) ![Figma](https://skillicons.dev/icons?i=figma)

**Back-End**

![Node.js](https://skillicons.dev/icons?i=nodejs) ![Express](https://skillicons.dev/icons?i=express) ![FastAPI](https://skillicons.dev/icons?i=fastapi)

**Databases**

![MongoDB](https://skillicons.dev/icons?i=mongodb) ![MySQL](https://skillicons.dev/icons?i=mysql)

**Machine Learning**

![Python](https://skillicons.dev/icons?i=py) ![TensorFlow](https://skillicons.dev/icons?i=tensorflow) ![PyTorch](https://skillicons.dev/icons?i=pytorch) ![OpenCV](https://skillicons.dev/icons?i=opencv)

**Cloud & Deployment**

![Azure](https://skillicons.dev/icons?i=azure) ![Vercel](https://skillicons.dev/icons?i=vercel) ![Netlify](https://skillicons.dev/icons?i=netlify)

**Tools**

![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VS Code](https://skillicons.dev/icons?i=vscode) ![Postman](https://skillicons.dev/icons?i=postman) ![Linux](https://skillicons.dev/icons?i=linux)

<sub>Also comfortable with: shadcn/ui · Radix UI · TanStack Query · React Context API · Axios · Zod · Framer Motion · Recharts · NumPy · Pandas · scikit-learn</sub>

<br>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=amira-hesham&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=amira-hesham&theme=tokyonight&hide_border=true" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amira-hesham&layout=compact&theme=tokyonight&hide_border=true" width="48%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=amira-hesham&theme=tokyo-night&hide_border=true" width="98%"/>

</div>

<sub>Replace <code>amira-hesham</code> above with your actual GitHub username for these to render correctly.</sub>

<br>

---

## Current Focus

<table align="center">
<tr>
<td width="33%" valign="top">

**Building**
- Deepening RAG architecture skills beyond the university chatbot
- Exploring server-driven UI patterns for large dashboards

</td>
<td width="33%" valign="top">

**Learning**
- Advanced TypeScript patterns for large-scale front-ends
- Model evaluation and fine-tuning workflows

</td>
<td width="33%" valign="top">

**Open Source Goals**
- Contributing to i18n/RTL tooling in React libraries
- Publishing reusable bilingual UI components

</td>
</tr>
</table>

<br>

---

## Why Work With Me

I've shipped a production system end-to-end — not a tutorial clone. That means I've dealt with the unglamorous parts: RTL layout math that breaks in subtle ways, chatbot state that has to survive route changes, dashboards that need to look different for three different user roles without three different codebases. I debug from the browser down to the API response, and I don't consider a feature done until it holds up in Arabic, in English, and on a phone.

<br>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E293B,100:0F172A&height=120&section=footer" width="100%"/>

<sub>Amira Hesham — Front-End Developer, AI Graduate, Faculty of Artificial Intelligence, Kafrelsheikh University, 2026</sub>

</div>
