<div align="center">

# 👋 Hi, I'm Metin Taşçı

### CTO • Software Architect • Product Builder

I design and build secure, local-first and AI-powered software platforms.

My work focuses on:

**Local AI Infrastructure • Autonomous Testing • Legal AI • System Monitoring • Secure Software Architecture**

[![Website](https://img.shields.io/badge/Website-alafteknoloji.com-black?style=for-the-badge)](https://alafteknoloji.com)
[![GitHub](https://img.shields.io/badge/GitHub-mtntasci-181717?style=for-the-badge&logo=github)](https://github.com/mtntasci)

</div>

---

## 🏗️ Product Ecosystem

```mermaid
flowchart TD
    MT["👨‍💻 Metin Taşçı<br/>CTO & Software Architect"]

    MT --> ALAF["🏢 ALAF Technology"]
    MT --> SOM["🛡️ SOM Defense"]

    ALAF --> NODE["🧠 AlafNode<br/>Local AI Control Plane"]
    ALAF --> CORE["🖥️ AlafCore<br/>System Monitoring"]
    ALAF --> LEGAL["⚖️ ALAF Legal<br/>Legal Intelligence"]

    SOM --> TEST["🛡️ SOMTest<br/>Autonomous Software Testing"]

    NODE --> LLM["🤖 Local LLMs"]
    NODE --> AGENT["⚙️ Go Agent"]
    NODE --> PANEL["🌐 Web Control Panel"]

    CORE --> MONITORING["📊 Hardware & System Telemetry"]
    LEGAL --> RAG["📚 Private RAG & Document Analysis"]
    TEST --> QA["✅ Quality, Security & Compliance"]
```

---

# 🧠 **AlafNode**

> **A production-oriented local AI infrastructure platform for deploying, pairing and managing private AI nodes.**

AlafNode provides a centralized control plane for running and managing local artificial intelligence infrastructure without sending sensitive data outside the organization.

### Key Capabilities

- Secure node registration and pairing
- Local LLM deployment and management
- Ollama integration
- Remote node monitoring
- Agent-based system control
- Private and local-first AI architecture
- Centralized web management panel
- Secure communication between nodes
- Multi-node infrastructure support

### Architecture

```mermaid
flowchart LR
    USER["👤 Administrator"]
    PANEL["🌐 Next.js Control Panel"]
    FIREBASE["🔥 Firebase"]
    AGENT["⚙️ Go Agent"]
    OLLAMA["🤖 Ollama"]
    MODELS["🧠 Local AI Models"]
    SERVER["🖥️ Linux / macOS Node"]

    USER --> PANEL
    PANEL --> FIREBASE
    FIREBASE --> AGENT
    AGENT --> SERVER
    AGENT --> OLLAMA
    OLLAMA --> MODELS

    SERVER -. Telemetry .-> AGENT
    AGENT -. Status & Metrics .-> PANEL
```

> **Core technologies:** Next.js, TypeScript, Go, Firebase, Ollama, Linux, Local LLMs

---

# 🖥️ **AlafCore**

> **A lightweight infrastructure and hardware monitoring ecosystem designed specifically for Apple Silicon and local AI systems.**

AlafCore provides visibility into system health, hardware resources and local AI workloads.

### Key Capabilities

- CPU, RAM and storage monitoring
- Apple Silicon system telemetry
- Local AI workload observation
- Hardware health monitoring
- Resource utilization tracking
- Node-level observability
- Infrastructure status reporting
- Lightweight monitoring architecture

```mermaid
flowchart TD
    DEVICE["🖥️ Apple Silicon / Server"]
    COLLECTOR["📡 AlafCore Collector"]
    METRICS["📊 System Metrics"]
    AI["🤖 Local AI Workloads"]
    DASHBOARD["🌐 Monitoring Dashboard"]
    ALERTS["🚨 Health Alerts"]

    DEVICE --> COLLECTOR
    COLLECTOR --> METRICS
    COLLECTOR --> AI
    METRICS --> DASHBOARD
    AI --> DASHBOARD
    DASHBOARD --> ALERTS
```

> **Core technologies:** Go, Swift, TypeScript, macOS, Linux, Apple Silicon, System Telemetry

---

# 🛡️ **SOMTest**

> **A local-first software quality and security platform designed for high-assurance and regulated environments.**

SOMTest automates software testing, security analysis and compliance reporting while keeping source code inside the organization.

### Key Capabilities

- Autonomous test generation
- Static code analysis
- Security testing
- Code coverage analysis
- Traceability reporting
- Local AI-assisted testing
- Zero-trust architecture
- Private source code processing
- Compliance-oriented reporting

### Target Standards

- DO-178C
- MIL-STD-498
- DISA STIG
- Secure software development practices
- High-assurance quality processes

```mermaid
flowchart LR
    SOURCE["💻 Source Code"]
    ENGINE["🛡️ SOMTest Engine"]
    AI["🤖 Local AI"]
    TESTS["🧪 Automated Tests"]
    SECURITY["🔐 Security Analysis"]
    COVERAGE["📈 Code Coverage"]
    REPORTS["📄 Compliance Reports"]

    SOURCE --> ENGINE
    ENGINE --> AI
    AI --> TESTS
    ENGINE --> SECURITY
    ENGINE --> COVERAGE
    TESTS --> REPORTS
    SECURITY --> REPORTS
    COVERAGE --> REPORTS
```

> **Core technologies:** Local LLMs, Static Analysis, Automated Testing, Security Testing, Compliance Reporting

---

# ⚖️ **ALAF Legal**

> **An AI-assisted legal intelligence platform built around private deployment, source-grounded responses and auditable outputs.**

ALAF Legal is designed to analyze legal documents, retrieve relevant decisions and produce traceable AI-assisted outputs.

### Key Capabilities

- Legal document analysis
- Private RAG infrastructure
- Source-grounded AI responses
- Similar case and precedent retrieval
- Large document summarization
- Petition and defense draft assistance
- Auditable outputs
- Institution-level data isolation
- Local and private deployment

```mermaid
flowchart TD
    DOCUMENTS["📚 Legal Documents"]
    INGESTION["📥 Document Ingestion"]
    INDEX["🧠 Private Knowledge Index"]
    LLM["🤖 Local Legal AI"]
    SEARCH["🔎 Precedent Search"]
    ANSWER["📝 Grounded Response"]
    SOURCES["📎 Source Citations"]

    DOCUMENTS --> INGESTION
    INGESTION --> INDEX
    INDEX --> LLM
    INDEX --> SEARCH
    SEARCH --> LLM
    LLM --> ANSWER
    ANSWER --> SOURCES
```

> **Core technologies:** RAG, Local LLMs, Vector Search, Document Analysis, Legal AI, Private Infrastructure

---

# 🚀 **Additional Product Work**

### SOM Crypto

A non-custodial cryptocurrency wallet focused on Ethereum and USDT transactions.

- React Native
- Biometric and PIN protection
- QR-based transactions
- Testnet and mainnet support
- Secure local wallet architecture

### AI-Powered Defense Systems

Research and product development involving:

- Computer vision
- Autonomous systems
- Drone technologies
- Facial recognition
- Secure edge AI
- Local inference infrastructure

### Enterprise AI Platforms

Development of private AI systems for:

- Document analysis
- Internal knowledge retrieval
- Software quality assurance
- Infrastructure management
- Regulated and high-security environments

---

## 🧩 Engineering Approach

```mermaid
mindmap
  root((Engineering Principles))
    Local First
      Private Data
      Offline Capability
      Local LLMs
    Security
      Zero Trust
      Least Privilege
      Secure Pairing
    Architecture
      Modular Systems
      Control Plane
      Agent Based Design
    Quality
      Automated Testing
      Observability
      Traceability
    Product
      Real Problems
      Scalable Platforms
      Enterprise Ready
```

---

## 🛠️ Technology Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

### Frontend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Backend & Infrastructure

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Artificial Intelligence

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

---

## 📍 Current Focus

```mermaid
timeline
    title Product Development Focus

    Local AI Infrastructure
        : AlafNode
        : Private LLM Management
        : Secure Node Architecture

    Software Quality
        : SOMTest
        : Autonomous Testing
        : Compliance Automation

    Legal Intelligence
        : ALAF Legal
        : Private RAG
        : Source-Grounded AI

    Infrastructure
        : AlafCore
        : Apple Silicon Monitoring
        : Local AI Observability
```

---

## 🤝 Leadership

As a CTO and product architect, I focus on turning complex technical requirements into reliable and commercially viable software platforms.

My responsibilities include:

- Product and technology strategy
- Software architecture
- AI infrastructure design
- Engineering team leadership
- Security and privacy architecture
- Technical research and development
- Enterprise and defense technology projects
- Product delivery from concept to production

---

## 📊 GitHub Statistics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mtntasci&show_icons=true&hide_border=true&theme=github_dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mtntasci&layout=compact&hide_border=true&theme=github_dark)

![GitHub Streak](https://streak-stats.demolab.com?user=mtntasci&theme=github-dark-blue&hide_border=true)

</div>

---

<div align="center">

## 📫 Contact

**Alaf Teknoloji Savunma Sanayi ve Havacılık A.Ş.**

🌐 [alafteknoloji.com](https://alafteknoloji.com)

💻 [github.com/mtntasci](https://github.com/mtntasci)

---

### Building secure, private and intelligent systems.

</div>
