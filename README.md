<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Chinmay+%F0%9F%91%8B;Software+Engineer+%7C+MS+%40+Northeastern;I+build+things.+Then+deploy+them.)](https://git.io/typing-svg)

</div>

---

Software engineer with **3.5+ years in fintech** - building and shipping B2B payment platforms, banking kiosks, and real-money transaction systems at AuroPay, Mumbai. Now doing my **MS in Information Systems at Northeastern University** (2025–27) and open to Summer/Fall 2026 co-op roles in software engineering, data, or AI.

When I'm not at a keyboard, I'm tracking tail numbers at Logan ✈️ or coaching form at Marino Recreation Center 🏋️.

---

## 🧠 About Me

```yaml
name: Chinmay Sakhare
location: Boston, MA
education: MS Information Systems @ Northeastern University (2025–2027)
looking_for: Summer 2026 Co-op — Software Engineering
previous_role: Software Engineer @ AuroPay, Mumbai (3.5 years)
hobbies:
  - Plane spotting ✈️ (yes, I know the difference between a 737 MAX and a 737 NG)
  - Helping people lift heavy things @ Marino Recreation Center
  - Building things I almost bought online
```

---

## 🚀 Projects

### 📊 [LogBase](https://github.com/Chinmay-Sakhare07/Log_Analytics_System) · [Live Demo](https://loganalyticssystem.vercel.app)

Distributed log analytics system built from scratch — the kind of thing Splunk and ELK Stack do, rebuilt to understand how it actually works. Full pipeline: a Python file tailer with exponential backoff and disk buffering, a FastAPI ingestion service writing to Astra DB (Cassandra) partitioned by service and date, hourly aggregates in PostgreSQL to keep stats queries cheap, a query API with cursor-based pagination, and a React dashboard with live tail, analytics charts, and a real-time log generator.

**Deployed entirely on free tiers** (Fly.io, Astra DB, Neon, Vercel) with rate limiting, CORS controls, and a GitHub Actions cron for daily data generation. Nine distinct deployment failures — port restrictions, SSL bundles, Fly.io sleep cycles — documented and resolved.

`FastAPI` `Python` `Cassandra (Astra DB)` `PostgreSQL` `React` `Fly.io` `Docker` `Prometheus`

---

### 🏥 [MediNexus](https://github.com/Chinmay-Sakhare07/Group13_Final_AED_Project_MediNexus_Hospital_management_system) · [Live Demo](https://medinexushealth.netlify.app)

Full-stack hospital management platform — patient registration, doctor scheduling, appointment management, billing with insurance claims, lab test tracking, prescriptions, and pharmacy inventory. Built for the DMDD course at Northeastern.

26-table normalized schema with 3 UDFs, 6 views, 1 audit trigger, 6 stored procedures, 54 performance indexes, and AES-256 column-level encryption on sensitive patient and insurance data. Deployed on free infrastructure: Oracle Cloud Always Free VM running the .NET API, Cloudflare Worker as an HTTPS proxy (bypassing Oracle's HTTP-only egress), Azure SQL Serverless for the database, Netlify for the frontend.

`React` `.NET Core 9` `SQL Server` `Azure SQL` `Dapper` `Oracle Cloud` `Cloudflare Worker` `DuckDNS`

---

### ☕ [CafeVision](https://github.com/Chinmay-Sakhare07/CafeVison-MGEN_Hackathon_2025)

Real-time café occupancy and customer behavior tracker built in 4 hours at the Plainsight × MGEN Computer Vision Hackathon 2025. YOLOv8 handles object detection, Norfair handles multi-object tracking, Shapely defines zone boundaries. The pipeline counts barista actions, tracks customer dwell time from entry/exit timestamps, and outputs live seat occupancy to a CSV log and console display.

`Python` `YOLOv8` `OpenCV` `OpenFilter` `Shapely` `PyTorch` `Norfair`

---

### 🎵 [VibeReact](https://github.com/Chinmay-Sakhare07/VibeReact) · [Live Demo](https://vibe-react-five.vercel.app)

Was about to buy LED strips off TEMU. Built this instead. Captures microphone audio in real time, runs beat detection on the bass frequency range (bottom 25% of FFT bins, 50ms debounce), and makes your entire screen flash and pulse with the music. Four modes: Strobe, Disco, RGB, Rainbow. No hardware required — just a browser and something playing loud enough for the mic to catch.

`React 18` `Web Audio API` `AudioContext / AnalyserNode` `getUserMedia` `requestAnimationFrame`

---

### 🌐 [Portfolio](https://chinmaysakhare.netlify.app)

Interactive portfolio built to feel like a product, not a template. Working terminal with 20+ commands, 4 hidden games (Snake, Tetris, Memory Match, Typing Speed Test), section-aware emoji cursor trails, scroll-triggered animations, and 10 color themes (5 light, 5 dark). Built entirely in React with zero CSS frameworks — every style is inline, every color flows from a single theme object in `themes.js`.

Hidden features: type `snake`, `tetris`, `memory`, or `typing` in the terminal. Try the Konami code. Run `sudo hire chinmay`.

`React 18` `Vite` `Canvas API` `Web Audio API` `React Context` `IntersectionObserver` `Netlify`

---

## 💼 Experience

**Software Engineer — AuroPay** *(Mumbai, India · 3.5 years)*

Built and maintained a B2B payments platform processing real-money transactions. Developed banking kiosk applications (CDK/PBK/MFK) deployed at Kotak Mahindra, Axis Bank, and SBI branches across India.

`.NET Core` `MySQL` `AWS Serverless` `Angular` `.NET MVC` `SQL Server`

---

## 🛠️ Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frameworks & Tools**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

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
