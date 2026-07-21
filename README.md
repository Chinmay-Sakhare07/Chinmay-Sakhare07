<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Chinmay+%F0%9F%91%8B;+Software+Engineer+%7C+MS+%40+Northeastern+;I+build+things.+Then+deploy+them.)](https://git.io/typing-svg)

</div>

---

I build software that can't afford to fail - nearly **four years** at **AuroPay (Aurionpro Payments)** in Mumbai, engineering the payment systems, APIs, and event-driven microservices behind **50,000+ daily transactions**. Now doing my **MS in Information Systems at Northeastern University** (2025–2027), going deeper on systems design, data engineering, and applied AI - and looking for a **Fall 2026 / Spring 2027 co-op** with a team that cares about getting things right.

When I'm not at a keyboard, you'll find me at the gym, tracking tail numbers at Logan ✈️, or on a Costco run.

---

## 🧠 About Me

```yaml
name: Chinmay Sakhare
location: Boston, MA
education: MS Information Systems @ Northeastern University (2025–2027)
looking_for: Fall 2026 / Spring 2027 Co-op - Software Engineering
previous_role: Software Engineer @ AuroPay (Aurionpro Payments), Mumbai · Dec 2021 – Aug 2025
focus: Systems design, data engineering, applied AI
hobbies:
  - Plane spotting ✈️ (yes, I know a 737 MAX from a 737 NG)
  - Lifting - and coaching lifts - at Marino Rec
  - Building things I almost bought online
```

---

## 🚀 Projects

*Live demos run on free tiers - the first load can take 30–60s to wake the server.*

### 🎙️ [Duologue AI](https://github.com/Chinmay-Sakhare07/duologue-ai) · [Live Demo](https://duologue-ai.streamlit.app/)

*Article / PDF / URL → two-host AI podcast · Jul 2026*

Turns any article, PDF, URL, or topic into a two-host AI podcast, generated end to end on free infrastructure. Source text runs through an LLM-written script (Groq / Llama 3.3 70B in JSON mode), into text-to-speech, then gets stitched into a single MP3 and dropped into a browsable episode library - all in a deployed Streamlit app. Built for resilience: a fault-tolerant TTS fallback chain, graceful degradation, rate limiting, and a scheduled keep-alive for the database. A practical study in shipping on free tiers and adapting when hosts, rate limits, and unofficial APIs shift underneath you.

`Python` `Streamlit` `Groq / Llama 3.3` `Edge TTS` `Supabase` `FFmpeg` `GitHub Actions`

---

### 📊 [LogBase](https://github.com/Chinmay-Sakhare07/Log_Analytics_System) · [Live Demo](https://loganalyticssystem.vercel.app)

*Distributed log analytics platform · Mar – Apr 2026*

Distributed log analytics system built from scratch - the kind of thing Splunk and ELK Stack do, rebuilt to understand how it actually works. Full pipeline: a Python file tailer with exponential backoff and disk buffering, a FastAPI ingestion service writing to Astra DB (Cassandra) partitioned by service and date, hourly aggregates in PostgreSQL to keep stats queries cheap, a query API with cursor-based pagination, and a React dashboard with live tail, analytics charts, and a real-time log generator.

Deployed entirely on free tiers (Fly.io, Astra DB, Neon, Vercel) with rate limiting, CORS controls, and a GitHub Actions cron for daily data generation. Nine distinct deployment failures - port restrictions, SSL bundles, Fly.io sleep cycles - documented and resolved.

`FastAPI` `Python` `Cassandra (Astra DB)` `PostgreSQL` `React` `Fly.io` `Docker` `Prometheus`

---

### 🏥 [MediNexus](https://github.com/Chinmay-Sakhare07/Group13_Final_AED_Project_MediNexus_Hospital_management_system) · [Live Demo](https://medinexushealth.netlify.app)

*Hospital management system · Jan 2026*

Full-stack hospital management platform - patient registration, doctor scheduling, appointment management, billing with insurance claims, lab test tracking, prescriptions, and pharmacy inventory. Built for the DMDD course at Northeastern.

26-table normalized schema with 3 UDFs, 6 views, 1 audit trigger, 6 stored procedures, 54 performance indexes, and AES-256 column-level encryption on sensitive patient and insurance data. Deployed on free infrastructure: an Oracle Cloud Always Free VM running the .NET API, a Cloudflare Worker as an HTTPS proxy (bypassing Oracle's HTTP-only egress), Azure SQL Serverless for the database, and Netlify for the frontend.

`React` `.NET Core 9` `SQL Server` `Azure SQL` `Dapper` `Oracle Cloud` `Cloudflare Worker` `DuckDNS`

---

### 🎵 [VibeReact](https://github.com/Chinmay-Sakhare07/VibeReact) · [Live Demo](https://vibe-react-five.vercel.app)

*Browser audio visualizer · Oct 2025*

Was about to buy LED strips off TEMU. Built this instead. It captures microphone audio in real time, runs beat detection on the bass frequency range (bottom 25% of FFT bins, 50ms debounce), and makes your whole screen flash and pulse with the music. Four modes: Strobe, Disco, RGB, Rainbow. No hardware required - just a browser and something playing loud enough for the mic to catch.

`React 18` `Web Audio API` `AudioContext / AnalyserNode` `getUserMedia` `requestAnimationFrame`

---

### ☕ [CafeVision](https://github.com/Chinmay-Sakhare07/CafeVison-MGEN_Hackathon_2025)

*Real-time computer-vision café analytics · MGEN Hackathon 2025*

Real-time café occupancy and customer-behavior tracker built in 4 hours at the Plainsight × MGEN Computer Vision Hackathon 2025. YOLOv8 handles object detection, Norfair handles multi-object tracking, and Shapely defines the zone boundaries. The pipeline counts barista actions, tracks customer dwell time from entry/exit timestamps, and outputs live seat occupancy to a CSV log and console display. Recognized by judges for practical business impact.

`Python` `YOLOv8` `OpenCV` `OpenFilter` `Shapely` `PyTorch` `Norfair`

---

### 🧠 Neuro Classifier

*EEG signal processing · undergraduate thesis · Jun 2021*

Undergraduate thesis - an EEG signal-processing system in MATLAB that detects epilepsy from brain signals. Savitzky-Golay filtering for noise reduction, Discrete Wavelet Transform for feature extraction, and an ANN for classification, reaching 80% accuracy across test subjects.

`MATLAB` `Machine Learning` `Signal Processing` `DWT` `ANN`

---

### 🌐 [Portfolio](https://chinmaysakhare.netlify.app) · [Code](https://github.com/Chinmay-Sakhare07/Chinmay_portfolio)

*Interactive developer portfolio*

Built to feel like a product, not a template. A working terminal with 20+ commands, 4 hidden games (Snake, Tetris, Memory Match, Typing Speed Test), a bento-grid About section with animated counters, glassmorphism cards, section-aware emoji cursor trails, and 10 color themes (5 light, 5 dark). Built entirely in React with zero CSS frameworks - every style is inline, and every color flows from a single theme object in `themes.js`.

Hidden features: type `snake`, `tetris`, `memory`, or `typing` in the terminal. Try the Konami code. Run `sudo hire chinmay`.

`React 18` `Vite` `Canvas API` `Web Audio API` `React Context` `IntersectionObserver` `Netlify`

---

## 💼 Experience

**Software Engineer - Aurionpro Payments (AuroPay)** *(Mumbai, India · Dec 2021 – Aug 2025)*

Engineered secure, compliant, event-driven microservices for AuroPay's real-time payments platform, supporting high-volume transactions.

- **Reconciliation engine:** architected a PostgreSQL-backed reconciliation pipeline processing 50,000+ daily transactions, cutting error rates by 90% and automating 60–80% of previously manual verification across the merchant payments lifecycle.
- **API throughput:** optimized throughput by 40% by profiling .NET Core service layers and restructuring MySQL query execution plans, holding performance under peak loads of 50,000+ daily requests.
- **Fraud & velocity engine:** built a rule engine over live transaction streams - a UN-watchlist blacklisting layer and a configurable velocity layer - catching 15% more anomalies.
- **Security & access:** implemented IAM-aligned RBAC with AES-256 column-level encryption across 200+ merchant accounts on a multi-tenant platform, in line with PCI DSS.
- **Banking kiosks:** delivered CDK, PBK, and MFK kiosk applications in .NET MVC and SQL Server to Kotak Mahindra Bank, Axis Bank, and SBI across 500+ branches.
- **Mentorship:** mentored 5+ junior engineers through code reviews, system-design walkthroughs, and incident retrospectives.

`.NET Core` `MySQL` `AWS Serverless` `Angular` `.NET MVC` `SQL Server`

**Fitness Consultant - Marino Recreation Center, Northeastern** *(Boston, MA · Sep 2025 – Present)*

Because building software is only half the fun. Coaching 50+ daily visitors on form, technique, and programming, and keeping a busy floor running smoothly.

---

## 🎓 Education

**MS in Information Systems - Northeastern University** *(Boston, MA · Sep 2025 – Aug 2027)*
Application Engineering and Development · Data Management and Database Design · Data Warehousing and Business Intelligence · Data Science Engineering Methods and Tools

**BE in Electronics Engineering - RAIT, University of Mumbai** *(Mumbai, India · Graduated Jun 2021)*
Thesis: ML-based classification of neurological disorders from EEG signals - Savitzky-Golay filtering, DWT feature extraction, and ANN classifiers; 80% accuracy.

---

## 🛠️ Tech Stack

**Backend**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Data**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge&logo=flydotio&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Llama 3.3](https://img.shields.io/badge/Llama%203.3-0866FF?style=for-the-badge&logo=meta&logoColor=white)
![Edge TTS](https://img.shields.io/badge/Edge%20TTS-0078D4?style=for-the-badge)

**Data Tools**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-372923?style=for-the-badge&logo=dbeaver&logoColor=white)
![Navicat](https://img.shields.io/badge/Navicat-1E88E5?style=for-the-badge)
![ER Studio](https://img.shields.io/badge/ER%20Studio-6E4C9E?style=for-the-badge)

---

## 📜 Certifications

- **AWS Certified Cloud Practitioner** - Amazon Web Services (Jan 2024) · License `98Z8MJ1D5B1QQYCY`
- **Enterprise Web Dev (.NET Core)** - Swabhav Techlabs (Dec 2021)
- **Introduction to Java** - Coursera / LearnQuest (Jul 2021) · [Verify](https://coursera.org/verify/EMFSF56S7J2E)
- **Programming for Everybody (Python)** - Coursera / U of Michigan (Jun 2020) · [Verify](https://coursera.org/verify/244ENWDYRM4F)
- **Python Data Structures** - Coursera / U of Michigan (Jul 2020) · [Verify](https://coursera.org/verify/C8FQUSNS4D9T)
- **Using Python to Access Web Data** - Coursera / U of Michigan (Aug 2020) · [Verify](https://coursera.org/verify/EQGHSCTACRW9)
- **Responsive Websites (HTML5 & CSS3)** - Udemy (Aug 2020) · [Verify](https://ude.my/UC-27ed60f3-990b-45db-ba28-e425badd7e25)

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chinmaysakhare/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sakhare.c@northeastern.edu)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white)](https://chinmaysakhare.netlify.app/)

</div>

---

<div align="center">
  <i>Open to co-op opportunities, interesting problems, and gate B12 at Logan ✈️</i>
</div>
