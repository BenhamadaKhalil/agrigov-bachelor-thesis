# AgriGov Market — Bachelor's Thesis

> **A Digital Platform for Direct Agricultural Trade and Logistics**  
> Bachelor's Degree in Computer Science · Specialization: Software Engineering  
> University of Constantine 2 — Department of Software Technologies and Information Systems  
> Academic Year 2025–2026

---

## 📄 About This Thesis

**AgriGov Market** addresses a critical gap in Algeria's agricultural sector: the absence of a unified platform combining market transparency, logistics management, and governmental supervision. The platform eliminates over-intermediation, provides real-time pricing references set by the Ministry of Agriculture, and coordinates the full trade cycle from product listing to delivery confirmation.

The thesis is structured into two chapters:
- **Chapter 1 — Requirements Analysis:** actor identification, use case modeling, system sequence diagrams, and UI mockups
- **Chapter 2 — System Design:** class diagram, activity diagram, relational database schema, deployment architecture, and full-stack implementation

---

## 🧩 Platform Actors

| Actor | Role |
|---|---|
| 🌾 **Farmer** | Register farms, list products, manage orders, post transport missions |
| 🛒 **Buyer** | Browse marketplace, place orders, track deliveries, rate products |
| 🚛 **Transporter** | View and accept delivery missions, update delivery status |
| 🏛️ **Ministry of Agriculture** | Validate users, set official prices, manage categories, monitor market activity |
| 🔍 **Quality Inspector** | Verify product compliance with government standards |
| 📦 **Delivery Manager** | Supervise and coordinate logistics operations |

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|---|---|---|
| Backend | Python · Django · Django REST Framework | MVT pattern, built-in ORM, REST API support |
| Frontend | TypeScript · Next.js · Tailwind CSS | SSR, file-based routing, type safety |
| Database | PostgreSQL (hosted on **Neon**) | Relational integrity for multi-entity model |
| File Storage | Cloudinary | CDN-based media delivery for product images |
| Mobile | React Native | Cross-platform iOS/Android from shared codebase |
| Deployment | Docker · Gunicorn/WSGI · Render/AWS | Containerized, production-ready deployment |
| Version Control | Git · GitHub | Branch-based team collaboration |
| IDE | Visual Studio Code | Full support for Python, TypeScript, Django |

---

## 📁 Repository Structure

```
server/                  # Django backend
├── Agrigov/             # Project configuration
├── cart/                # Cart & CartItem logic
├── categories/          # Product categories
├── farms/               # Farm management
├── missions/            # Delivery missions
├── official_prices/     # Ministry price regulation
├── orders/              # Order processing
├── products/            # Product listings
├── users/               # Authentication & validation
├── vehicules/           # Transporter vehicles
└── manage.py

web-App/                 # Next.js frontend
├── app/
├── components/
│   ├── Auth/
│   ├── Farmer/ · Buyer/ · Transporter/ · Ministry/
│   └── ...
└── types/

mobile-app/              # React Native mobile app
├── screens/
│   ├── farmer/ · buyer/ · transporter/
├── components/
└── navigation/
```

---

## 🔗 Repositories

| Repository | Link |
|---|---|
| 🌐 Web (Frontend + Backend) | [AGRIGOV-MARKET](https://github.com/DabbacheDjawad/AGRIGOV-MARKET) |
| 📱 Mobile Application | [Agrigov-mobile](https://github.com/BenhamadaKhalil/Agrigov-mobile) |

---

## 🤖 AI Tools Used

This project transparently integrated AI assistants as development productivity tools. All outputs were reviewed and validated by the team before use.

| Tool | Usage |
|---|---|
| **ChatGPT** (OpenAI) | Code generation, Django/DRF boilerplate, query optimization, API documentation |
| **Claude** (Anthropic) | Architecture review, technical writing, refactoring suggestions |

> All design decisions and intellectual contributions remain the sole responsibility of the authors.

---

## 👥 Authors

| Name | Role |
|---|---|
| **BENHAMADA Mohamed Salah Eddine** | Full-stack development |
| **BOULEMAIZ Siradj Eddine** | Full-stack development |
| **DABBACHE Djaouad Djaouhar Eddin** | Full-stack development |

**Supervisor:** Dr. Zakaria BENZADRI  
**Institution:** University of Constantine 2 — Department of Software Technologies and Information Systems  
**Academic Year:** 2025–2026

---

## 📜 License

This project was submitted as an academic thesis. All rights reserved © 2026.
