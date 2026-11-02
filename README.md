

![](https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Venkata%20Mahith%20Manne&fontColor=ffffff&fontSize=44&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Scalable%20Systems%20%26%20Intelligent%20Automation&descAlignY=60&descSize=16)

**If a solution doesn't exist, I build it. I refuse to stick to one lane.**

![LinkedIn](https://img.shields.io/badge/LinkedIn-mahithmanne-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)
![Email](https://img.shields.io/badge/Email-venkatamahith@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)



---

## 👋 About me

I'm a software engineer from Hyderabad, India. I work across AI, cybersecurity and DevOps, and I treat every repetitive manual task as a bug that needs an automated fix.

- 🧠 **Domain-agnostic builder.** I pick up a new stack on the fly, from AES-256/HMAC primitives to RAG pipelines and autonomous agents.
- ⚙️ **Automation first.** If I do something twice, I script it.
- 🎓 B.E. Computer Science and Engineering, Matrusri Engineering College (Osmania University), CGPA 8.2
- 🌱 Always learning, always building.

## 🛠️ Tech stack



![](https://skillicons.dev/icons?i=python,go,java,kotlin,ts,nodejs,cs,react&perline=8)  
![](https://skillicons.dev/icons?i=fastapi,flask,kafka,docker,aws,jenkins,githubactions,nginx&perline=8)  
![](https://skillicons.dev/icons?i=sqlite,firebase,androidstudio,dotnet,tailwind,vite,linux,git&perline=8)



**AI/ML:** PydanticAI · RAG · FAISS · Pinecone · scikit-learn · YOLOv8 · Whisper · sentence-transformers
**Security:** ModSecurity · CrowdSec · iptables · fail2ban · Zeek · AES-256 · HMAC · BCrypt
**Infra:** gRPC/Protobuf · Gunicorn · Celery · Caddy · systemd · Prometheus · Grafana

## 💼 Professional work

### Independent Software Engineer (Freelance) · Varkasa Inc, California (remote)

*Aug 2025 to present*

- **CI/CD:** built a Jenkins pipeline that replaced a 1-day build-and-test cycle run by 5 engineers with a 15-minute automated one.
- **Releases:** wrote GitHub Actions workflows that package cross-platform PyInstaller builds. Release packaging dropped from 10 minutes to under 60 seconds, with no manual deployment errors.
- **Backend:** rebuilt the FastAPI/Flask API service with consolidated endpoints and async workers (Gunicorn, gevent, Celery) on AWS EC2. It self-heals in under 30 s and runs at 99.9% uptime.
- **Infrastructure:** own the AWS setup (EC2, S3), reverse proxies and resource allocation for business-critical analytical tools.
- **Agentic AI:** built workflows on a multi-stage ReAct loop where the agent plans, executes and self-corrects.

**What I built there**

| Project | What it does |
|---|---|
| **FoXYiZ Test Framework** | Data-driven test automation driven by CSV, Excel or JSON, with no code per test. It has 14+ action families (UI, API, DB, AI, Cloud, IoT and more), reusable plans, tag filtering, parallel suites and an HTML dashboard. Ships as executables for Windows, macOS and Linux. *Python, pandas, Selenium, PyInstaller* |
| **FoXYiZ Backend API** | Flask service on AWS EC2: upload a CSV, run the engine, poll status and download the results, with API-key auth. Handles multi-file inputs, status shared safely across Gunicorn workers, timeout and idle watchdogs, and cleanup of orphaned Chrome processes. *Flask, Gunicorn, AWS EC2* |
| **FoXYiZ_User (BRAHL)** | Distributable package for end users: a compiled `FoXYiZ.exe`, editable test suites and a desktop UI. Optional AI helpers run on your own OpenAI key or a free local Ollama model. *Python, PyInstaller* |
| **ITeLearn Analytics Agent** | Joins GoTo Webinar and Teachable data so business questions can be asked in plain language, and reports what changed since your last visit. Uses an OpenAI agent with guarded tools (read-only SQL capped at 200 rows) and an account database the AI can't reach. Ingests about 106k students and 24k registrants, with a daily sync of about 1.5 min. *FastAPI, SQLite, Caddy, systemd, AWS Lightsail* |

### Freelance Software Developer · Lohitha Power Products Private Limited

- Built **UNIQE Servo**, a fully offline Windows desktop app that tracks warranty and AMC (Annual Maintenance Contract) reminders for the client's servo stabilizers.
- Warranty reminder dates are calculated automatically from the delivery date and warranty period. Records are colour-coded as expired, expiring today, upcoming or active, and searchable by customer, serial number, invoice or contact.
- A startup popup shows what needs attention, such as warranties expiring or expired and AMCs due within 30 days.
- Multiple users share one SQLite database over the LAN, with automatic fallback to local storage. Daily backups run on a schedule, and every change is logged with the user and a timestamp.
- Delivered as standalone `.exe` files with a Windows startup setup script.
- *Python, PyQt5, SQLite, PyInstaller*

### Android Application Developer Intern · No-Veg

*10 Apr 2025 to 4 Jun 2025*

- Built **NoVegDelivery**, the native Android app for delivery partners on the No-Veg food delivery platform.
- Implemented phone-OTP sign-in, multi-step rider onboarding with form validation, and a live order flow (online/offline toggle, accept/reject cards with a sound alert).
- Integrated Google Maps and the Directions API for route polylines and geocoding, on a Cloud Firestore backend shared with the customer and vendor apps.
- *Kotlin, Android Views (Material), Firebase Auth, Cloud Firestore, Google Maps SDK, Fused Location Provider*

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **SentinelFlow** | Kafka-based autonomous transaction-audit pipeline. An AI "Brain" (RAG over Pinecone) decides APPROVE / BLOCK / VERIFY, and a Go gRPC ingestor locks down accounts in under a second on high-value fraud. | Node/TS, Python, PydanticAI, Go, Kafka, gRPC, Docker |
| **PingsLanding** | Multi-layer DDoS defence: iptables, fail2ban, Nginx rate limits, ModSecurity + OWASP CRS, CrowdSec and Zeek, plus a Random Forest traffic classifier trained on CICIDS2017 and CSE-CIC-IDS2018. | Linux, Nginx, Python, scikit-learn, Prometheus, Grafana |
| **CryptoCrate** | File encryption toolkit with AES-256, HMAC integrity checks, BCrypt hashing and key management. | Java 11, Maven, Bouncy Castle |
| **Prospect Pulse** | Lead-scoring model with a Streamlit dashboard and a human-in-the-loop retraining loop (active learning). | scikit-learn, Streamlit |
| **SummarizeMe** | Cuts a video down to about 30% of its length using speech, object and face signals. | Whisper, YOLOv8, DeepFace, OpenCV, MoviePy |
| **Whereabouts** | Real-time location-sharing Android app. Users see shared locations on a live map and control who can see theirs. Location updates stream every 5-15 s through FusedLocationProvider. | Kotlin, Jetpack Compose, MVVM, StateFlow, Firebase Auth + Firestore, Google Maps Compose |
| **VitalGuard** | Wear OS health monitor with a live waveform UI and Firebase alerts. | Kotlin, Compose for Wear OS, Firebase |
| **FlowState** | Tray app for hydration reminders and hourly productivity tracking, with a Markdown end-of-day summary. | C#, WPF, .NET 8 |
| **TranslateX** | Desktop app that takes an image, PDF, audio file or Word document, extracts the text, translates it into Hindi, Marathi, Bengali, Gujarati, Tamil or Telugu, and saves the result as a `.docx` or `.mp3`. | Python, Tkinter, Tesseract OCR, SpeechRecognition, pdfplumber, Google Translate, gTTS |

More on my [repositories tab](https://github.com/Mahith0534?tab=repositories).

## 🏆 Highlights

- 🥇 **Google Cloud Skills Boost** Top 10 Learner, 3 seasons
- 🔐 **Zscaler** Zero Trust Certified Associate (ZTCA) and **CCNAv7**
- 🧩 **LeetCode** peak rating 1710, 115+ solved
- 🐍 IIT technical training in Python and Machine Learning

## 🔭 Currently building

- 🤖 **Agentic AI workflows** that plan, execute and self-correct, using a multi-stage ReAct loop.
- 📈 **An analytics agent** that answers business questions in plain language, with the AI limited to guarded, read-only tools.
- 🧪 **A data-driven test automation framework** that runs from spreadsheets with no code per test.
- 🌱 **Learning in public.** Building an LLM tokenizer from first principles in `token-to-agent`.


## 📫 Let's connect

I'm open to backend, DevOps/SRE, full-stack, AI and security roles.

- 💼 [LinkedIn](https://www.linkedin.com/in/mahithmanne/)
- ✉️ venkatamahith@gmail.com



<img src="assets/footer.svg" alt="Animated terminal: whoami, ls ~/lanes, cat philosophy.txt (If a solution doesn't exist, I build it.) and ./impact.sh (api with 99.9% uptime, CI/CD from 1 day to 15 min, releases from 10 min to under 60 s)" width="100%" />
