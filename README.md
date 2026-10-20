<!-- ========================================================= -->
<!--                         SMAQR                             -->
<!--              SMART ACCESS. INTELLIGENT RETAIL.             -->
<!-- ========================================================= -->

<div align="center">

<!-- Animated Header Banner with Dynamic Wave & Glowing Particle FX -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:4285F4,25:EA4335,50:FBBC05,75:34A853,100:4285F4&fontColor=FFFFFF&text=SMAQR&fontSize=72&fontAlignY=38&animation=twinkle&desc=Smart%20Access.%20Intelligent%20Retail.&descSize=20&descAlignY=62" alt="SMAQR Banner"/>

<br/>

<p align="center">
  <a href="https://github.com">
    <img src="https://readme-typing-svg.demolab.com?font=Google+Sans+Display&weight=600&size=24&duration=3000&pause=1000&color=4285F4&center=true&vCenter=true&width=600&height=50&lines=A+New+Perspective+on+Retail.;Scan.+Shop.+Checkout.+Verify.;Powered+by+FastAPI+%2B+PostgreSQL." alt="Typing Subtitle" />
  </a>
</p>

<!-- Pill Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/BACKEND-FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/ENGINE-PYTHON%203.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/DATABASE-POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/UI-MATERIAL%203-000000?style=for-the-badge&logo=googlematerialdesign&logoColor=4285F4" />
</p>

<br/>

<!-- Quick Navigation Bar -->
<p align="center">
  <a href="#-overview"><b>Overview</b></a> &nbsp;•&nbsp;
  <a href="#-the-shopping-experience"><b>Experience</b></a> &nbsp;•&nbsp;
  <a href="#-features"><b>Features</b></a> &nbsp;•&nbsp;
  <a href="#-tech-stack"><b>Tech Stack</b></a> &nbsp;•&nbsp;
  <a href="#-architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#-getting-started"><b>Setup</b></a>
</p>

<!-- Google Gradient Divider -->
<img width="100%" height="3" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4285F4,25:EA4335,50:FBBC05,75:34A853,100:4285F4" />

</div>

<br/>

## 🌐 Overview

> **SMAQR** is an API-driven smart retail self-checkout ecosystem engineered to eliminate checkout friction, automate inventory processing, and provide cryptographic exit security.

<div align="center">
<table border="0" width="100%">
  <tr>
    <td width="33%" align="center" style="background-color: #f8f9fa; border-radius: 12px; padding: 16px;">
      💻<br/>
      <b>Modular REST API</b><br/>
      <sub>FastAPI + SQLAlchemy for low-latency transaction flows</sub>
    </td>
    <td width="33%" align="center" style="background-color: #f8f9fa; border-radius: 12px; padding: 16px;">
      🛡️<br/>
      <b>Cryptographic Exit</b><br/>
      <sub>SHA-256 token hashing & Fernet encryption for gate verification</sub>
    </td>
    <td width="33%" align="center" style="background-color: #f8f9fa; border-radius: 12px; padding: 16px;">
      🗄️<br/>
      <b>Relational Data</b><br/>
      <sub>PostgreSQL backend for strict transactional integrity</sub>
    </td>
  </tr>
</table>
</div>

---

## 🛍️ The Shopping Experience

Designed around Google's Material 3 motion guidelines for intuitive, step-by-step user journeys:

<br/>

<div align="center">

<table>
  <tr align="center">
    <td width="16%">
      📱<br/>
      <b>01. ACCESS</b><br/>
      <sub>Scan Store QR</sub>
    </td>
    <td width="16%">
      🛒<br/>
      <b>02. SHOP</b><br/>
      <sub>Scan Barcodes</sub>
    </td>
    <td width="16%">
      🛍️<br/>
      <b>03. CART</b><br/>
      <sub>Manage Items</sub>
    </td>
    <td width="16%">
      💳<br/>
      <b>04. PAY</b><br/>
      <sub>Simulated Pay</sub>
    </td>
    <td width="16%">
      🧾<br/>
      <b>05. RECEIPT</b><br/>
      <sub>Digital Receipt</sub>
    </td>
    <td width="16%">
      🔐<br/>
      <b>06. EXIT</b><br/>
      <sub>Verify Token</sub>
    </td>
  </tr>
</table>

</div>

---

## ✨ Features & Roadmap

### ⚡ Core Backend Modules

| Feature Module | Capabilities & Description | Status |
| :--- | :--- | :---: |
| **Store Sessions** | Generates isolate, cryptographically verifiable shopping sessions | ![Implemented](https://img.shields.io/badge/Ready-34A853?style=flat-square&logo=google-check) |
| **Product Discovery** | Instant barcode lookup with stock & price verification | ![Implemented](https://img.shields.io/badge/Ready-34A853?style=flat-square&logo=google-check) |
| **Cart Management** | Dynamic updates, batch quantity management, total calculation | ![Implemented](https://img.shields.io/badge/Ready-34A853?style=flat-square&logo=google-check) |
| **Checkout Engine** | Atomically converts carts to orders with stock deduction | ![Implemented](https://img.shields.io/badge/Ready-34A853?style=flat-square&logo=google-check) |
| **Security & Exit Gate**| SHA-256 token hashing, Fernet recovery & time-bound expiration | ![Implemented](https://img.shields.io/badge/Ready-34A853?style=flat-square&logo=google-check) |

### 🚀 Planned Client & UI Enhancements

<details open>
<summary><b>Frontend & User Interface (Next Phase)</b></summary>

- [ ] Modern React + Vite frontend adhering to **Material Design 3 Expressive** design tokens.
- [ ] Camera-based dynamic barcode & QR scanner integration (WebRTC + BarcodeDetector API).
- [ ] Real-time WebSocket integration for automated exit turnstile triggers.
- [ ] Staff administration dashboard & exit receipt validator portal.
</details>

---

## 🧰 Tech Stack

<div align="center">

### Backend & Database Platform
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,git,github,vscode,docker&theme=light" alt="Tech Stack Icons" />
  </a>
</p>

</div>

<br/>

<div align="center">

| Layer | Technologies | Purpose |
| :--- | :--- | :--- |
| **Language & Engine** | `Python 3.11+` | Core application logic, REST interfaces, and cryptography |
| **API Framework** | `FastAPI` + `Uvicorn` | High-performance asynchronous OpenAPI server |
| **ORM & Data** | `SQLAlchemy` + `Pydantic v2` | Data serialization, relational mapping & dynamic validation |
| **Database** | `PostgreSQL` | Acid-compliant transactional persistence |
| **Security** | `Cryptography (Fernet)` + `SHA-256` | Secure single-use exit verification tokens |
| **Frontend (Planned)**| `React` + `Vite` + `TailwindCSS` | Material 3 component UI and mobile client |

</div>

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    %% Custom Styling matching Google Color Palette
    classDef customerStyle fill:#E8F0FE,stroke:#4285F4,stroke-width:2px,color:#1A73E8;
    classDef frontendStyle fill:#FEF7E0,stroke:#FBBC05,stroke-width:2px,color:#B06000;
    classDef backendStyle fill:#E6F4EA,stroke:#34A853,stroke-width:2px,color:#137333;
    classDef securityStyle fill:#FCE8E6,stroke:#EA4335,stroke-width:2px,color:#C5221F;
    classDef dbStyle fill:#F1F3F4,stroke:#5F6368,stroke-width:2px,color:#202124;

    subgraph CLIENT["📱 Client Interaction (Planned)"]
        C([Customer App]) ::: customerStyle
        UI[React Mobile UI] ::: frontendStyle
        SCANNER[Barcode & QR Scanner] ::: frontendStyle
    end

    subgraph API_GATEWAY["⚡ FastAPI Service Core"]
        SESS[Session Manager] ::: backendStyle
        CART_SRV[Cart & Catalog Service] ::: backendStyle
        ORDER_SRV[Checkout & Inventory Engine] ::: backendStyle
    end

    subgraph SEC_VAULT["🔐 Security & Verification Module"]
        HASH_ENG[SHA-256 Hashing] ::: securityStyle
        FERNET_ENG[Fernet Encryption] ::: securityStyle
        VAL_GATE[Exit Gate Validator] ::: securityStyle
    end

    DB[(PostgreSQL Database)] ::: dbStyle

    C --> UI
    UI --> SCANNER
    SCANNER -->|REST API Requests| SESS
    SCANNER -->|Product Scanning| CART_SRV
    UI -->|Checkout Flow| ORDER_SRV

    SESS --> DB
    CART_SRV --> DB
    ORDER_SRV --> DB

    ORDER_SRV --> HASH_ENG
    ORDER_SRV --> FERNET_ENG
    VAL_GATE --> HASH_ENG
    SEC_VAULT --> DB
