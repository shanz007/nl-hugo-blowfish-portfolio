---
title: "Projects: Academic Research"
date: 2025-09-26
type: page
draft: false
summary: "A collection of my recent research work in AI, HCI, and Software Development."
showHero: false
---

---

{{< alert icon=circle-info >}}
**Project:** WorkspaceLens-Outdoor Knowledge Work Photo Collection & Analysis  
**Research Unit:** CrowdComputing Research Group, University of Oulu  
**Timeline:** May 2026 – Ongoing  
**Type:** Research Project / Progressive Web App  
**Status:** Pilot study / data collection in progress  
**Main App:** [WorkSpaceLens](https://tinyurl.com/y89w8637)  
**Admin Portal:** [WorkSpaceLens-Admin](https://tinyurl.com/mumu3ey2)
{{< /alert >}}

- Researched, Designed and developed a mobile-first Progressive Web Application (PWA) implementing the **pOKW2 photo analysis model** for collecting self-reported gaze-direction photographs from outdoor and semi-outdoor knowledge work environments.
- Built an end-to-end data collection pipeline: in-browser privacy editor (black box + blur censoring), 8-question pOKW2-aligned ESM questionnaire, GPS capture, and direct upload to cloud storage - all working offline with automatic retry on reconnect.
- Integrated an automated vision analysis pipeline using Supabase Edge Functions and OpenRouter vision models to extract pOKW2 environmental scores (nature, built environment, light quality, shelter, greenness index) from submitted photos.
- Developed a secure researcher admin dashboard with JWT authentication, paginated photo gallery, ESM response viewer, vision score display, and CSV export for statistical analysis.
- **Technologies:** `React 19` · `TypeScript` · `Vite` · `PWA / Workbox` · `Supabase` · `PostgreSQL` · `Deno Edge Functions` · `OpenRouter` · `Netlify`
- **Keywords:** `HCI` · `Mobile Computing` · `Experience Sampling Method (ESM)` · `Computer Vision` · `Hybrid Work` · `Knowledge Work` · `Photo Analysis` · `pOKW2` · `Environmental Affordances` · `Outdoor Workspaces`

👉 [View the project in detail →](/projects/academic/workspacelens/)

---

{{< alert icon=circle-info >}}
**Project:** Smart Adaptive Interfaces – AI-Powered Digital Wellbeing  
**Research Unit:** Applied Computing Research Project, UBICOMP, University of Oulu  
**Timeline:** Nov 2024 – May 2025  
**Type:** Academic Research / Progressive Web Software - A browser-based extension tool   
**ACM paper:** [ACM](https://dl.acm.org/doi/10.1145/3757980.3762111)
{{< /alert >}}


- Designed and Developed a browser-based tool leveraging Large Language Models (LLMs) to combat digital distractions through real-time web content modification.
- Conducted a mixed-methods study with 18 participants to evaluate the system's effectiveness and user experience.
- Selected for Academic MindTrek 2025 Conference, Tampere, Finland.
- **Technologies:** · `React`· `Chrome Browser Extensions API`·`OpenAI` 
- **Keywords:** `HCI` · `LLM` · `Digital Wellbeing` · `Browser Extensions` · `Distraction Management` · `Mixed-Methods Study`

👉 [View the project & App in detail →](/projects/academic/smartadaptiveinterfaces/)

---

{{< alert icon=circle-info >}}
**Project:** TrustifyAI – Sociam Media(Twitter) Profile Credibility Analyzer  
**Research Unit:** CrowdComputing Research Group, UBICOMP, University of Oulu  
**Timeline:** Nov 2024 – May 2025  
**Type:** MSc Thesis project - Academic Research / Progressive Web App 

**View app:** [TrustifyAI](https://vm1297.kaj.pouta.csc.fi/)    
**API Dashboard:** [TrustifyAI API](https://vm1297.kaj.pouta.csc.fi/api)
{{< /alert >}}

- Designed and developed an AI-powered PWP to evaluate and enhance Twitter profile credibility using LLM-based recommendations.
- Evalauted in a user study to investigate factors influencing trust perception and overall usability of the tool.
- **Technologies:**  `Vue.js` · `Node.js` · `SQLite`  · `MongoDB`  · `Nginx` · `OpenAI`
- **Keywords:** `HCI` · `LLM` · `Trust & Credibility` · `Social Media` · `User Study` · `AI Recommendations`

👉 [View the project in detail →](/projects/academic/trustifyai/)

---


{{< alert icon=circle-info >}}
**Project:** IoT-Based Weather Station ( Raspberry Pi Pico W )  
**Timeline:** Nov 2024 – May 2025  
**Type:** Academic Course Project, University of Oulu - Internet of Things (IoT)  

👉 [Project Report](/reports/IoT_Weather_Station_report.pdf) -  [Project Source](https://github.com/vniinimaki/iot_project.git)

{{< /alert >}}

- Worked on a group project designing implementing an IoT-based weather station using **Raspberry Pi Pico W**, collecting real-time environmental data - temperature, altitude, and atmospheric pressure via the **BMP280 sensor**
- Published sensor data to an **MQTT broker** and built a live web interface using **WebSocket** to subscribe and visualise incoming data streams in real time
- Explored person detection using the **OV7670 camera module** with on-device ML inference, encountered memory and image size constraints on the microcontroller, demonstrating practical trade-offs in embedded ML systems

- Technologies: · `Raspberry Pi Pico W` · `MicroPython` · `BMP280 Sensor` · `MQTT` · `WebSocket` · `HTML/CSS/JavaScript`
- Keywords: `IoT` · `Embedded Systems` · `MQTT` · `Real-Time Data` · `Raspberry Pi` · `WebSocket` · `Sensor Integration`


---

{{< alert icon=circle-info >}}
**Project:** Raft-Based Distributed Job Queue 
**Timeline:** Jan 2024 – May 2024  
**Type:** Academic Course Project, University of Oulu - Distributed Systems (Industry Track)  
[GitHub](https://github.com/KRVPerera/DistributedJobRaft)
{{< /alert >}}

- Worked on group project designing and implementing a scalable **distributed job queue** using the **Raft consensus algorithm**, supporting dynamic scaling to N nodes with guaranteed consistency through leader election and log replication

- Adhered to **RPC-based inter-node communication** following the original Raft paper specification
- Implemented **persistent state management** using SQLite to ensure nodes recover gracefully from failures without losing committed log entries.
- Conducted **performance evaluation** across multiple scenarios - measuring throughput (messages/second) under varying message counts and payload sizes

- Technologies: · `Go` · `SQLite` · `Docker` · `RPC` · `TCP` · `GitHub Actions`
- Keywords: `Distributed Systems` · `Raft Consensus` · `Leader Election` · `Log Replication` · `Fault Tolerance` · `Distributed Computing` · `Containerisation`
	
	