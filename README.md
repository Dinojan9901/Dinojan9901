# Hi, I'm Dinojan 👋

**Full Stack Developer · Computer Engineering graduate (University of Ruhuna, 2026) · Vavuniya, Sri Lanka**

I build production web platforms and the systems behind them: APIs, real-time features, event-driven pipelines, and the CI/CD that ships them. I spent a year at **Yarl Ventures** building features for two live products, and my side work leans into applied AI and data engineering.

- 🔭 Currently: final research on **TRACES**, post-quantum secure vehicular networks with an LLM-based intrusion detection cascade
- 📄 Co-author: *AutoGradePro* (Academic Sessions 2026, University of Ruhuna)
- 💬 Ask me about: MERN / TypeScript backends, RAG systems, Kafka + Spark pipelines, Docker & CI/CD
- 📫 [dinojv21@gmail.com](mailto:dinojv21@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dinojan) · [Portfolio](https://dinojan-v.vercel.app)

---

## 💼 Work

**Full Stack Developer, Yarl Ventures (PVT) Ltd** · *May 2025 – May 2026 (intern → full-time)*

- **[MediMan](https://mediman.life/)**: telemedicine admin platform, my main product. Server-side pagination and field projection to cut API payloads; a read-only viewer-admin role, clinic management and appointment rescheduling; Twilio, Nodemailer and Firebase notifications; wallet and account-deletion approval workflows; GitHub Actions CI/CD behind Nginx.
- **[EDUS LMS](https://lms.edustutor.com/)**: contributed to a subscription LMS with monthly billing. Role-permission testing across 103 user actions, API response optimisation, tutor profile features, and work on payments, wallets and chat.

---

## 🚀 Featured Projects

| Project | What makes it different | Stack |
|---|---|---|
| [**Real-Time Fleet Operations Platform**](https://github.com/Dinojan9901/miniproject-fleet-lambda) | Lambda architecture: Kafka + Spark Structured Streaming give real-time metrics, while an Airflow batch layer reconciles costs *exactly* against source data. Pipeline health is watched by Prometheus alert rules and Grafana. | Kafka · Spark · Airflow · FastAPI · Prometheus · Docker |
| [**Financial Document Q&A (RAG)**](https://github.com/Dinojan9901/Financial-QA-System) · [live](https://financial-app-system-bcffpkdt88dxp8krfjg7pd.streamlit.app/) | Answers questions over 10-K and SEC filings with **page-level citations**. Hit@1 retrieval of **1.000** and **84%** gold-keyword recovery vs **<1%** for an ungrounded LLM on financial-qa-10K. | Python · FastAPI · ChromaDB · Llama 3.3 · Streamlit |
| [**QuickDeliver**](https://github.com/Dinojan9901/delivery-system) | Microservices behind an Nginx gateway that load-balances horizontally scaled order replicas. RabbitMQ decouples notifications, so placing an order never waits on downstream services. | Node.js · RabbitMQ · MongoDB · Nginx · Docker · GitHub Actions |
| [**AutoGradePro**](https://github.com/Dinojan9901/AutoGradePro) · *published* | Grades short answers on **meaning, not keywords** by pairing rule-based checks with local LLM semantic matching (Ollama). Accepts TXT, DOCX and PDF. | Next.js · TypeScript · Django · PostgreSQL · Ollama |
| [**Parallel BFS (HPC)**](https://github.com/Dinojan9901/HPC-BFS-Report) | Same algorithm in OpenMP, MPI and CUDA, all matching the serial baseline exactly. Amdahl analysis found an 89.4% parallel fraction and a 9.43x speedup ceiling. | C++17 · OpenMP · MPI · CUDA |
| [**Library Management System**](https://github.com/Dinojan9901/Library_Management) | Commit-to-cloud automation: GitHub webhooks trigger Jenkins, which builds Docker images and deploys to AWS EC2 provisioned with Terraform and Ansible. | MERN · Jenkins · Terraform · Ansible · AWS |

<details>
<summary><b>More projects</b></summary>

- [ECG Image Classification](https://github.com/Dinojan9901/ECG_Image_Classification): CNN with transfer learning on MIT-BIH and PTB datasets
- [GSM Smart Home Automation](https://github.com/Dinojan9901/Smart_Home_Automation_System): Arduino control over the cellular network, with temperature, gas and light sensors
- [Personal AI Assistant](https://github.com/Dinojan9901/AI_Assistant_App): React + Node.js chat assistant with OpenAI, JWT auth and saved history
- [Room Occupancy Detection](https://github.com/Dinojan9901/Room_Occupancy_Detection_ML): ML classifiers on multi-sensor IoT data
- [Healthcare Mobile App](https://github.com/Dinojan9901/Healthcare_Mobile_Application): Flutter app with Firebase auth and real-time data
- [Employee Shift Tracker](https://github.com/Dinojan9901/Employee_Shift_Tracker): MERN app deployed to Render with `render.yaml` infrastructure-as-code

</details>

---

## 🛠️ Tech Stack

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Web & Backend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socketdotio&logoColor=white)

**Data & AI**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## 🏅 Beyond Code

- IEEE Xtreme 18.0 (2024): 24-hour global programming contest, 3-member team
- Demonstrator, ReXtro 2025 Engineering Exhibition (Software Engineering Zone), University of Ruhuna
- Member of IESL and formerly the IEEE Student Branch, University of Ruhuna
