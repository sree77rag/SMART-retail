<!-- ========================================================= -->
<!-- SMAQR | CINEMATIC TECHNOLOGY BRAND                         -->
<!-- Smart Access. Intelligent Retail.                         -->
<!-- ========================================================= -->

<div align="center">

<!-- CINEMATIC HERO -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:020617,25:020617,55:064E3B,80:047857,100:10B981&text=SMAQR&fontSize=100&fontColor=FFFFFF&fontAlignY=40&desc=SMART%20ACCESS.%20INTELLIGENT%20RETAIL.&descAlignY=61&descSize=17&animation=fadeIn" alt="SMAQR — Smart Access. Intelligent Retail."/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=2800&pause=900&color=34D399&center=true&vCenter=true&width=750&lines=THE+FUTURE+OF+SELF-CHECKOUT.;SCAN.+SHOP.+PAY.+WALK+OUT.;ENGINEERED+FOR+A+SMARTER+RETAIL+EXPERIENCE." alt="SMAQR animated tagline"/>

<br/><br/>

<h3>A NEW PERSPECTIVE ON RETAIL.</h3>

<p>
An API-driven self-checkout platform designed to simplify shopping,<br/>
streamline checkout workflows, and enable QR-based exit verification.
</p>

<br/>

<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-34D399?style=for-the-badge&labelColor=020617" alt="Project in development"/>
<img src="https://img.shields.io/badge/ENGINE-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/API-FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/DATA-POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>

<br/><br/>

<img width="88%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,30:064E3B,70:10B981,100:020617" alt="Emerald divider"/>

<br/>

<a href="#-the-vision">◈ THE VISION</a>
&nbsp;&nbsp; ━ &nbsp;&nbsp;
<a href="#-capabilities">✦ CAPABILITIES</a>
&nbsp;&nbsp; ━ &nbsp;&nbsp;
<a href="#-technology">⬡ TECHNOLOGY</a>
&nbsp;&nbsp; ━ &nbsp;&nbsp;
<a href="#-architecture">⌘ ARCHITECTURE</a>
&nbsp;&nbsp; ━ &nbsp;&nbsp;
<a href="#-development-status">◉ PROGRESS</a>
&nbsp;&nbsp; ━ &nbsp;&nbsp;
<a href="#-getting-started">↗ SETUP</a>

<br/><br/>

</div>

---

## ◈ THE VISION

**SMAQR — Smart Access. Intelligent Retail.**

SMAQR is a smart retail self-checkout platform designed to transform the traditional supermarket shopping journey into a connected digital experience.

The platform combines QR-based store access, barcode-based product identification, shopping cart management, checkout workflows, digital receipts, and QR-based exit verification.

Its backend connects application logic with a PostgreSQL database through a modular REST API architecture.

> *Less friction. Smarter shopping. A more connected retail experience.*

<br/>

<div align="center">

### THE SHOPPING JOURNEY

<br/>

<table>
<tr>
<td align="center" width="33%">
<h3>01</h3>
<strong>◉ ACCESS</strong>
<br/><br/>
Enter through a store QR code.
</td>
<td align="center" width="33%">
<h3>02</h3>
<strong>▦ DISCOVER</strong>
<br/><br/>
Identify products and manage the cart.
</td>
<td align="center" width="33%">
<h3>03</h3>
<strong>↗ CHECKOUT</strong>
<br/><br/>
Create an order and simulate payment.
</td>
</tr>
<tr>
<td align="center" width="33%">
<h3>06</h3>
<strong>⌑ EXIT</strong>
<br/><br/>
Verify the exit token.
</td>
<td align="center" width="33%">
<h3>05</h3>
<strong>▤ RECEIPT</strong>
<br/><br/>
Retrieve digital order details.
</td>
<td align="center" width="33%">
<h3>04</h3>
<strong>◇ PAYMENT</strong>
<br/><br/>
Validate the simulated transaction.
</td>
</tr>
</table>

<br/>

<img width="88%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,30:064E3B,70:10B981,100:020617" alt="Emerald divider"/>

</div>

---

## ✦ CAPABILITIES

### Backend Systems

| Capability | Description | Status |
|:---|:---|:---:|
| ◉ Session Management | Create unique shopping sessions | Implemented |
| ▦ Product Identification | Retrieve products using barcode information | Implemented |
| 🛒 Shopping Cart | Manage cart items and quantities | Implemented |
| ↗ Checkout Workflow | Create orders from shopping sessions | Implemented |
| ◇ Payment Simulation | Simulate payment processing | Implemented |
| ▤ Inventory Updates | Deduct stock during successful simulated payment | Implemented |
| ▤ Digital Receipts | Retrieve order details and itemized totals | Implemented |
| ⌑ Exit QR Generation | Generate time-limited exit tokens | Implemented |
| ◈ Token Hashing | Hash tokens for lookup and verification | Implemented |
| ◈ Token Encryption | Encrypt recoverable token values | Implemented |
| ✓ Exit Verification | Reject expired or previously used tokens | Implemented |

### NEXT EVOLUTION

- [ ] React customer interface
- [ ] Responsive mobile, tablet, and desktop layouts
- [ ] Frontend–backend API integration
- [ ] Camera-based barcode scanning
- [ ] Interactive cart and checkout
- [ ] Digital receipt and exit QR interface
- [ ] Staff-facing exit verification
- [ ] Expanded automated testing
- [ ] Improved concurrency and transaction safeguards
- [ ] Real payment-provider integration
- [ ] Production deployment and monitoring

> **Development note:** Payment is currently simulated. The customer-facing frontend, camera-based scanning, real payment processing, and production deployment are planned, not completed.

---

## ⬡ TECHNOLOGY

<div align="center">

### THE ENGINEERING STACK

<br/>

<img src="https://skillicons.dev/icons?i=python,fastapi,postgresql&theme=dark" alt="Python, FastAPI, PostgreSQL"/>

<br/><br/>

<img width="78%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:020617,50:10B981,100:020617" alt="Emerald divider"/>

<br/>

### FRONTEND — NEXT PHASE

<img src="https://skillicons.dev/icons?i=html,css,js,react,vite&theme=dark" alt="Planned frontend technologies"/>

<br/>

<sub>Frontend technologies are planned for the next development phase.</sub>

</div>

### 01 — LANGUAGES

| Language | Responsibility | Status |
|:---|:---|:---:|
| Python | Backend logic and API implementation | In use |
| SQL | Relational data queries | In use |
| JavaScript | Frontend interactions and API requests | Planned |
| HTML5 | Frontend structure | Planned |
| CSS3 | Styling and responsive layouts | Planned |

### 02 — FRAMEWORKS & LIBRARIES

| Technology | Purpose | Status |
|:---|:---|:---:|
| FastAPI | REST API framework | In use |
| SQLAlchemy | Python database ORM | In use |
| Pydantic | Request validation and data schemas | In use |
| React | Component-based frontend | Planned |
| Vite | Frontend development and production builds | Planned |

### 03 — DATABASE & DATA MANAGEMENT

| Technology | Purpose |
|:---|:---|
| PostgreSQL | Persistent relational data storage |
| SQLAlchemy | Database interaction through Python |
| Relational Data Modeling | Stores, products, sessions, carts, orders, and exit tokens |

### 04 — SECURITY ENGINEERING

| Technology | Purpose |
|:---|:---|
| SHA-256 | Hashing exit tokens |
| Fernet | Encrypting tokens that must later be recovered |
| Environment Variables | Supplying sensitive configuration |
| Expiration Validation | Rejecting expired tokens |
| Single-Use Validation | Rejecting previously consumed tokens |

### 05 — DEVELOPMENT TOOLS

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,vscode,windows&theme=dark" alt="Git, GitHub, VS Code, Windows"/>

</div>

| Tool | Purpose |
|:---|:---|
| Visual Studio Code | Development environment |
| Git | Version control |
| GitHub | Source code hosting |
| PowerShell | Local development commands |
| Uvicorn | ASGI server for FastAPI |
| Swagger UI | Interactive API documentation and testing |

<sub>Verify technology and dependency listings against the actual project configuration.</sub>

---

## ⌘ ARCHITECTURE

SMAQR separates the customer interface, backend application logic, and persistent data storage.

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
