<div align="center">

  <h1>🧬 NutriScan AI</h1>
  <h3><i>Clinical Malnutrition Surveillance & Biometric Intelligence Platform</i></h3>

  <p align="center">
    <a href="https://www.who.int/tools/child-growth-standards"><img src="https://img.shields.io/badge/WHO_Standards-100%25_Compliant-06B6D4?style=for-the-badge&logo=worldhealthorganization&logoColor=white" alt="WHO Standards"></a>
    <a href="https://hono.dev/"><img src="https://img.shields.io/badge/Runtime-Hono_v4-FF6B00?style=for-the-badge&logo=hono&logoColor=white" alt="Hono Runtime"></a>
    <a href="https://workers.cloudflare.com/"><img src="https://img.shields.io/badge/Edge-Cloudflare_D1-F97316?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare D1"></a>
    <a href="https://www.tensorflow.org/js"><img src="https://img.shields.io/badge/AI_Engine-TensorFlow.js-8B5CF6?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow.js"></a>
    <a href="https://ai.google.dev/"><img src="https://img.shields.io/badge/Reasoning-Gemini_2.0_Flash-EC4899?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Google Gemini"></a>
    <a href="https://pptr.dev/"><img src="https://img.shields.io/badge/Export-Puppeteer_PDF-10B981?style=for-the-badge&logo=puppeteer&logoColor=white" alt="Puppeteer"></a>
  </p>

  <br />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=23&pause=1000&color=06B6D4&center=true&vCenter=true&width=780&lines=AI-Powered+Anthropometric+Biometric+Diagnostics;Real-Time+WHO+Z-Score+(WHZ%2C+HAZ%2C+WAZ)+Analytics;Privacy-First+On-Device+Limb+%26+Pose+Landmark+Detection;Therapeutic+Nutritional+Blueprint+%26+Diet+Generation;Sub-Millisecond+Edge+Deployment+via+Cloudflare+Global+Network" alt="Typing Banner" />
  </a>

  <br />

  <p align="center">
    <b>Next-generation clinical decision support transforming standard camera optics into a precision pediatric biometric diagnostic workstation.</b>
  </p>

  <p align="center">
    <a href="#-executive-summary"><b>Executive Summary</b></a> •
    <a href="#-core-capabilities"><b>Core Capabilities</b></a> •
    <a href="#-diagnostic-classification-matrix"><b>Z-Score Matrix</b></a> •
    <a href="#-system-architecture"><b>Architecture</b></a> •
    <a href="#-technology-stack"><b>Tech Stack</b></a> •
    <a href="#-developer-execution-guide"><b>Execution Guide</b></a>
  </p>

</div>

<br />

> [!NOTE]
> ### 💡 Platform Highlights
> - **Biometric Intelligence:** On-device computer vision analyzing anatomical wasting markers in real-time.
> - **WHO Matrix Normalization:** Automated computation of **WHZ**, **HAZ**, and **WAZ** standard statistical scores.
> - **Edge Serverless Infrastructure:** Sub-millisecond global execution powered by **Hono.js** and **Cloudflare D1**.

<br />

---

## ⚡ Executive Summary

Childhood malnutrition represents a critical global healthcare emergency. In field clinics and low-resource medical environments, early wasting indicators frequently go undetected due to subtle physical manifestations and manual z-score calculation workloads.

**NutriScan AI** transforms everyday webcams and mobile cameras into a **high-precision clinical diagnostic suite**. Combining client-side pose estimation with official **WHO Growth Standards** and **Google Gemini AI** clinical reasoning, NutriScan AI empowers medical staff with instant diagnostic clarity.

<br />

> [!CAUTION]
> ### 🚨 The Clinical Challenge
> - **Undetected Wasting:** Early-stage acute malnutrition (limb circumference loss, subtle rib prominence) slips past routine visual inspection.
> - **Manual Calculation Errors:** Human error during manual WHO growth chart cross-referencing causes misclassified triage priority.
> - **Fragmented Tracking:** High drop-off rate during multi-week therapeutic feeding recovery cycles.

<br />

> [!TIP]
> ### 🛡️ The NutriScan AI Solution
> - **Biometric Vision Scan:** Sub-millimeter landmark extraction via `TensorFlow.js` running 100% locally in-browser for total patient privacy.
> - **Automated WHO Engine:** Instant mathematical evaluation of Z-scores with automatic triaging into ![SAM](https://img.shields.io/badge/SAM-Severe_Malnutrition-DC2626?style=flat-square), ![MAM](https://img.shields.io/badge/MAM-Moderate_Malnutrition-F59E0B?style=flat-square), or ![NORMAL](https://img.shields.io/badge/NORMAL-Healthy-10B981?style=flat-square).
> - **Generative Diet Blueprints:** Tailored therapeutic feeding protocols (`RUTF`, `F75`, `F100`) synthesized via `Google Gemini 2.0` AI reasoning.

<br />

---

## ✨ Core Capabilities

<br />

### 🔍 1. Biometric Computer Vision Engine
> [!IMPORTANT]
> **Privacy-First On-Device AI Execution**  
> All computer vision processing happens on the client device using `TensorFlow.js` (`MoveNet` / `MobileNet`). Zero patient images are uploaded or transmitted.

* **Anatomical Landmark Extraction:** Measures limb ratios, rib cage prominence, and facial tissue volume.
* **Optical Quality Validation:** Automatically assesses ambient lighting and camera angle before starting diagnostics.

<br />

### 📐 2. Precision WHO Anthropometric Calculator
* **Multi-Vector Normalization:** Evaluates ![WHZ](https://img.shields.io/badge/WHZ-Weight_for_Height-06B6D4?style=flat-square) ![HAZ](https://img.shields.io/badge/HAZ-Height_for_Age-8B5CF6?style=flat-square) ![WAZ](https://img.shields.io/badge/WAZ-Weight_for_Age-EC4899?style=flat-square) scores simultaneously.
* **Confidence Scoring:** Outputs statistical confidence metrics alongside full clinical logic breakdowns.

<br />

### 🍱 3. Generative Therapeutic Nutrition Generator
* **AI Clinical Synthesis:** Leverages `Google Gemini 2.0` to generate customized caloric, fluid, and micronutrient schedules.
* **WHO Therapeutic Standards:** Formulates specific feeding plans featuring ![RUTF](https://img.shields.io/badge/RUTF-Ready_to_Use_Food-FF6B00?style=flat-square), ![F75](https://img.shields.io/badge/F75-Therapeutic_Milk-10B981?style=flat-square), and ![F100](https://img.shields.io/badge/F100-Rehab_Milk-06B6D4?style=flat-square).

<br />

### 📄 4. Clinical Export & Patient History Hub
* **PDF Report Compiler:** Serverless Headless Chrome via `Puppeteer` builds print-ready medical records.
* **Edge Relational Database:** High-speed patient record storage on `Cloudflare D1` (SQLite) via type-safe `Kysely` queries.

<br />

---

## 📐 Diagnostic Classification Matrix

NutriScan AI evaluates patient anthropometrics against standardized **WHO Growth Matrices (0–60 Months)**:

<div align="center">

| Metric Index | Target Indicator | Severity Threshold | Triage Status | Clinical Action Plan |
| :---: | :---: | :---: | :---: | :--- |
| **WHZ** | Weight-for-Height | `< -3 SD` | ![SAM](https://img.shields.io/badge/CRITICAL-SAM-DC2626?style=for-the-badge) | Immediate Outpatient / Inpatient RUTF Medical Protocol |
| **WHZ** | Weight-for-Height | `-3 SD to -2 SD` | ![MAM](https://img.shields.io/badge/WARNING-MAM-F59E0B?style=for-the-badge) | Targeted Supplementary Feeding & Bi-weekly Checkups |
| **HAZ** | Height-for-Age | `< -2 SD` | ![STUNTING](https://img.shields.io/badge/ALERT-STUNTING-8B5CF6?style=for-the-badge) | Chronic Stunting Intervention & Micronutrient Protocol |
| **WAZ** | Weight-for-Age | `< -2 SD` | ![UNDERWEIGHT](https://img.shields.io/badge/NOTICE-UNDERWEIGHT-06B6D4?style=for-the-badge) | Pediatric Caloric Supplementation & Growth Tracking |
| **WHZ** | Weight-for-Height | `>= -2 SD` | ![NORMAL](https://img.shields.io/badge/OPTIMAL-NORMAL-10B981?style=for-the-badge) | Routine Standard Pediatric Care & Monitoring |

</div>

<br />

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    %% Custom Colored Nodes
    classDef client fill:#0F172A,stroke:#06B6D4,stroke-width:2px,color:#F8FAFC;
    classDef edge fill:#1E1B4B,stroke:#8B5CF6,stroke-width:2px,color:#F8FAFC;
    classDef ai fill:#27005D,stroke:#EC4899,stroke-width:2px,color:#F8FAFC;
    classDef storage fill:#064E3B,stroke:#10B981,stroke-width:2px,color:#F8FAFC;

    subgraph Client ["💻 Client Terminal (Browser / Camera)"]
        Cam["📷 Optical Capture Engine"]
        TFJS["⚡ TensorFlow.js Landmark Detection"]
        Privacy["🔒 Privacy Guard (Local Processing)"]
        Cam --> TFJS --> Privacy
    end

    subgraph EdgeGateway ["🌐 Cloudflare Workers Edge Network"]
        Hono["🔥 Hono.js Router & Middleware"]
        WHOEngine["📐 WHO Z-Score Analytics (WHZ / HAZ / WAZ)"]
        TriageEngine["🏷️ Severity Triaging (SAM / MAM / Normal)"]
        Hono --> WHOEngine --> TriageEngine
    end

    subgraph Intelligence ["🧠 AI Synthesis Engine"]
        Gemini["✨ Google Gemini 2.0 LLM"]
        DietPlanner["🍱 Therapeutic Diet Blueprint Generator"]
        Gemini --> DietPlanner
    end

    subgraph Storage ["🗄️ Persistence & Document Engine"]
        D1[("🗃️ Cloudflare D1 SQLite Database")]
        Puppeteer["📄 Puppeteer PDF Export Engine"]
    end

    Privacy -->|Extracted Biometric Vectors| Hono
    TriageEngine -->|Diagnostic Context Payload| Gemini
    DietPlanner -->|Nutritional Blueprint| Hono
    Hono -->|Structured Patient Record| D1
    Hono -->|Export Task| Puppeteer

    class Client client;
    class EdgeGateway edge;
    class Intelligence ai;
    class Storage storage;
```

<br />

---

## 🛠️ Technology Stack

<div align="center">

| System Layer | Technology | Function in NutriScan AI | Palette |
| :--- | :--- | :--- | :---: |
| **Framework & Runtime** | ![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white) ![Hono](https://img.shields.io/badge/Hono_v4-E36002?style=flat-square&logo=hono&logoColor=white) | Sub-millisecond serverless API route handler | `🔥 Orange` |
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript_5.0-3178C6?style=flat-square&logo=typescript&logoColor=white) | Strict type safety across client, edge & database | `⚡ Blue` |
| **Computer Vision** | ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) | On-device anatomical pose landmark tracking | `🧠 Amber` |
| **Generative AI** | ![Google Gemini](https://img.shields.io/badge/Google_Gemini_AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white) | Clinical reasoning & meal blueprint synthesis | `✨ Cyan` |
| **Database** | ![Cloudflare D1](https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white) | Edge serverless relational SQLite data store | `🌐 Orange` |
| **Document Export** | ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white) | High-fidelity clinical PDF certificate generation | `📄 Green` |
| **Clinical Base** | ![WHO](https://img.shields.io/badge/WHO_Growth_Standards-008080?style=flat-square&logo=worldhealthorganization&logoColor=white) | Official WHO child growth reference matrices | `🩺 Teal` |

</div>

<br />

---

## 💻 Developer & Execution Guide

### Local Environment Setup

```bash
# 1. Clone the project repository
git clone https://github.com/your-username/nutriscan-ai.git
cd nutriscan-ai

# 2. Install all dependencies
npm install

# 3. Configure local environment variables (.env)
echo "GEMINI_API_KEY=your_google_gemini_api_key" > .env

# 4. Apply local D1 database migrations & seed dataset
npm run db:migrate:local
npm run db:seed

# 5. Launch Vite development server
npm run dev
```

> Open interactive client suite at **`http://localhost:5173`**

---

### Command Reference

```json
{
  "npm run dev": "Start Vite local development server",
  "npm run dev:sandbox": "Run Cloudflare Pages sandbox environment with local D1 bindings",
  "npm run build": "Compile application assets for production deployment",
  "npm run db:migrate:local": "Apply migrations to local SQLite D1 database",
  "npm run db:migrate:prod": "Apply migrations to production Cloudflare D1 database",
  "npm run deploy": "Build and deploy directly to Cloudflare Pages"
}
```

<br />

---

<div align="center">

  <br />

  <p align="center">
    <img src="https://img.shields.io/badge/NutriScan_AI-Clinical_Surveillance_Suite-06B6D4?style=for-the-badge&logo=dna&logoColor=white" alt="NutriScan AI">
    <img src="https://img.shields.io/badge/Status-Active_Development-10B981?style=for-the-badge&logo=github&logoColor=white" alt="Status">
    <img src="https://img.shields.io/badge/Impact-Global_Child_Health-8B5CF6?style=for-the-badge&logo=heart&logoColor=white" alt="Impact">
  </p>

  <h3>🧬 NutriScan AI</h3>
  <p><b>Transforming Optical Sensors into Life-Saving Biometric Diagnostic Tools</b></p>

  <p>
    Built with dedication for pediatric health equity across global health communities.
  </p>

  <sub>© NutriScan AI • Powered by Hono, TensorFlow.js, Google Gemini & Cloudflare Workers</sub>

  <br/><br/>

</div>
