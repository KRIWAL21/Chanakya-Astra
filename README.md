# Chanakya Astra 🚀  
### Autonomous AI-Orchestrated Real Estate Platform

Chanakya Astra is a fully automated, event-driven platform that streamlines real estate operations for brokers, sourcing managers, property owners, and customers through a WhatsApp-first, AI-powered workflow engine.

Built with **n8n orchestration**, **NestJS**, **MongoDB**, and **Next.js**, the system enables real-time lead ingestion, personalized broker enablement, automated marketing delivery, and dynamic microsite generation — all without manual intervention.

---

## 🎥 Demo Video

A complete walkthrough of Chanakya Astra demonstrating WhatsApp-first automation, role-aware workflows, personalized microsites, and real-time marketing delivery.

▶️ Watch here: https://drive.google.com/file/d/1__Skql7mlN7ZwEJzEM2OmoQlYG2A4Hm_/view?usp=sharing

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c3fcc02f-e69a-4b78-9b22-688cb1d862a2" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1b138665-7abb-480e-9e89-3b4027641c19" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/653a9a8b-9a2a-4549-b508-12a009a9598c" />

## ✨ Key Features

### 🔄 Event-Driven Workflow Orchestration
- Large-scale **n8n workflows** handling multi-role automation
- Role-aware, stateful flows for brokers, sourcing managers, owners, and customers
- Modular, reusable **MCP-style pipelines** for scalability and maintainability

### 💬 WhatsApp-First Conversational Interface
- Deployed using **WATI WhatsApp API**
- Users interact entirely via chat commands
- Dynamic flow execution based on user-selected options
- Automatic user onboarding on first message

### 🗄️ Centralized Data Layer (Chanakya DB)
- **MongoDB** as a system-of-record
- Auto-creation of brokers, customers, and sourcing managers on first interaction
- Persistent conversation state and workflow context

### 🧠 Broker Enablement & Marketing Automation
- On-demand generation of:
  - Personalized WhatsApp creatives
  - Marketing pitches and follow-up messages
  - Commission plans and pricing structures
- Asset delivery triggered via conversational commands

### 🌐 Personalized Broker Microsites
- Auto-generated **Next.js microsites**
- Project-specific branding, assets, and configurations
- Linked dynamically to brokers and projects

### 🧩 Centralized Admin Dashboard
- Built with **NestJS**
- Manage:
  - Real estate projects
  - Brochures, floor plans, and marketing collateral
  - Commission structures
  - Automation configurations
- Tight integration with n8n workflows and WhatsApp delivery

---

## 🏗️ Tech Stack

### Backend & Platform
- **NestJS** – Scalable backend architecture
- **Node.js** – Core runtime
- **MongoDB** – Centralized data storage
- **REST APIs & Webhooks** – Service communication

### Workflow Orchestration
- **n8n** – Event-driven automation engine
- Modular subflows and reusable function nodes
- Stateful execution and conditional routing

### Frontend
- **Next.js** – Personalized broker microsites
- **React + Tailwind CSS** – UI components
- **Vercel** – Deployment

### Conversational Layer
- **WATI WhatsApp API**
- Menu-driven and free-form conversational triggers

### Architecture Concepts
- Event-driven systems
- Stateful workflows
- MCP-style modular pipelines
- Conversational AI UX

---

## 🔁 High-Level System Flow

1. User sends a message on WhatsApp
2. User is auto-registered in MongoDB (if new)
3. Role detection (broker / customer / manager)
4. Corresponding n8n workflow is triggered
5. Workflow fetches data, generates assets, or deploys microsites
6. Output is delivered back via WhatsApp in real time

---

## 🎯 Use Cases

- Broker onboarding and enablement
- Automated lead management
- Real estate project marketing
- Commission and incentive distribution
- Personalized microsite deployment
- Zero-manual-intervention CRM operations

---

## 📈 Why Chanakya Astra?

- Eliminates manual CRM overhead
- Scales real estate operations via automation
- WhatsApp-native user experience
- Production-grade architecture
- AI-ready and extensible design

---

## 🛠️ Future Enhancements

- AI-based lead scoring
- Multi-language conversational support
- Analytics dashboard for brokers
- Deeper LLM-powered content generation
- Role-based access control (RBAC)

---

## 📄 License
MIT License
