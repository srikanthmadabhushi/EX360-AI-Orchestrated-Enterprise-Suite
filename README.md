# 🚀 EX360 — AI Orchestrated Enterprise Suite  

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT" />
  <img src="https://img.shields.io/badge/Build-EX360_Stable-green.svg" alt="Build Status" />
  <img src="https://img.shields.io/badge/Platform-ServiceNow_Yokhoma-red.svg" alt="Platform" />
  <img src="https://img.shields.io/badge/AI-Orchestrated_Enterprise-purple.svg" alt="AI" />
</p>

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

---

## 🔹 1. Real-Time Signal Intelligence
EX360 ingests events from any enterprise system and converts them into structured workflow triggers.

**Technical Capabilities**
- Handles JSON, text, structured/unstructured signals  
- Performs source classification & normalization  
- Automatically sets lifecycle state (New → Processed)  

**Business Impact**
- Zero manual triage  
- Faster response times  
- Full visibility into operational noise  

---

## 🔹 2. Autonomous Case Generation Engine
Signals are instantly converted into structured EX360 Cases.

**Technical Capabilities**
- Auto-populates category, subcategory, source system  
- Links back to originating signal  
- Enriched metadata for decisioning  

**Business Impact**
- Cleaner routing  
- Consistent case structure  
- End-to-end traceability  

---

## 🔹 3. Intelligent Decision Engine (AEB Core)
Every case triggers automated decision logic with AI confidence scoring.

**Technical Capabilities**
- Automated decision summary generation  
- Configurable decision types  
- Confidence scoring model  
- Pluggable rule sets & ML extensions  

**Business Impact**
- Reduced analyst workload  
- Improved accuracy  
- Faster issue resolution  

---

## 🔹 4. Autonomous Action Executor
The system automatically performs remediation or routing actions.

**Technical Capabilities**
- Executes contextual actions  
- Logs payload, summary, and execution metadata  
- Supports multi-action chaining  
- Fully auditable logs  

**Business Impact**
- Removes repetitive human tasks  
- Ensures consistent response  
- Increases workflow reliability  

---

## 🔹 5. Digital Twin Snapshot Engine
Every transaction creates a snapshot of system state.

**Technical Capabilities**
- JSON-based snapshot representation  
- Links to Signal, Case, Decision, and Action  
- Timestamped historical versioning  
- Supports anomaly detection  

**Business Impact**
- Operational replayability  
- Simplified RCA (Root Cause Analysis)  
- Enhanced governance & compliance  

---

## 🔹 6. AEB Command Center (Analytics Dashboard)
A real-time cockpit for operational intelligence.

**Technical KPIs**
- Signal → Case conversion rate  
- Decision confidence trend  
- Action success rate  
- Cognitive Load Score  
- Processing time & SLA metrics  

**Business Impact**
- Faster insight delivery  
- Data-driven leadership decisions  
- Visibility across the entire automation chain  

---

## 🔹 7. Enterprise-Grade Security Framework
Custom ACLs safeguard every EX360 table.

**Technical Highlights**
- Create / Read / Write / Delete protections  
- Viewer-only vs Admin roles  
- Scoped app isolation  
- Supports enterprise RBAC models  

**Business Impact**
- Prevents unauthorized actions  
- Ensures safe automation at scale  
- Aligned with enterprise IT controls  

---

## 🔹 8. Modular & Extensible Architecture
Designed so teams can build plugins or extend any phase:

- Custom Signal types  
- New Decision models  
- Additional Action modules  
- External AI integrations (OpenAI, Vertex AI, etc.)  

---

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

---

## 🏷️ Release Notes

### **Version 1.0.0 — Initial Public Release**
**Release Date:** December 2025  
**Status:** Stable Release  
**Scope:** End-to-End Autonomous Workflow Suite

The EX360 AI Orchestrated Enterprise Suite delivers a fully autonomous enterprise workflow engine built on the ServiceNow platform. This release introduces the complete lifecycle system capable of intelligent processing across Signals, Cases, Decisions, Actions, and Digital Twin Snapshots.

---

### 🌟 **Key Highlights**

#### **1. Autonomous Workflow Pipeline**
Fully automated pipeline:
- Signal Ingestion  
- Case Creation  
- Decision Modeling  
- Action Execution  
- Digital Twin Snapshot Recording  

Each stage is driven without manual intervention, enabling rapid and consistent enterprise automation.

---

#### **2. AEB (Autonomous Enterprise Brain) Dashboard**
A multi-layer analytics experience featuring:
- Pipeline metrics (Signal → Case → Decision → Action)
- Cognitive Load Score
- Case Journey Insights
- Confidence Trend Line
- Workflow Efficiency KPIs

---

#### **3. Modular Architecture**
A highly structured 12-phase engineering model including:
- Core tables & data schemas  
- Script Include logic  
- Business Rules  
- ACL security framework  
- Dashboard visualizations  
- Notifications & extensibility hooks  

---

#### **4. Digital Twin Engine**
Every automated transaction produces a state snapshot used for:
- Auditing  
- RCA (Root Cause Analysis)  
- Predictive analytics  
- Workflow lineage  

Now enterprises can replay any workflow’s lifecycle.

---

#### **5. Enterprise Security Model**
Includes:
- Scoped app isolation  
- Role-based access controls  
- Protected system actions  

---

### 🧩 Compatibility & Requirements
- **Platform:** ServiceNow Zurich or later  
- **Role Requirements:** `admin` or `ex360.user`  
- **Browser:** Chrome recommended  

---

### 🔮 Upcoming Enhancements
(Planned for Version 1.1.0+)
- AI-based Decision Recommendation Engine  
- Adaptive routing and priority scoring  
- Multi-signal correlation models  
- Predictive digital twin insights  



## 🧑‍💻 Author  
**Srikanth Madabhushi**  
AI Automation & Workflow Specialist  
Portfolio: https://srikanthmadabhushi.github.io  
