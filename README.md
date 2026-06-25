# 👋 Hi, I'm Mohamad Al-Ashmar

**AI Engineer · Healthcare Tech · Enterprise Platforms**

📍 Damascus, Syria · 📞 +963 997 300 716 · ✉️ mohamad.ashmar.ai@gmail.com  
🔗 [GitHub](https://github.com/M0-AR) · [quantum-ai-web](https://github.com/M0-AR/quantum-ai-web)

Software Engineer (DTU, Denmark) with 5+ years of experience spanning the full AI lifecycle — from training models on hospital data and deploying on SuperComputer-DTU, to building hardware-software medical devices from scratch, to architecting multi-tenant enterprise platforms serving real users at scale. I've secured **$2M+ in funding** for a Danish Board of Health-approved data extraction project, delivered **15+ production AI modules** on GKE with ArgoCD GitOps, and driven measurable client impact including **60% profitability gains** and **35% cost reduction**. My work covers healthcare diagnostics (kidney/bladder tumor detection at 85–98% accuracy, real-time 3D urological devices), enterprise SaaS (14 analytics modules with SARIMA/Prophet forecasting, 10+ FastAPI microservices with circuit breakers and Redis Vector), LLM/RAG systems (GraphRAG, multi-agent architectures, 11+ MCP servers), embedded systems (PCBA validation, IoT-Azure integration), and governmental AI strategy (advising the Damascus Health Directorate on national AI adoption). I navigate complex regulatory landscapes including MDR 2017/745, ISO 13485, HIPAA, and GDPR, and have led cross-functional teams across **Denmark, Saudi Arabia, and Syria**.

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamad-al-ashmar-0502a240a/)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://quantum-ai-web.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamad.ashmar.ai@gmail.com)

---

## ⚡ Key Impact

| Metric | Achievement |
|--------|------------|
| **$2M+** | Funding secured for Epic healthcare data extraction (Danish Board of Health approved) |
| **90%** | Benign vs malignant kidney tumor classification |
| **98%** | Kidney vs non-kidney detection |
| **94%** | Four-class kidney classification (benign/malignant/normal/undefined) |
| **60%** | Client profitability increase via AI-driven inventory optimization |
| **35%** | Operational cost reduction |
| **15+** | Production AI modules on GKE (FastAPI + ArgoCD) |
| **11+** | MCP servers in production |
| **3** | Countries of cross-functional team leadership (DK, KSA, SY) |

---

## 🛠️ Core Stack

**AI/ML:** PyTorch · TensorFlow · JAX · HuggingFace Transformers · Unsloth · TRL · Axolotl · DeepSpeed  
**RAG & Agents:** LangChain · LlamaIndex · LangGraph · GraphRAG · CrewAI · AutoGPT  
**CV & Multimodal:** OpenCV · YOLO · SAM · Detectron2 · Diffusers  
**Infrastructure:** FastAPI · GKE · ArgoCD · Docker · Terraform · Prometheus · Grafana  
**Databases:** Elasticsearch · Redis · PostgreSQL · Neo4j · Qdrant · Pinecone · Milvus  
**LLM Serving:** vLLM · TGI · ONNX · TensorRT · OpenRouter · Groq  
**Languages:** Python · Rust · Go · TypeScript · Java · C++

---

## 🚀 Featured Projects

### 🇩🇰 Denmark Projects (DTU & Regionsjaelland Hospital)

#### 💰 AI-Powered Medical Data Extraction (Epic Scraping) — $2M+ Funding
Spearheaded a 1.5-year collaborative project between RUC and DTU using RPA to extract and stabilize patient data from Epic Software. Modular Python architecture (PyAutoGUI, OpenCV, pytesseract) for screen scraping and OCR — approved by the Danish Board of Health. Automated upload to REDCap within HIPAA/GDPR/21 CFR Part 11 compliance. **Secured $2M+ in funding** to expand across Europe.

#### 🧠 LLM-Based Patient Data Processing
Pipeline using GPT-4 and open-source LLMs (LLaMA) to process patient data extracted from healthcare systems. Generated clean structured Excel outputs, predicted patient risk percentages pre/post-operation, implemented RAG for local database Q&A, and built anonymization software (static + dynamic algorithms) for patient privacy before sending data to external models.

#### 🩺 Kidney Tumor AI Models (90–98% Accuracy)
Four AI models deployed on **DTU SuperComputer**: (1) Kidney vs. Non-Kidney detection (98%), (2) Benign vs Malignant classification (90%), (3) Four-class classification — benign, malignant, normal, undefined (94%), (4) Localization/Segmentation (YOLOv8) + Tumor Detection. Automated Jenkins/Docker CI/CD pipeline (RCC_v2) integrating with Orthanc PACS via C-STORE SCU protocols. Multi-stage processing: Data Validation → DICOM to BMP → AI Classification → Cleaning → Segmentation. SNOMED/ICD code mapping from raw Excel exports for oncology metrics (TNM staging, ISUP grading).

#### 🎥 AI Bladder Tumor Detection from Video
Real-time AI system detecting bladder tumors from cystoscopic video footage using SSIM (Structural Similarity Index) for intelligent sub-sampling and KMeans Clustering for key frame extraction — eliminating redundancy while enabling urologists with actionable intra-procedure insights.

#### 🏥 Real-Time 3D Urological Diagnostics (Medical Device)
Built a **medical device from scratch** integrating Ambu® aScope™4 Cysto with BNO055 orientation sensor for real-time cystoscope tracking mapped onto a 3D bladder model with color-coded navigation. SmartScopePC (AMD Ryzen 9 7950X, RTX 4090) for real-time inference. FastAPI microservice backend with client-server architecture enabling remote processing on DTU Supercomputer. **ISO 13485 / MDR 2017/745 compliant**.

#### ✋ SurgicalAir — Touchless Surgical Interface
Touchless interface enabling surgeons to control operational equipment via hand gestures in the air, maintaining sterile field. Computer Vision pipeline (MediaPipe + OpenCV) for full hand/finger detection and gesture recognition. Kinematic logic using `np.arctan2` and Euclidean distance for sub-millimeter precision. Hardware Abstraction Layer (HAL) parsing IMU telemetry with BLE→WiFi 6 communication roadmap for zero-lag response.

#### 🔌 Embedded Systems & Hardware Manufacturing
End-to-end PCBA process management with Eurocircuits (ODB++, CPL, BOM). AI-driven PCB design ecosystem using LLMs for component placement and routing optimization. Embedded firmware flashing (Atmel-ICE, Microchip Studio). LoRa→Azure Cloud IoT integration with real-time data visualization. Three-phase power system fault simulation for AI model testing.

#### ✅ Regulatory Compliance & Medical Device Certification
Class II Medical Device compliance (MDR 2017/745, ISO 13485, ISO 14971, FDA 21 CFR Part 820). Collaborated with Presafe Denmark A/S and Dansk Standard for CE Marking. AI integration strategy under EU Artificial Intelligence Act. Cost-benefit analysis for regulatory approval ($70K–$140K) and eQMS implementation.

#### 🏢 VisionTechWave — Entrepreneurship
Founded VisionTechWave in Denmark, driving AI and healthcare innovation. Directed RCC AI Intelligent Decision Support System for radiologists (Agile Sprint planning, full lifecycle from design to deployment).

#### 🏠 Arked — Bachelor Project (Score: 12/12)
Distinguished between house types from user-provided images using Computer Vision (SAM, Stable Diffusion). Later expanded to exterior facade design — detecting and replacing windows while preserving original view. **Achieved the highest score in the Danish system (12/12)**. [Demo](https://youtu.be/12zcDAHvOFY) · [Thesis](https://www.youtube.com/watch?v=JUSLCYDCZO4)

#### 🔐 Cryptera A/S — Internship & Student Job
Embedded device communication software in C++ (Linux-64bit/Windows-64bit), DLL libraries, TR31 secure key interchange, CMake, GDB debugging, Doxygen documentation, Jenkins CI/CD with Groovy. Developed mock testing framework for NUC management with pytest integration into Jenkins pipeline.

---

### 🇸🇦 KSA Projects (Wateen & Trustangle Group)

#### 🏪 Enterprise AI Platform — Wateen (14 Analytics Modules)
Multi-tenant FastAPI platform on GKE with SARIMA/Prophet forecasting, menu engineering (BCG Matrix), inventory optimization (98% accuracy), and organization-scoped Elasticsearch isolation. Enabled **60% profitability gains** and **35% cost reduction** for clients.

#### ⚙️ AI Microservices Suite (10+ Services)
FastAPI microservices monorepo with 17+ independently deployable services on GKE via ArgoCD GitOps. Includes OCR invoice extraction (4-stage pipeline, 50× cost savings), PO-Invoice Matcher (3-phase financial reconciliation with GRN auto-suggestions), AI Insights Chatbot (53 business modules, WebSocket + HTTP, Redis Vector for 18–52× faster search), Text-to-Image (3-agent LLM pipeline), and AI Recipe Generation (Halal compliance, bilingual).

#### 🔧 11+ MCP Servers in Production
Suite of production Model Context Protocol servers including Wateen operations (5 servers, 8,000+ LOC), Snowflake administration (55+ tools, 7,800+ LOC), and enterprise integrations (Elasticsearch, Keycloak, GCloud, LinkedIn Marketing, Browser automation).

#### 🤖 Multi-Agent Systems & R&D
ChatDev (virtual software company with role-playing agents), Reachware AI Agents (production assistant, code generator, proposal evaluator with TinyLlama 1.1B 4-bit + QLoRA), 6-service food microservices (CrewAI + ChromaDB + Apache Pulsar), Anything-LLM full-stack RAG (27+ AI providers, 8 vector DBs, MCP protocol).

#### 🏗️ Construction AI — Silver Foundation
12 specialized AI agents (EstimationBot, ContractReviewAI, BOQ generation from PDF/DWG/IFC/BIM) using FastAPI, Qdrant, MCP Protocol, and A2A agent interoperability. AI-powered quantity takeoff with CSI MasterFormat codes and historical pricing.

---

### 🇸🇾 Syria Projects

#### 🌐 Government AI Strategy — Damascus Health Directorate
Strategic advisor to the Directorate Head: AI readiness audits across public hospitals (Damascus Hospital, Al-Mowasat Hospital), ministry-level presentations on national AI adoption roadmap. Deployed bilingual (Arabic/English) administrative dashboard for **200+ employees across 22 facilities** with employee management, project oversight, real-time Plotly analytics, and operational alerts.

#### 📚 AI Education & Mentorship
Designed and delivered comprehensive AI curriculum. Trained **11 students** to full AI engineering proficiency. Mentored **2 high school students** to build a 90%+ accurate heart disease detection model. Founded mentorship program at Damascus University (50+ attendees per workshop). Workshops on Agentic AI, System Prompt Engineering, Full-Stack (React+AI), Back-End, and Mobile Development (Flutter & React Native).

---

## 📊 GitHub Stats

![Mohamad's GitHub stats](https://github-readme-stats.vercel.app/api?username=M0-AR&show_icons=true&theme=algolia&hide=prs,issues&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=M0-AR&layout=compact&theme=algolia)

---

## 📌 Pinned Repositories

- [LLM-From-Zero-to-Hero](https://github.com/M0-AR/LLM-From-Zero-to-Hero) — Comprehensive hands-on curriculum for mastering LLMs from absolute beginner to production practitioner


---

## 📈 Activity

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=M0-AR&theme=algolia)
![Profile Views](https://komarev.com/ghpvc/?username=M0-AR&color=blueviolet)

---

## 🏆 GitHub Trophies

![Trophy](https://github-profile-trophy.vercel.app/?username=M0-AR&theme=algolia&column=-1&no-frame=true&no-bg=false)

---

*"Building AI that ships — from hospital wards to Kubernetes clusters."*
