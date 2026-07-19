<div align="center">

  <h1><font color="#06B6D4">🧬 NutriScan AI</font></h1>
  <h3><font color="#EC4899"><i>Clinical Malnutrition Surveillance & Biometric Intelligence Platform</i></font></h3>

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
    <font color="#38BDF8"><b>Next-generation clinical decision support transforming standard camera optics into a precision pediatric biometric diagnostic workstation.</b></font>
  </p>

  <p align="center">
    <a href="#-executive-summary"><font color="#06B6D4"><b>Executive Summary</b></font></a> •
    <a href="#-core-capabilities"><font color="#EC4899"><b>Core Capabilities</b></font></a> •
    <a href="#-diagnostic-classification-matrix"><font color="#F59E0B"><b>Z-Score Matrix</b></font></a> •
    <a href="#-system-architecture"><font color="#8B5CF6"><b>Architecture</b></font></a> •
    <a href="#-technology-stack"><font color="#10B981"><b>Tech Stack</b></font></a> •
    <a href="#-developer-execution-guide"><font color="#38BDF8"><b>Execution Guide</b></font></a>
  </p>

  <sub><font color="#94A3B8">Engineering diagnostic accuracy for field clinicians, healthcare workers, and global health organizations.</font></sub>

</div>

<br />

---

## <font color="#06B6D4">⚡ Executive Summary</font>

Malnutrition in early childhood remains a critical global health challenge. In resource-constrained clinical settings, early visual wasting indicators are frequently overlooked due to subtle physical manifestations and manual Z-score calculation burdens.

<font color="#38BDF8"><b>NutriScan AI</b></font> bridges this critical healthcare gap by converting standard webcams and smartphone cameras into an <font color="#EC4899"><b>AI-assisted biometric diagnostic workstation</b></font>. Fusing on-device pose estimation with official <font color="#F59E0B"><b>WHO Child Growth Standards</b></font> and <font color="#8B5CF6"><b>Google Gemini AI</b></font> clinical reasoning, the system generates instant, reliable anthropometric assessments and custom therapeutic nutrition protocols.

<br />

<table width="100%">
  <tr>
    <td width="50%" valign="top" style="background-color: #1a1016; border: 1px solid #EC4899;">
      <h3 align="center"><font color="#F43F5E">🚨 The Clinical Challenge</font></h3>
      <ul>
        <li><font color="#FB7185"><b>Undetected Wasting:</b></font> Early-stage acute malnutrition (limb thinning, facial muscle atrophy) often escapes conventional observation.</li>
        <li><font color="#FB7185"><b>Manual Calculation Errors:</b></font> Human miscalculations in WHZ/HAZ/WAZ Z-score tables leading to misclassified triage urgency.</li>
        <li><font color="#FB7185"><b>Data Fragmentations:</b></font> Difficulty maintaining longitudinal patient growth curves during multi-week therapeutic feeding cycles.</li>
      </ul>
    </td>
    <td width="50%" valign="top" style="background-color: #0c1a1a; border: 1px solid #06B6D4;">
      <h3 align="center"><font color="#38BDF8">🛡️ The NutriScan AI Solution</font></h3>
      <ul>
        <li><font color="#2DD4BF"><b>Biometric Computer Vision:</b></font> Sub-millimeter anatomical landmark extraction using TensorFlow.js (MoveNet/MobileNet) directly in browser.</li>
        <li><font color="#2DD4BF"><b>Automated WHO Engine:</b></font> Instant math computation of Z-scores with automatic triaging into SAM, MAM, or Normal classifications.</li>
        <li><font color="#2DD4BF"><b>Generative Diet Blueprints:</b></font> Tailored therapeutic feeding protocols (RUTF, F75, F100) generated via Gemini AI reasoning.</li>
      </ul>
    </td>
  </tr>
</table>

<br />

---

## <font color="#EC4899">✨ Core Capabilities</font>

<br />

### <font color="#06B6D4">🔍 1. Biometric Computer Vision Engine</font>
* <font color="#38BDF8"><b>Anatomical Landmark Scan:</b></font> Extracts key physical points to measure limb proportions, rib cage prominence, and facial tissue volume.
* <font color="#38BDF8"><b>Privacy-Preserving Execution:</b></font> Runs entirely on-device via TensorFlow.js. Zero patient imagery leaves the local browser terminal.
* <font color="#38BDF8"><b>Lighting & Angle Auto-Validation:</b></font> Ensures optical capture quality satisfies clinical accuracy threshold before diagnostic evaluation.

<br />

### <font color="#F59E0B">📐 2. Precision WHO Anthropometric Calculator</font>
* <font color="#FBBF24"><b>Multi-Vector Z-Scores:</b></font> Simultaneously evaluates <font color="#38BDF8"><b>WHZ</b></font> (Weight-for-Height), <font color="#EC4899"><b>HAZ</b></font> (Height-for-Age), and <font color="#8B5CF6"><b>WAZ</b></font> (Weight-for-Age).
* <font color="#FBBF24"><b>Instant Risk Triaging:</b></font> Automates categorization into <font color="#F43F5E"><b>SAM</b></font> (Severe Acute Malnutrition), <font color="#F59E0B"><b>MAM</b></font> (Moderate Acute Malnutrition), or <font color="#10B981"><b>Normal</b></font>.
* <font color="#FBBF24"><b>Confidence Rating:</b></font> Outputs a statistical confidence score and diagnostic rationale breakdown for clinician verification.

<br />

### <font color="#8B5CF6">🍱 3. Generative Therapeutic Nutrition Generator</font>
* <font color="#C084FC"><b>Protocol Synthesis:</b></font> Leverages Google Gemini 2.0 API to formulate customized caloric intake targets and micronutrient schedules.
* <font color="#C084FC"><b>WHO Dietary Formulations:</b></font> Recommends specific ready-to-use therapeutic food plans including <font color="#EC4899"><b>RUTF</b></font>, <font color="#F59E0B"><b>F-75</b></font>, and <font color="#06B6D4"><b>F-100</b></font> milk diets.
* <font color="#C084FC"><b>Longitudinal Cycle Rules:</b></font> Calculates intervention duration, dietary restriction flags, and scheduled follow-up milestones.

<br />

### <font color="#10B981">📄 4. Clinical Export & Patient History Hub</font>
* <font color="#34D399"><b>PDF Report Generation:</b></font> Serverless Headless Chrome via `Puppeteer` compiles diagnostic certificates, patient details, and growth charts.
* <font color="#34D399"><b>Edge Storage Hub:</b></font> Relational patient database built on Cloudflare D1 (SQLite) with type-safe Kysely ORM queries.
* <font color="#34D399"><b>Longitudinal Trends:</b></font> Visualizes historical recovery trajectories to track treatment efficacy over time.

<br />

---

## <font color="#F59E0B">📐 Diagnostic Classification Matrix</font>

NutriScan AI evaluates anthropometric inputs against standardized <font color="#06B6D4"><b>WHO Child Growth Matrices (0–60 Months)</b></font> to instantly compute patient severity:

<div align="center">

| Metric Index | Target Indicator | Severity Threshold | Triage Status | Clinical Action Required |
| :---: | :---: | :---: | :---: | :--- |
| <font color="#06B6D4"><b>WHZ</b></font> | Weight-for-Height | `< -3 SD` | <img src="https://img.shields.io/badge/CRITICAL-SAM-DC2626?style=for-the-badge" alt="SAM"> | <font color="#F43F5E"><b>Immediate Inpatient / Outpatient RUTF & Medical Protocol</b></font> |
| <font color="#06B6D4"><b>WHZ</b></font> | Weight-for-Height | `-3 SD to -2 SD` | <img src="https://img.shields.io/badge/WARNING-MAM-F59E0B?style=for-the-badge" alt="MAM"> | <font color="#F59E0B"><b>Targeted Supplementary Feeding & Bi-weekly Monitoring</b></font> |
| <font color="#EC4899"><b>HAZ</b></font> | Height-for-Age | `< -2 SD` | <img src="https://img.shields.io/badge/ALERT-STUNTING-8B5CF6?style=for-the-badge" alt="Stunting"> | <font color="#C084FC"><b>Chronic Malnutrition Protocol & Micronutrient Therapy</b></font> |
| <font color="#8B5CF6"><b>WAZ</b></font> | Weight-for-Age | `< -2 SD` | <img src="https://img.shields.io/badge/NOTICE-UNDERWEIGHT-06B6D4?style=for-the-badge" alt="Underweight"> | <font color="#38BDF8"><b>Comprehensive Nutritional Support & Growth Tracking</b></font> |
| <font color="#10B981"><b>WHZ</b></font> | Weight-for-Height | `>= -2 SD` | <img src="https://img.shields.io/badge/OPTIMAL-NORMAL-10B981?style=for-the-badge" alt="Normal"> | <font color="#34D399"><b>Routine Wellness Check & Standard Pediatric Diet</b></font> |

</div>

<br />

---

## <font color="#8B5CF6">🏗️ System Architecture</font>

The following diagram illustrates the complete end-to-end data pipeline:

```mermaid
flowchart TD
    %% Custom Vibrant Node Styling
    classDef client fill:#0f172a,stroke:#06B6D4,stroke-width:2px,color:#fff;
    classDef edge fill:#1e1b4b,stroke:#8B5CF6,stroke-width:2px,color:#fff;
    classDef ai fill:#27005D,stroke:#EC4899,stroke-width:2px,color:#fff;
    classDef persistence fill:#064E3B,stroke:#10B981,stroke-width:2px,color:#fff;

    subgraph Client ["💻 Client Terminal (Browser / Camera)"]
        Cam["📷 Optical Video Acquisition"]
        TFJS["⚡ TensorFlow.js Landmark Detection"]
        Privacy["🔒 Privacy Guard (On-Device Extraction)"]
        Cam --> TFJS --> Privacy
    end

    subgraph EdgeGateway ["🌐 Cloudflare Workers Edge Network"]
        Hono["🔥 Hono.js Router & Middleware"]
        WHOEngine["📐 WHO Z-Score Analytics (WHZ / HAZ / WAZ)"]
        TriageEngine["🏷️ Severity Classification (SAM / MAM / Normal)"]
        Hono --> WHOEngine --> TriageEngine
    end

    subgraph Intelligence ["🧠 AI Clinical Synthesis"]
        Gemini["✨ Google Gemini 2.0 API"]
        DietPlanner["🍱 Therapeutic Diet & Blueprint Generator"]
        Gemini --> DietPlanner
    end

    subgraph Storage ["🗄️ Persistence & Document Engine"]
        D1[("🗃️ Cloudflare D1 SQLite Database")]
        Puppeteer["📄 Puppeteer PDF Export"]
    end

    Privacy -->|Extracted Biometric Vectors| Hono
    TriageEngine -->|Diagnostic Context Payload| Gemini
    DietPlanner -->|Nutritional Plan| Hono
    Hono -->|Structured Patient Record| D1
    Hono -->|Export Request| Puppeteer

    class Client client;
    class EdgeGateway edge;
    class Intelligence ai;
    class Storage persistence;
```

<br />

---

## <font color="#10B981">🛠️ Technology Stack</font>

<div align="center">

| Ecosystem Layer | Core Technology | Primary Functionality |
| :--- | :--- | :--- |
| <font color="#FF6B00"><b>App & Runtime</b></font> | ![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white) ![Hono](https://img.shields.io/badge/Hono_v4-E36002?style=flat-square&logo=hono&logoColor=white) | Sub-millisecond serverless routing & Vite build system |
| <font color="#38BDF8"><b>Language</b></font> | ![TypeScript](https://img.shields.io/badge/TypeScript_5.0-3178C6?style=flat-square&logo=typescript&logoColor=white) | Strict end-to-end type safety across API & Database |
| <font color="#8B5CF6"><b>Computer Vision</b></font> | ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) | Pose estimation & anatomical landmark extraction |
| <font color="#EC4899"><b>Generative AI</b></font> | ![Google Gemini](https://img.shields.io/badge/Google_Gemini_AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white) | AI-assisted medical reasoning & dietary synthesis |
| <font color="#F97316"><b>Edge Storage</b></font> | ![Cloudflare D1](https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white) | Global serverless relational SQLite database |
| <font color="#10B981"><b>Document Export</b></font> | ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white) | High-resolution PDF clinical report compiler |
| <font color="#06B6D4"><b>Clinical Standard</b></font> | ![WHO](https://img.shields.io/badge/WHO_Growth_Standards-008080?style=flat-square&logo=worldhealthorganization&logoColor=white) | Standardized WHO growth charts (0–60 Months) |

</div>

<br />

---

## <font color="#38BDF8">💻 Developer & Execution Guide</font>

### <font color="#06B6D4">Environment Prerequisites</font>
* **Node.js**: `v18.0.0` or higher
* **Package Manager**: `npm` v9+
* **Cloudflare CLI**: `wrangler` v4+

---

### <font color="#EC4899">Step-by-Step Local Quickstart</font>

```bash
# 1. Clone the project repository
git clone https://github.com/your-username/nutriscan-ai.git
cd nutriscan-ai

# 2. Install all required dependencies
npm install

# 3. Set up environment variables (.env)
echo "GEMINI_API_KEY=your_google_gemini_api_key" > .env

# 4. Initialize local SQLite D1 database and seed test dataset
npm run db:migrate:local
npm run db:seed

# 5. Start the local Vite development server
npm run dev
```

> <font color="#38BDF8">Access the interactive terminal at</font> **`http://localhost:5173`**

---

### <font color="#F59E0B">Command Palette Reference</font>

```bash
npm run dev               # Start local Vite development server
npm run dev:sandbox       # Start local Wrangler Pages sandbox with D1 SQLite bindings
npm run build             # Build production static bundle
npm run db:migrate:local  # Apply migrations to local D1 database
npm run db:migrate:prod   # Apply migrations to production Cloudflare D1
npm run deploy            # Build and deploy directly to Cloudflare Pages
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

  <h2><font color="#06B6D4">🧬 NutriScan AI</font></h2>
  <p><font color="#EC4899"><b>Transforming Optical Sensors into Life-Saving Biometric Diagnostic Tools</b></font></p>

  <p>
    <font color="#38BDF8">Built with passion for pediatric health equity across underserved global communities.</font>
  </p>

  <sub><font color="#94A3B8">© NutriScan AI • Powered by Hono, TensorFlow.js, Google Gemini & Cloudflare Workers</font></sub>

  <br/><br/>

</div>
