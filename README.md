#  De-Cruft AI: The Autonomous Engineering Manager

> **"Code is messy. Managers speak money. We translate between the two."**

![Status](https://img.shields.io/badge/Status-Hackathon_Prototype-purple?style=for-the-badge) 
![Tech Stack](https://img.shields.io/badge/Stack-FastAPI_React_AI-00f3ff?style=for-the-badge)

## 🚀 The Problem
Developers spend **42% of their time** fixing bad code (Technical Debt). But explaining "Cyclomatic Complexity" to a non-technical manager is impossible. They don't care about clean code; they care about **cost**, **speed**, and **risk**.

## 💡 The Solution
**De-Cruft AI** is an intelligent dashboard that acts as your **Autonomous Engineering Manager**. You paste a GitHub repository link **ONCE**, and our system assigns the code to a squad of **5 Specialized AI Agents** to analyze, price, and fix the mess.

### 🤖 The Agent Squad
We don't just "scan" code. We dispatch it to these specialists:

| Agent | Role | Mission |
| :--- | :--- | :--- |
| **🧹 The Cleaner** | Refactoring Specialist | Identifies spaghetti code and estimates the "Cost to Fix" in USD. |
| **🛡️ The Guard** | Security Auditor | Scans for vulnerabilities, leaked secrets, and injection risks. |
| **🎨 The Artist** | Visualizer | Maps complex code dependencies into clear logic flowcharts. |
| **📝 The Writer** | Documentation Lead | Detects undocumented functions and drafts standard docstrings. |
| **⚖️ The Judge** | QA Engineer | Writes unit test cases to prove the code works reliably. |

---

## 🏗️ Architecture

### **Frontend (The Dashboard)**
* **Framework:** React (Vite)
* **Styling:** Custom CSS3 (Neon Cyberpunk Theme)
* **Visualization:** Recharts (Interactive Data Graphing)
* **Icons:** Lucide React

### **Backend (The Engine)**
* **Server:** FastAPI (Python)
* **Core Logic:** GitPython (Cloning & AST parsing)
* **AI Orchestration:** OnDemand Agents API
* **Validation:** Pydantic Models

---

## 💸 The "Debt Pricing" Formula
We translate code metrics into a financial forecast using the **SQALE Method**:

$$\text{Total Debt Cost} = (\text{Remediation Hours}) \times (\text{Avg Developer Rate } \$85/hr)$$

Where **Remediation Hours** are calculated from:
1.  **Complexity Penalty:** Time required to simplify nested loops and logic.
2.  **Duplication Penalty:** Time required to merge copy-pasted code blocks.
3.  **Documentation Penalty:** Time required to read and document legacy code.

---

## ⚡ Installation & Setup

### Prerequisites
* Node.js (v18+)
* Python (v3.9+)

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/De-Cruft.git](https://github.com/your-username/De-Cruft.git)
cd De-Cruft

cd backend

# Install the required Python libraries
pip install fastapi uvicorn requests gitpython pydantic

# Start the Backend Server
uvicorn main:app --reload

cd frontend

# Install the required Node modules
npm install

# Start the React Dashboard
npm run dev
