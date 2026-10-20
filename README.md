<!-- ========================================================= -->
<!--                         SMAQR                             -->
<!--              SMART ACCESS. INTELLIGENT RETAIL.             -->
<!-- ========================================================= -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:4285F4,30:34A853,60:FBBC05,100:EA4335&fontColor=FFFFFF&text=SMAQR&fontSize=64&fontAlignY=42&animation=fadeIn" alt="SMAQR Header"/>

<br/>

# Smart Access. Intelligent Retail.

### A NEW PERSPECTIVE ON RETAIL.

An API-driven self-checkout platform built to simplify shopping,
streamline checkout workflows, and enable exit verification.

<br/>

<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-4285F4?style=for-the-badge&labelColor=FFFFFF" />
<img src="https://img.shields.io/badge/ENGINE-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/API-FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/DATA-POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />

<br/><br/>

<a href="#-overview">Overview</a>
&nbsp; • &nbsp;
<a href="#-features">Features</a>
&nbsp; • &nbsp;
<a href="#-technology-stack">Technology</a>
&nbsp; • &nbsp;
<a href="#-architecture">Architecture</a>
&nbsp; • &nbsp;
<a href="#-development-status">Progress</a>
&nbsp; • &nbsp;
<a href="#-getting-started">Setup</a>

<br/><br/>

<img width="85%" src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:4285F4,33:34A853,66:FBBC05,100:EA4335" />

</div>

---

## 🌐 Overview

**SMAQR — Smart Access. Intelligent Retail.**

SMAQR is a smart retail self-checkout platform designed to make supermarket shopping more convenient through QR-based store access, barcode-based product identification, shopping cart management, checkout workflows, digital receipts, and QR-based exit verification.

The backend connects application logic with a PostgreSQL database through a modular REST API architecture.

The project is being developed incrementally, focusing on backend engineering, database management, API integration, and security-conscious transaction workflows.

> **Our vision:** Less friction. Smarter shopping. Better retail experiences.

---

## 🛍️ The Shopping Experience

<div align="center">

| <img src="https://img.icons8.com/color/96/qr-code.png" width="48" alt="QR code"/> | <img src="https://img.icons8.com/color/96/barcode.png" width="48" alt="Barcode"/> | <img src="https://img.icons8.com/color/96/shopping-cart--v1.png" width="48" alt="Shopping cart"/> |
|:---:|:---:|:---:|
| **01. ACCESS** | **02. SHOP** | **03. CHECKOUT** |
| Scan the store QR | Identify products | Create an order |

| <img src="https://img.icons8.com/color/96/bank-card-back-side.png" width="48" alt="Payment"/> | <img src="https://img.icons8.com/color/96/receipt.png" width="48" alt="Receipt"/> | <img src="https://img.icons8.com/color/96/verified-account.png" width="48" alt="Verification"/> |
|:---:|:---:|:---:|
| **04. PAYMENT** | **05. RECEIPT** | **06. EXIT** |
| Simulate payment | Review order details | Verify the exit token |

</div>

---

## ✨ Features

### Backend Capabilities

| Feature | Description | Status |
|---|---|---|
| Store Sessions | Create unique shopping sessions | Implemented |
| Product Identification | Retrieve products using barcode information | Implemented |
| Shopping Cart | Manage cart items and quantities | Implemented |
| Checkout | Create orders from shopping sessions | Implemented |
| Payment Simulation | Simulate the payment workflow | Implemented |
| Inventory Updates | Deduct stock during successful simulated payment | Implemented |
| Digital Receipts | Retrieve order details and itemized totals | Implemented |
| Exit QR Generation | Generate time-limited exit tokens | Implemented |
| Token Hashing | Hash tokens for lookup and verification | Implemented |
| Token Encryption | Encrypt tokens for subsequent retrieval | Implemented |
| Exit Verification | Reject expired or previously used tokens | Implemented |

### Upcoming Features

- [ ] React-powered customer interface
- [ ] Responsive mobile, tablet, and desktop layouts
- [ ] Frontend–backend API integration
- [ ] Camera-based barcode scanning
- [ ] Interactive cart and checkout screens
- [ ] Digital receipt and exit QR interface
- [ ] Staff-facing exit-verification interface
- [ ] Expanded automated testing
- [ ] Improved transaction and concurrency guarantees
- [ ] Real payment-provider integration
- [ ] Production deployment and monitoring

> **Current limitation:** Payments are simulated. The customer-facing frontend, camera-based scanning, real payment processing, and production deployment are not yet complete.

---

## 🧰 Technology Stack

### 01. Programming Languages

<div align="center">

<img src="https://skillicons.dev/icons?i=python&theme=light" alt="Python"/>

</div>

| Language | Purpose | Status |
|---|---|---|
| Python | Backend application logic and API development | In use |
| SQL | Relational database queries and management | In use |
| JavaScript | Frontend interactions and API requests | Planned |
| HTML5 | Frontend structure | Planned |
| CSS3 | Styling and responsive layouts | Planned |

### 02. Frameworks and Libraries

<div align="center">

<img src="https://skillicons.dev/icons?i=fastapi,react,vite&theme=light" alt="Frameworks"/>

</div>

| Technology | Purpose | Status |
|---|---|---|
| FastAPI | REST API framework | In use |
| SQLAlchemy | Database ORM | In use |
| Pydantic | Request validation and data schemas | In use |
| React | Component-based frontend | Planned |
| Vite | Frontend development and production builds | Planned |

### 03. Database

<div align="center">

<img src="https://skillicons.dev/icons?i=postgresql&theme=light" alt="PostgreSQL"/>

</div>

| Technology | Purpose |
|---|---|
| PostgreSQL | Persistent relational data storage |
| SQLAlchemy | Database interaction through Python |
| Relational Data Modeling | Stores, products, sessions, carts, orders, and exit tokens |

### 04. Security and Cryptography

| Technology | Purpose |
|---|---|
| SHA-256 | Hashing exit tokens |
| Fernet | Encrypting recoverable token values |
| Environment Variables | Supplying sensitive configuration |
| Expiration Validation | Rejecting expired tokens |
| Single-Use Validation | Rejecting previously consumed tokens |

### 05. Development Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,vscode,windows&theme=light" alt="Development Tools"/>

</div>

| Tool | Purpose |
|---|---|
| Visual Studio Code | Development environment |
| Git | Version control |
| GitHub | Source code hosting |
| PowerShell | Local development commands |
| Uvicorn | ASGI server for FastAPI |
| Swagger UI | Interactive API documentation and testing |

> Frontend technologies are planned and are not yet integrated into the current application. Verify package names against the project's dependency configuration.

---

## 🏗️ Architecture

SMAQR follows a layered architecture connecting the customer interface, backend API, and PostgreSQL database.

```mermaid
flowchart TB

    CUSTOMER([Customer])

    subgraph FRONTEND["Frontend — Planned"]
        UI[React Interface]
        SCAN[Product Scanning]
        CART[Shopping Cart]
        CHECKOUT[Checkout and Receipt]
    end

    subgraph BACKEND["Backend — Core Workflows Implemented"]
        API[FastAPI REST API]
        SESSION[Session Management]
        PRODUCTS[Product and Cart Services]
        ORDERS[Order and Checkout Services]
        SECURITY[Exit Token Services]
    end

    DB[(PostgreSQL Database)]

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

    SESSION --> DB
    PRODUCTS --> DB
    ORDERS --> DB
    SECURITY --> DB

    classDef planned fill:#E8F0FE,stroke:#4285F4,color:#174EA6
    classDef active fill:#E6F4EA,stroke:#34A853,color:#137333

    class UI,SCAN,CART,CHECKOUT planned
    class API,SESSION,PRODUCTS,ORDERS,SECURITY,DB active
