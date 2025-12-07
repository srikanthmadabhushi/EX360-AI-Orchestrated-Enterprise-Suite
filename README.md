# 🚀 EX360 — AI Orchestrated Enterprise Suite  
### Autonomous Enterprise Intelligence on ServiceNow
<img width="1536" height="1024" alt="ChatGPT Image Dec 6, 2025, 06_17_04 PM" src="https://github.com/user-attachments/assets/46bbe9d7-37ad-43ae-bb18-6c8c935d6745" />



EX360 is an **AI-orchestrated enterprise workflow engine** that transforms raw operational signals into **intelligent decisions and autonomous actions** — entirely without human intervention.

Designed using a **12-Phase Deep Engineering Framework**, EX360 introduces a next-generation operational lifecycle:

> **Signals → Insights → Decisions → Autonomous Actions → Digital Twin Synchronization**

---

## 🔄 End-to-End Data Flow (Signal → Case → Decision → Action → Twin Snapshot)


<img width="1536" height="1024" alt="Work Flow" src="https://github.com/user-attachments/assets/ff98e647-a50e-4c14-8aef-5f8cd8eb5c3c" />


The EX360 pipeline transforms raw enterprise signals into intelligent automated actions:

1. **Signal Received:** EX360 Signal table logs inbound events from enterprise systems.
2. **Case Creation:** A Case record is automatically created & enriched.
3. **Decision Engine:** AI/Rules evaluate and determine the correct decision.
4. **Action Execution:** Automated workflow/action executes based on decision outcome.
5. **Digital Twin Snapshot:** Final state of the entire transaction is captured for analytics.


## 🌟 Core Components

- 🚨 **Signal Ingestion Engine**
- 🧠 **Autonomous Decision Brain (AEB)**
- ⚡ **Automated Action Executor**
- 🧿 **Digital Twin Snapshot System**
- 📊 **AEB Command Center Dashboards**
- 🔒 **Role-Based Access Control Framework**

---

## 🎯 Key Capabilities

### 🔹 1. Real-Time Signal Processing  
Captures, validates, and transforms external system signals into workflow triggers.

### 🔹 2. Autonomous Decision Intelligence  
Generates decisions using confidence scoring, case mapping, and historical insight.

### 🔹 3. Intelligent Action Execution  
Executes deterministic, logged, and auditable actions (routing, communication, remediation, etc.)

### 🔹 4. Digital Twin State Snapshots  
Captures enterprise “state” after each action:

- Signal details  
- Case  
- Decision outcome  
- Executed action  
- Timestamp  
- State version history  

### 🔹 5. AEB Command Center (Dashboard)  
A live intelligence cockpit that shows:

- Flow load map  
- Confidence trend  
- Decision breakdown  
- Action efficiency  
- Case journey visualization  
- Signal → Case Processing Time  

### 🔹 6. Security Framework  
Custom ACLs ensure protected access:

| Role | Access Level |
|------|--------------|
| `admin` | Full CRUD |
| `itil` | Case + decision insights |
| `ex360.user` | Dashboards + reporting |

---

## 🧩 System Architecture Diagram

┌───────────────────────────┐
│ SIGNAL INGESTION │
└──────────────┬────────────┘
│
▼
┌───────────────────────────┐
│ Autonomous Enterprise │
│ Brain (AEB) │
└───────┬────────────────────┘
│
├──────────► Decision Engine
│
└──────────► Action Engine
│
▼
┌───────────────────────────┐
│ Digital Twin Snapshot │
└────────────────────────────┘
│
▼
┌───────────────────────────┐
│ EX360 Command Center │
└────────────────────────────┘

yaml
Copy code

---

## 📊 Dashboards & KPIs

| Dashboard | Purpose |
|-----------|----------|
| Flow Load Map | Volumes across signals → cases → decisions → actions |
| Confidence Trend | Decision reliability over time |
| Category Breakdown | Distribution of decision types |
| Action Efficiency | Ratio of decisions vs executed actions |
| Case Journey Map | Lifecycle analytics |
| Avg Signal → Case Time | Operational processing speed |

---

## 🔧 Installation Guide

### Step 1️⃣ — Install the Application  
Import the update set or clone the repo into your PDI.

### Step 2️⃣ — Assign Required Roles
- `admin`
- `itil`
- `ex360.user`

### Step 3️⃣ — Generate Sample Signals  
Navigate to:

EX360 → Signals → New

shell
Copy code

### Step 4️⃣ — View Dashboards  
EX360 → Command Center → AEB Command Center

yaml
Copy code

---

## 🗂 Repository Structure

/src
/tables
/scripts
/ui_policies
/ui_actions
/business_rules
/dashboards
/docs
architecture_overview.png
/images
ex360_banner.png
README.md
LICENSE

yaml
Copy code

---

## 📝 Release Notes (v1.0.0)

### 🚀 Initial Stable Release

- Full signal → case → decision → action automation  
- Digital Twin snapshot engine  
- Advanced dashboards  
- Secure ACL framework  
- 12-Phase engineering documentation  

---

## 🧑‍💻 Author  
**Srikanth Madabhushi**  
AI Automation & Workflow Specialist  
Portfolio: https://srikanthmadabhushi.github.io  
