<!-- ========================================================= -->
<!--                 SMART RETAIL | README                     -->
<!-- ========================================================= -->

<div align="center">

<!-- PREMIUM ANIMATED HEADER -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:020617,35:064E3B,70:059669,100:10B981&text=SMART%20RETAIL&fontSize=55&fontColor=FFFFFF&fontAlignY=38&desc=Intelligent%20Self-Checkout%20%7C%20Retail%20Technology&descAlignY=58&descSize=16&animation=fadeIn" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=700&lines=Scan.+Shop.+Pay.+Walk+Out.;Engineering+a+Smarter+Retail+Experience.;FastAPI+%7C+PostgreSQL+%7C+React+%7C+Python" alt="Typing SVG" />

<br/><br/>

<p>
  <strong>A smarter approach to supermarket shopping.</strong>
  <br/>
  <sub>Scan products · Manage your cart · Simulate checkout · Verify your exit</sub>
</p>

<br/>

<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-10B981?style=for-the-badge&labelColor=020617" />
<img src="https://img.shields.io/badge/BACKEND-FASTAPI-059669?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/DATABASE-POSTGRESQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />

<br/><br/>

<a href="#-overview">Overview</a>
&nbsp; • &nbsp;
<a href="#-features">Features</a>
&nbsp; • &nbsp;
<a href="#-architecture">Architecture</a>
&nbsp; • &nbsp;
<a href="#-technology-stack">Tech Stack</a>
&nbsp; • &nbsp;
<a href="#-getting-started">Getting Started</a>

<br/><br/>

</div>

---

## ◈ Overview

**Smart Retail** is a QR-enabled supermarket self-checkout platform designed to simplify the shopping journey.

The goal is to let customers enter a store through a store QR code, scan product barcodes, manage their shopping cart, complete a checkout flow, receive a digital receipt, and verify their exit using a QR-based token.

The project is being developed incrementally, with an emphasis on backend engineering, API integration, database design, and security-conscious transaction handling.

> **Project philosophy:** Less friction. Smarter shopping. Better retail experiences.

### The Vision

```text
       ENTER                  SHOP                  CHECKOUT
         │                      │                       │
         ▼                      ▼                       ▼
    ┌──────────┐          ┌──────────┐            ┌──────────┐
    │ Store QR │ ───────► │  Product │ ─────────► │  Digital │
    │  Access  │          │   Cart   │            │  Receipt │
    └──────────┘          └──────────┘            └────┬─────┘
                                                       │
                                                       ▼
                                                ┌────────────┐
                                                │ Exit Token │
                                                │ Verification│
                                                └────────────┘
