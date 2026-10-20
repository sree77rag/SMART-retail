<!-- ============================================================ -->
<!-- SMAQR | CINEMATIC × ACADEMIC ENGINEERING PORTFOLIO           -->
<!-- ============================================================ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:020617,30:0B1220,65:064E3B,100:10B981&text=SMAQR&fontSize=82&fontColor=F8FAFC&fontAlignY=38&desc=SMART%20ACCESS%20%7C%20INTELLIGENT%20RETAIL&descSize=16&descAlignY=59&animation=fadeIn" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=3500&pause=1200&color=34D399&center=true&vCenter=true&width=800&lines=ENGINEERING+THE+NEXT+RETAIL+EXPERIENCE.;SCAN.+SHOP.+PAY.+WALK+OUT.;A+STUDY+IN+INTELLIGENT+SELF-CHECKOUT+SYSTEMS." alt="SMAQR Project Introduction" />

<br/><br/>

### AN INTELLIGENT RETAIL SELF-CHECKOUT PLATFORM

<sub>
A software engineering initiative exploring QR-enabled access,
barcode-based shopping, transaction workflows, and digital exit verification.
</sub>

<br/><br/>

<img src="https://img.shields.io/badge/PROJECT-SOFTWARE%20ENGINEERING-10B981?style=flat-square&labelColor=020617" />
<img src="https://img.shields.io/badge/BACKEND-FASTAPI-34D399?style=flat-square&labelColor=020617" />
<img src="https://img.shields.io/badge/DATABASE-POSTGRESQL-93C5FD?style=flat-square&labelColor=020617" />
<img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-FBBF24?style=flat-square&labelColor=020617" />

<br/><br/>

<sub>
SYSTEM DESIGN &nbsp; • &nbsp; API ENGINEERING &nbsp; • &nbsp;
DATABASE MANAGEMENT &nbsp; • &nbsp; SECURITY
</sub>

<br/><br/>

</div>

---

<div align="center">

## 01 &nbsp; — &nbsp; PROJECT ABSTRACT

</div>

**SMAQR** is a smart retail self-checkout platform designed to explore a more streamlined approach to supermarket shopping through connected software systems.

The platform brings together QR-based store access, barcode-oriented product identification, shopping cart management, checkout workflows, digital receipts, and exit-token verification.

Its backend is developed using **Python and FastAPI**, with **PostgreSQL** providing persistent relational data storage.

The current implementation focuses on API development, database integration, order processing, simulated payments, and token-based exit verification. A React-based frontend is planned as the next major development phase.

> *Research direction:* Investigating how connected APIs, structured data management, and token-based verification can support a more efficient retail checkout experience.

---

<div align="center">

## 02 &nbsp; — &nbsp; SYSTEM CONCEPT

<sub>FROM STORE ENTRY TO VERIFIED EXIT</sub>

</div>

```text
                         SMAQR
              INTELLIGENT RETAIL SYSTEM
                            │
                            ▼
                  ┌──────────────────┐
                  │   STORE ACCESS   │
                  │   QR SESSION     │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │ PRODUCT DISCOVERY│
                  │ BARCODE & CATALOG│
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │  CART MANAGEMENT │
                  │ ITEMS & QUANTITY │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │ CHECKOUT & ORDER │
                  │ PAYMENT SIMULATION│
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │ DIGITAL RECEIPT │
                  │ EXIT QR TOKEN   │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │ EXIT VERIFICATION│
                  │ TOKEN VALIDATION │
                  └──────────────────┘
