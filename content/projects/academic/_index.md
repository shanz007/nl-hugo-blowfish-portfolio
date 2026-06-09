---
title: "Projects: Academic Research"
date: 2025-09-26
type: page
draft: false
summary: "A collection of my recent research work in AI, HCI, and Software Development."
showHero: false
---

---

**WorkspaceLens – Outdoor Knowledge Work Photo Collection & Analysis**  
*Research Internship Project, CrowdComputing Research Group, University of Oulu*  

- Designed and developed a mobile-first Progressive Web Application (PWA) implementing the **pOKW2 photo analysis model** for collecting self-reported gaze-direction photographs from outdoor and semi-outdoor knowledge work environments.
- Built an end-to-end data collection pipeline: in-browser privacy editor (black box + blur censoring), 8-question pOKW2-aligned ESM questionnaire, GPS capture, and direct upload to cloud storage — all working offline with automatic retry on reconnect.
- Integrated an automated vision analysis pipeline using Supabase Edge Functions and OpenRouter vision models to extract pOKW2 environmental scores (nature, built environment, light quality, shelter, greenness index) from submitted photos.
- Developed a secure researcher admin dashboard with JWT authentication, paginated photo gallery, ESM response viewer, vision score display, and CSV export for statistical analysis.
- **Technologies:** `React 19` · `TypeScript` · `Vite` · `PWA / Workbox` · `Supabase` · `PostgreSQL` · `Deno Edge Functions` · `OpenRouter` · `Netlify`
- **Keywords:** `HCI` · `Mobile Computing` · `Experience Sampling Method (ESM)` · `Computer Vision` · `Hybrid Work` · `Knowledge Work` · `Photo Analysis` · `pOKW2` · `Environmental Affordances` · `Outdoor Workspaces`

---

**Smart Adaptive Interfaces – AI-Powered Digital Wellbeing**
*Applied Computing Research Project, University of Oulu*  
{{< alert icon=circle-info >}}
*Selected for Academic MindTrek 2025 Conference, Tampere, Finland.* 
[MindTrek 2025 Conference](https://www.mindtrek.org/mindtrek-conference-2025/), and published on
[ACM](https://dl.acm.org/doi/10.1145/3757980.3762111/)

{{< /alert >}}

- Designed and Developed a browser-based tool leveraging Large Language Models (LLMs) to combat digital distractions through real-time web content modification.
- Conducted a mixed-methods study with 18 participants to evaluate the system's effectiveness and user experience.
- **Technologies:** · `React`· `Chrome Browser Extensions API`·`OpenAI` 
- **Keywords:** `HCI` · `LLM` · `Digital Wellbeing` · `Browser Extensions` · `Distraction Management` · `Mixed-Methods Study`
---

**TrustifyAI – Twitter Profile Credibility Analyzer**  
*Thesis Research Project, University of Oulu*  
- Designed and developed an AI-powered PWP to evaluate and enhance Twitter profile credibility using LLM-based recommendations.
- Evalauted in a user study to investigate factors influencing trust perception and overall usability of the tool.
- **Technologies:**  `Vue.js` · `Node.js` · `SQLite`  · `MongoDB`  · `Nginx` · `OpenAI`
- **Keywords:** `HCI` · `LLM` · `Trust & Credibility` · `Social Media` · `User Study` · `AI Recommendations`
