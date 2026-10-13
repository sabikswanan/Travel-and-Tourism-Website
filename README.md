<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:0E7490,100:F97316&height=260&section=header&text=Travel%20and%20Tourism%20Platform&fontSize=44&fontColor=FDBA74&fontAlignY=38&animation=fadeIn&desc=Full-stack%20MERN%20booking%20platform%20with%20AI%20itineraries%2C%20maps%20and%20payments&descSize=17&descAlignY=58&descAlign=50" alt="Travel and Tourism Platform" width="100%"/>

<a href="https://github.com/sabikswanan/Travel-and-Tourism-Website"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=F97316&center=true&vCenter=true&width=780&lines=%3E+Browse.+Plan.+Book.+Travel.;%3E+AI-generated+day-by-day+itineraries+with+Gemini;%3E+Interactive+maps+%C2%B7+live+currency+rates+%C2%B7+wallet;%3E+Role-based+dashboards+for+travellers%2C+agents+and+admins" alt="Browse, plan, book, travel. AI itineraries, maps, live currency rates and role-based dashboards."/></a>

<br/>

<a href="https://travel-and-tourism-website-chi.vercel.app"><img src="https://img.shields.io/badge/%E2%96%B6%20LIVE-DEMO-F97316?style=for-the-badge&labelColor=0B1220" alt="Live demo"/></a>

<img src="https://img.shields.io/badge/API%20ENDPOINTS-36-0E7490?style=for-the-badge&labelColor=0B1220" alt="36 API endpoints"/>
<img src="https://img.shields.io/badge/PAGES-24-0891B2?style=for-the-badge&labelColor=0B1220" alt="24 pages"/>
<img src="https://img.shields.io/badge/USER%20ROLES-3-14B8A6?style=for-the-badge&labelColor=0B1220" alt="3 user roles"/>
<img src="https://img.shields.io/badge/CURRENCIES-8-F59E0B?style=for-the-badge&labelColor=0B1220" alt="8 currencies"/>

<img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=0B1220" alt="React 19"/>
<img src="https://img.shields.io/badge/Vite-7-646CFF?style=for-the-badge&logo=vite&logoColor=white&labelColor=0B1220" alt="Vite 7"/>
<img src="https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=0B1220" alt="Tailwind CSS"/>
<img src="https://img.shields.io/badge/Node.js-Express%205-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=0B1220" alt="Node.js and Express 5"/>
<img src="https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=0B1220" alt="MongoDB and Mongoose"/>
<img src="https://img.shields.io/badge/Google-Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white&labelColor=0B1220" alt="Google Gemini"/>
<img src="https://img.shields.io/badge/Leaflet-Maps-199900?style=for-the-badge&logo=leaflet&logoColor=white&labelColor=0B1220" alt="Leaflet maps"/>
<img src="https://img.shields.io/badge/Vercel-Deployed-000000?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0B1220" alt="Deployed on Vercel"/>

<br/><br/>

**[Overview](#overview)** &nbsp;|&nbsp;
**[Features](#features)** &nbsp;|&nbsp;
**[Architecture](#architecture)** &nbsp;|&nbsp;
**[Booking Flow](#booking-flow)** &nbsp;|&nbsp;
**[API](#api)** &nbsp;|&nbsp;
**[Getting Started](#getting-started)** &nbsp;|&nbsp;
**[Author](#author)**

</div>

<br/>

<a name="overview"></a>

## 🌍 Overview

A full-stack **travel booking platform** built on the **MERN stack**. Travellers can discover tour
packages, see every stop on an interactive map, plan trips with an **AI itinerary generator**, pay,
and manage bookings, refunds and a wallet. Travel agents and admins get their own dashboards for
packages, inventory, bookings, sales reports, user roles and activity logs.

> [!NOTE]
> **Built as a team project for CSE471 — System Analysis and Design at BRAC University**, covering the
> full cycle from requirements to a deployed React frontend and a REST API backed by MongoDB.

<br/>

<a name="features"></a>

## ✨ Features

<table>
<tr>
<td valign="top" width="50%">

#### 🧳 For travellers
- Browse and filter packages by **type and destination**
- Package pages with **day-by-day itinerary** and an **interactive Leaflet map**
- **Wishlist**, **reviews and ratings**
- Prices in **8 currencies** using live exchange rates
- Secure checkout with a **simulated payment gateway**
- **My Bookings** with cancellation and automatic refunds
- **Wallet** with full transaction history
- **Notification center** with booking and payment updates

</td>
<td valign="top" width="50%">

#### 🛠️ For agents and admins
- Create, edit and deactivate **tour packages**
- **AI itinerary generator** (Google Gemini) with matching destination photos
- **Inventory** view of booked seats, capacity and occupancy rate
- Manage **all bookings** and their status
- **Sales reports** dashboard
- **User and role management**
- Full **activity log** of who did what and when

</td>
</tr>
</table>

<details>
<summary><b>Package types</b></summary>
<br/>

<img src="https://img.shields.io/badge/Adventure-0E7490?style=flat-square" alt="Adventure"/>
<img src="https://img.shields.io/badge/Luxury-0E7490?style=flat-square" alt="Luxury"/>
<img src="https://img.shields.io/badge/Relaxation-0E7490?style=flat-square" alt="Relaxation"/>
<img src="https://img.shields.io/badge/Cultural-0E7490?style=flat-square" alt="Cultural"/>
<img src="https://img.shields.io/badge/Honeymoon-0E7490?style=flat-square" alt="Honeymoon"/>
<img src="https://img.shields.io/badge/Friends-0E7490?style=flat-square" alt="Friends"/>
<img src="https://img.shields.io/badge/Family-0E7490?style=flat-square" alt="Family"/>

</details>

<details>
<summary><b>Supported currencies</b></summary>
<br/>

<img src="https://img.shields.io/badge/USD-F97316?style=flat-square" alt="USD"/>
<img src="https://img.shields.io/badge/BDT-F97316?style=flat-square" alt="BDT"/>
<img src="https://img.shields.io/badge/EUR-F97316?style=flat-square" alt="EUR"/>
<img src="https://img.shields.io/badge/GBP-F97316?style=flat-square" alt="GBP"/>
<img src="https://img.shields.io/badge/INR-F97316?style=flat-square" alt="INR"/>
<img src="https://img.shields.io/badge/CAD-F97316?style=flat-square" alt="CAD"/>
<img src="https://img.shields.io/badge/AUD-F97316?style=flat-square" alt="AUD"/>
<img src="https://img.shields.io/badge/JPY-F97316?style=flat-square" alt="JPY"/>

</details>

<br/>

<a name="architecture"></a>

## 🏗️ Architecture

```mermaid
flowchart LR
    U(["👤 Traveller · Agent · Admin"]) --> FE["<b>Frontend</b><br/>React 19 · Vite · Tailwind<br/>Leaflet maps · Context API"]
    FE -->|"REST + JWT"| BE["<b>Backend</b><br/>Node.js · Express 5<br/>10 route modules · role middleware"]
    BE --> DB[("<b>MongoDB</b><br/>7 Mongoose models")]
    BE --> AI["Google Gemini<br/>AI itineraries"]
    BE --> PX["Pexels<br/>destination photos"]
    BE --> FX["ExchangeRate-API<br/>live currency rates"]
    BE --> EM["Nodemailer<br/>email notifications"]

    classDef user fill:#FFF7ED,stroke:#F97316,stroke-width:2px,color:#0F172A
    classDef fe fill:#0E7490,stroke:#22D3EE,stroke-width:2px,color:#FFFFFF
    classDef be fill:#0F172A,stroke:#F97316,stroke-width:2px,color:#FFFFFF
    classDef db fill:#14B8A6,stroke:#0F766E,stroke-width:2px,color:#FFFFFF
    classDef ext fill:#FFF7ED,stroke:#F97316,stroke-width:1.5px,color:#0F172A
    class U user
    class FE fe
    class BE be
    class DB db
    class AI,PX,FX,EM ext
    linkStyle default stroke:#F97316,stroke-width:2px
```

<details>
<summary><b>Data model</b></summary>
<br/>

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#ECFEFF", "primaryBorderColor": "#0E7490", "primaryTextColor": "#0F172A", "lineColor": "#F97316", "secondaryColor": "#FFF7ED", "tertiaryColor": "#F8FAFC", "actorBkg": "#0E7490", "actorTextColor": "#FFFFFF", "actorBorder": "#0E7490", "signalColor": "#F97316", "signalTextColor": "#F97316", "textColor": "#F97316", "labelTextColor": "#F97316", "sequenceNumberColor": "#FFFFFF", "noteBkgColor": "#FFF7ED"}}}%%
erDiagram
    USER ||--o{ BOOKING : makes
    USER ||--o{ REVIEW : writes
    USER ||--o{ WALLET_TRANSACTION : has
    USER ||--o{ NOTIFICATION : receives
    USER ||--o{ ACTIVITY_LOG : generates
    USER }o--o{ PACKAGE : wishlists
    PACKAGE ||--o{ BOOKING : "booked in"
    PACKAGE ||--o{ REVIEW : receives
    BOOKING ||--o{ WALLET_TRANSACTION : "paid or refunded by"

    USER {
        string name
        string email
        string role "user, Agent, admin"
        number walletBalance
    }
    PACKAGE {
        string name
        string destination
        number price
        string type
        number duration
        date startDate
        number maxPeople
        number rating
    }
    BOOKING {
        string status "Pending, Confirmed, Cancelled, Completed"
        number totalPrice
        number refundAmount
    }
    WALLET_TRANSACTION {
        number amount
        string type "deposit, payment, refund"
    }
```

</details>

<br/>

<a name="booking-flow"></a>

## 🧭 Booking Flow

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#ECFEFF", "primaryBorderColor": "#0E7490", "primaryTextColor": "#0F172A", "lineColor": "#F97316", "secondaryColor": "#FFF7ED", "tertiaryColor": "#F8FAFC", "actorBkg": "#0E7490", "actorTextColor": "#FFFFFF", "actorBorder": "#0E7490", "signalColor": "#F97316", "signalTextColor": "#F97316", "textColor": "#F97316", "labelTextColor": "#F97316", "sequenceNumberColor": "#FFFFFF", "noteBkgColor": "#FFF7ED"}}}%%
sequenceDiagram
    autonumber
    participant T as Traveller
    participant FE as React app
    participant API as Express API
    participant DB as MongoDB
    participant Mail as Email service
    T->>FE: Pick a package and book
    FE->>API: POST /api/bookings
    API->>DB: Save booking (Pending)
    T->>FE: Pay at checkout
    FE->>API: POST /api/bookings/:id/pay
    API->>DB: Confirm booking + log wallet transaction
    API->>Mail: Send payment confirmation
    API->>DB: Create in-app notification
    API-->>FE: Booking confirmed
    FE-->>T: Trip confirmed 🎉
```

### Cancellation and refunds

Refunds are calculated automatically from how early the trip is cancelled and credited straight to
the traveller's **wallet**, with an email and an in-app notification.

| Cancelled before the trip starts | Refund |
|---|:---:|
| 30 days or more | **90%** |
| 7 – 29 days | **50%** |
| Less than 7 days | **0%** |

<br/>

<a name="api"></a>

## 🔌 API

**36 REST endpoints** across 10 route modules, protected by **JWT authentication** and
**role-based middleware**.

<details>
<summary><b>View all endpoints</b></summary>
<br/>

| Module | Endpoints |
|---|---|
| **Auth** `/api/auth` | `POST /register` · `POST /login` · `GET /profile` · `PUT /profile` |
| **Packages** `/api/packages` | `GET /` · `GET /:id` · `GET /types` · `GET /destinations` · `GET /inventory` · `GET /image-search` · `POST /generate-itinerary` · `POST /` · `PUT /:id` · `PATCH /deactivate/:id` · `DELETE /:id` |
| **Bookings** `/api/bookings` | `POST /` · `GET /` · `GET /my` · `PUT /:id` · `POST /:id/pay` · `PATCH /:id/cancel` · `GET /reports` |
| **Payments** `/api/payments` | `POST /initiate` · `POST /callback` |
| **Wallet** `/api/wallet` | `GET /` |
| **Wishlist** `/api/wishlist` | `GET /` · `POST /add` · `POST /remove` |
| **Reviews** `/api/reviews` | `GET /:packageId` · `POST /:packageId` |
| **Notifications** `/api/notifications` | `GET /` · `PATCH /:id/read` |
| **Currency** `/api/currency` | `GET /rates` |
| **Admin** `/api/admin` | `GET /users` · `PUT /users/:id/role` · `GET /logs` |

</details>

<br/>

<a name="getting-started"></a>

## 🚀 Getting Started

**1. Clone**

```bash
git clone https://github.com/sabikswanan/Travel-and-Tourism-Website.git
cd Travel-and-Tourism-Website
```

**2. Backend**

```bash
cd backend
npm install
npm run dev        # http://localhost:5000
```

**3. Frontend**

```bash
cd frontend
npm install
npm run dev        # http://localhost:5173
```

<details>
<summary><b>Environment variables</b></summary>
<br/>

Create `backend/.env`:

| Variable | Purpose |
|---|---|
| `MONGO_URI` | MongoDB connection string |
| `JWT_SECRET` | Secret for signing login tokens |
| `PORT` | API port (default `5000`) |
| `FRONTEND_URL` | Allowed frontend origin for CORS |
| `GEMINI_API_KEY` | AI itinerary generation (falls back to a template if missing) |
| `PEXELS_API_KEY` | Destination photos for itineraries |
| `EXCHANGE_RATE_API_KEY` | Live currency rates |
| `MASTER_ADMIN_EMAIL` | Email of the master admin account |

Create `frontend/.env`:

| Variable | Purpose |
|---|---|
| `VITE_API_URL` | Backend API URL (default `http://localhost:5000/api`) |

</details>

<br/>

## 🗺️ Roadmap

- [ ] Connect a live payment gateway in place of the simulator
- [ ] Switch development email to a production mail provider
- [ ] Trip reminder emails before the start date
- [ ] Automated tests for the API and key user flows

<br/>

<a name="author"></a>

## 👤 Author

<div align="center">

### Sabik Swanan

B.Sc. in Computer Science · BRAC University

<br/>

<a href="https://github.com/sabikswanan"><img src="https://img.shields.io/badge/GitHub-sabikswanan-0E7490?style=for-the-badge&logo=github&logoColor=white&labelColor=0B1220" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/sabikswanan"><img src="https://img.shields.io/badge/LinkedIn-sabikswanan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B1220" alt="LinkedIn"/></a>
<a href="https://mail.google.com/mail/?view=cm&fs=1&to=sabikswanan@gmail.com"><img src="https://img.shields.io/badge/Email-sabikswanan%40gmail.com-F97316?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B1220" alt="Email"/></a>

<br/><br/>

<sub>⭐ Star this repo if you found it useful</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,55:0E7490,100:0F172A&height=130&section=footer" alt="" width="100%"/>

</div>
