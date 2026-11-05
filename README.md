# Hi, I'm Dinojan 👋

**Full Stack Developer · Computer Engineering graduate (University of Ruhuna, 2026) · Sri Lanka**

I build production web platforms and the systems behind them: APIs, real-time features, event-driven pipelines, and the CI/CD that ships them. I spent a year at **Yarl Ventures** building features for two live products, and my own work leans into applied AI, LLM agents and MLOps.

- 🔭 Recently: final-year research on **TRACES**, post-quantum secure vehicular networks with an LLM-based intrusion detection cascade (7 attack classes at 0.867 macro-F1 on held-out data)
- 📄 Co-author: *AutoGradePro* (Proceedings of the Vice Chancellor's Awards and Academic Sessions 2026, University of Ruhuna)
- 💬 Ask me about: MERN / TypeScript backends, LLM agents and RAG, MLOps on Kubernetes, Kafka + Spark pipelines, Docker & CI/CD
- 📫 [dinojv21@gmail.com](mailto:dinojv21@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dinojan) · [Portfolio](https://dinojan-v.vercel.app)

---

## 💼 Work

**Full Stack Developer, Yarl Ventures (PVT) Ltd** · *May 2025 – May 2026 (intern → full-time)*

- **[MediMan](https://mediman.life/)**: telemedicine admin platform, my main product. Server-side pagination and field projection to cut API payloads; a read-only viewer-admin role, clinic management and appointment rescheduling; Twilio, Nodemailer and Firebase notifications; wallet and account-deletion approval workflows. Maintained its GitHub Actions CI/CD (behind Nginx) and ran its production releases.
- **[EDUS LMS](https://lms.edustutor.com/)**: contributed to a subscription LMS with monthly billing. Role-permission testing across 103 user actions, API response optimisation, tutor profile features, and work on payments, wallets and chat.

---

## 🚀 Featured Projects

| Project | What makes it different | Stack |
|---|---|---|
| [**Larkway – AI Support Agent**](https://github.com/Dinojan9901/larkway-support-agent) · [live](https://larkway-support-agent.vercel.app) | An AI support agent with 9 tools over policies, contracts and order data, also served over **MCP**. A deterministic policy engine, not the LLM, computes fees and SLAs; **156 tests** and **16/16 evals** pass. | Python · FastAPI · React · TypeScript · Claude / Groq / Gemini |
| [**LLM Research Agents**](https://github.com/Dinojan9901/llm-financial-research-agents) | Tool-calling financial research agents plus a **QLoRA fine-tuned Phi-3-mini** risk extractor. The fine-tune raised schema-valid JSON from **1/12 to 12/12** and ROUGE-L by **31%** over the base model. | Python · LangChain · Groq · Hugging Face PEFT/TRL |
| [**Credit Default MLOps Pipeline**](https://github.com/Dinojan9901/credit-default-mlops) | LightGBM tracked in MLflow and served by FastAPI on **Kubernetes (kind)**. Test ROC-AUC **0.79**; retraining promotes a model only if it beats the champion, with drift alerts. | LightGBM · MLflow · SHAP · Docker · Kubernetes · GitHub Actions |
| [**LendLot – Rental Marketplace**](https://github.com/Dinojan9901/lendlot) · [live](https://lendlot.vercel.app) | Blocks double-booking **in the database**: of 25 simultaneous requests for the same dates, only 1 is booked. CI runs **152 tests** plus CodeQL and Trivy scans; Lighthouse 96–100. | Next.js · TypeScript · Prisma · PostgreSQL · Playwright |
| [**Financial Document Q&A (RAG)**](https://github.com/Dinojan9901/Financial-QA-System) · [live](https://financial-app-system-bcffpkdt88dxp8krfjg7pd.streamlit.app/) | Team project. Answers questions over 10-K and SEC filings with **page-level citations**. Hit@1 retrieval of **1.000** and **84%** gold-keyword recovery vs **<1%** for an ungrounded LLM. | Python · FastAPI · ChromaDB · Llama 3.3 · Streamlit |
| [**Real-Time Fleet Operations Platform**](https://github.com/Dinojan9901/miniproject-fleet-lambda) | Lambda architecture: Kafka + Spark Structured Streaming give real-time metrics, while an Airflow batch layer reconciles costs *exactly* against source data. Watched by Prometheus alert rules and Grafana. | Kafka · Spark · Airflow · FastAPI · Prometheus · Docker |
| [**QuickDeliver**](https://github.com/Dinojan9901/delivery-system) | Microservices behind an Nginx gateway that load-balances horizontally scaled order replicas. RabbitMQ decouples notifications, so placing an order never waits on downstream services. | Node.js · RabbitMQ · MongoDB · Nginx · Docker · GitHub Actions |

<details>
<summary><b>More projects</b></summary>

- [AutoGradePro](https://github.com/Dinojan9901/AutoGradePro) (*published*): grades short answers on meaning, not keywords, by pairing rule-based checks with local LLM semantic matching (Ollama)
- [Parallel BFS (HPC)](https://github.com/Dinojan9901/HPC-BFS-Report): the same algorithm in OpenMP, MPI and CUDA, all matching the serial baseline; Amdahl analysis found an 89.4% parallel fraction
- [Library Management System](https://github.com/Dinojan9901/Library_Management): GitHub webhooks trigger Jenkins, which deploys Docker images to AWS EC2 provisioned with Terraform and Ansible
- [ECG Image Classification](https://github.com/Dinojan9901/ECG_Image_Classification): transfer-learning CNN on MIT-BIH and PTB, 95% test accuracy, served by FastAPI
- [GSM Smart Home Automation](https://github.com/Dinojan9901/Smart_Home_Automation_System): Arduino control over the cellular network, with temperature, gas and light sensors
- [Personal AI Assistant](https://github.com/Dinojan9901/AI_Assistant_App): React + Node.js chat assistant with OpenAI, JWT auth and saved history
- [Room Occupancy Detection](https://github.com/Dinojan9901/Room_Occupancy_Detection_ML): ML classifiers on multi-sensor IoT data
- [Healthcare Mobile App](https://github.com/Dinojan9901/Healthcare_Mobile_Application): Flutter app with Firebase auth and real-time data
- [Employee Shift Tracker](https://github.com/Dinojan9901/Employee_Shift_Tracker): MERN app with `render.yaml` infrastructure-as-code for Render

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
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socketdotio&logoColor=white)

**Data & AI**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

**DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(kind)-326CE5?style=flat&logo=kubernetes&logoColor=white)
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
- IEEE INSL Southern Provincial Competition (2024)
- 3rd Runner-Up, Provincial Under-19 Boys Chess (2015 and 2016)
- Member of IESL and formerly the IEEE Student Branch, University of Ruhuna
