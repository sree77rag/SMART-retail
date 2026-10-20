<!-- ========================================================= -->
<!--                       SMAQR                               -->
<!--             CINEMATIC RETAIL TECHNOLOGY                   -->
<!-- ========================================================= -->

<div align="center">

<!-- CINEMATIC HERO -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:000000,25:020617,55:064E3B,80:047857,100:10B981&text=SMAQR&fontSize=100&fontColor=FFFFFF&fontAlignY=40&desc=SMART%20ACCESS.%20INTELLIGENT%20RETAIL.&descAlignY=61&descSize=17&animation=fadeIn" alt="SMAQR Cinematic Header"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2800&pause=900&color=34D399&center=true&vCenter=true&width=800&lines=THE+FUTURE+OF+SELF-CHECKOUT.;SCAN.+SHOP.+PAY.+WALK+OUT.;ENGINEERED+FOR+A+SMARTER+RETAIL+EXPERIENCE.;PYTHON+%7C+FASTAPI+%7C+POSTGRESQL" alt="SMAQR Cinematic Typing Animation"/>

<br/><br/>

### A NEW PERSPECTIVE ON RETAIL.

<sub>
An API-driven self-checkout platform built to simplify shopping,
streamline checkout workflows, and enable secure exit verification.
</sub>

<br/><br/>

<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-34D399?style=for-the-badge&labelColor=020617"/>
<img src="https://img.shields.io/badge/ENGINE-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/API-FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/DATA-POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>

<br/><br/>

<a href="#-the-vision">THE VISION</a>
&nbsp; ━ &nbsp;
<a href="#-capabilities">CAPABILITIES</a>
&nbsp; ━ &nbsp;
<a href="#-technology">TECHNOLOGY</a>
&nbsp; ━ &nbsp;
<a href="#-architecture">ARCHITECTURE</a>
&nbsp; ━ &nbsp;
<a href="#-development-status">PROGRESS</a>
&nbsp; ━ &nbsp;
<a href="#-getting-started">SETUP</a>

<br/><br/>

<img width="85%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,30:064E3B,70:10B981,100:020617" />

</div>

---

<!-- ========================================================= -->
<!-- THE VISION                                                -->
<!-- ========================================================= -->

## ◈ The Vision

**SMAQR — Smart Access. Intelligent Retail.**

SMAQR is a smart retail self-checkout platform designed to transform the traditional supermarket shopping journey into a more connected digital experience.

The system combines QR-based store access, barcode-based product identification, shopping cart management, checkout workflows, digital receipts, and QR-based exit verification.

Its backend is built around a modular API architecture, connecting application logic with a PostgreSQL database.

The project is being developed incrementally, with an emphasis on backend engineering, API design, database management, and security-conscious transaction workflows.

> *Less friction. Smarter shopping. A more connected retail experience.*

<div align="center">

### THE SHOPPING JOURNEY

<br/>

| 01 — ACCESS | 02 — DISCOVER | 03 — CHECKOUT |
|:---:|:---:|:---:|
| QR-Based Store Entry | Barcode-Based Shopping | Order Creation |
| Enter a shopping session | Identify products | Prepare the order |

**↓**

| 04 — PAYMENT | 05 — RECEIPT | 06 — EXIT |
|:---:|:---:|:---:|
| Simulated Payment | Digital Receipt | QR Verification |
| Process a test transaction | Review order details | Validate the exit token |

<br/>

<img width="85%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,30:064E3B,70:10B981,100:020617"/>

</div>

---

<!-- ========================================================= -->
<!-- CAPABILITIES                                              -->
<!-- ========================================================= -->

## ✦ Capabilities

### Backend Systems

The current implementation includes the following core workflows.

| Capability | Description | Status |
|:---|:---|:---:|
| Session Management | Create unique shopping sessions | Implemented |
| Product Identification | Retrieve product information using barcodes | Implemented |
| Shopping Cart | Manage cart items and quantities | Implemented |
| Checkout Workflow | Generate orders from shopping sessions | Implemented |
| Payment Simulation | Simulate payment processing | Implemented |
| Inventory Updates | Deduct available stock during successful simulated payment | Implemented |
| Digital Receipts | Retrieve order details and itemized totals | Implemented |
| Exit QR Generation | Generate time-limited exit tokens | Implemented |
| Token Hashing | Hash exit tokens for lookup and verification | Implemented |
| Token Encryption | Encrypt tokens for subsequent retrieval | Implemented |
| Exit Verification | Reject expired or previously used tokens | Implemented |

### The Next Evolution

- [ ] React-powered customer interface
- [ ] Responsive mobile, tablet, and desktop layouts
- [ ] Frontend–backend API integration
- [ ] Camera-based barcode scanning
- [ ] Interactive shopping cart and checkout screens
- [ ] Digital receipt and exit QR interface
- [ ] Staff-facing exit-verification interface
- [ ] Expanded automated testing
- [ ] Stronger transaction and concurrency guarantees
- [ ] Real payment-provider integration
- [ ] Production deployment and monitoring

> **Current scope:** Payments are simulated. The customer-facing frontend, camera-based barcode scanning, real payment processing, and production deployment are not yet complete.

---

<!-- ========================================================= -->
<!-- TECHNOLOGY                                                -->
<!-- ========================================================= -->

## ⬡ Technology

<div align="center">

### THE ENGINEERING STACK

<br/>

<img src="https://skillicons.dev/icons?i=python,postgresql,fastapi&theme=dark" alt="Current backend technology stack"/>

<br/><br/>

<img width="80%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,50:10B981,100:020617"/>

<br/>

### FRONTEND — NEXT PHASE

<img src="https://skillicons.dev/icons?i=html,css,js,react,vite&theme=dark" alt="Planned frontend technology stack"/>

<br/>

<sub>Frontend technologies are planned and are not yet integrated into the current application.</sub>

</div>

### 01 — Programming Languages

| Language | Responsibility | Status |
|:---|:---|:---:|
| Python | Backend logic and API implementation | In use |
| SQL | Relational data queries and management | In use |
| JavaScript | Frontend interactions and API requests | Planned |
| HTML5 | Frontend structure | Planned |
| CSS3 | Visual styling and responsive layouts | Planned |

### 02 — Frameworks and Libraries

| Technology | Responsibility | Status |
|:---|:---|:---:|
| FastAPI | REST API framework | In use |
| SQLAlchemy | Database ORM | In use |
| Pydantic | Data validation and request schemas | In use |
| React | Component-based frontend | Planned |
| Vite | Frontend development and production builds | Planned |

### 03 — Database

| Technology | Responsibility |
|:---|:---|
| PostgreSQL | Persistent relational data storage |
| SQLAlchemy | Python database interaction |
| Relational Data Modeling | Stores, products, sessions, carts, orders, and exit tokens |

### 04 — Security Engineering

| Technology | Responsibility |
|:---|:---|
| SHA-256 | Hashing exit tokens |
| Fernet | Encrypting recoverable token values |
| Environment Variables | Supplying sensitive configuration |
| Expiration Validation | Rejecting expired tokens |
| Single-Use Validation | Preventing sequential reuse of consumed tokens |

### 05 — Developer Tooling

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,vscode,windows&theme=dark" alt="Developer tooling"/>

</div>

| Tool | Purpose |
|:---|:---|
| Visual Studio Code | Development environment |
| Git | Version control |
| GitHub | Source code hosting |
| PowerShell | Local development commands |
| Uvicorn | ASGI server for FastAPI |
| Swagger UI | Interactive API documentation and testing |

<sub>Package and technology listings should be verified against the current repository configuration.</sub>

---

<!-- ========================================================= -->
<!-- ARCHITECTURE                                              -->
<!-- ========================================================= -->

## ◈ Architecture

SMAQR follows a layered application architecture, separating the customer interface, backend application logic, and persistent data storage.

```mermaid
flowchart TB

    CUSTOMER([Customer])

    subgraph FRONTEND["FRONTEND — PLANNED"]
        UI[React Interface]
        SCAN[Product Scanning]
        CART[Shopping Cart]
        CHECKOUT[Checkout and Receipt]
    end

    subgraph BACKEND["BACKEND — CORE WORKFLOWS IMPLEMENTED"]
        API[FastAPI REST API]
        SESSION[Session Management]
        PRODUCTS[Product and Cart Services]
        ORDERS[Order and Checkout Services]
        SECURITY[Exit Token Services]
    end

    DATABASE[(PostgreSQL)]

    CUSTOMER --> UI

    UI --> SCAN
    UI --> CART
    UI --> CHECKOUT

    SCAN --> API
    CART --> API
    CHECKOUT --> API

    API --> SESSION
    API --> PRODUCTS
    API --> ORDERS
    API --> SECURITY

    SESSION --> DATABASE
    PRODUCTS --> DATABASE
    ORDERS --> DATABASE
    SECURITY --> DATABASE

    classDef planned fill:#0f172a,stroke:#64748b,color:#f8fafc
    classDef active fill:#064e3b,stroke:#10b981,color:#ffffff

    class UI,SCAN,CART,CHECKOUT planned
    class API,SESSION,PRODUCTS,ORDERS,SECURITY,DATABASE active
