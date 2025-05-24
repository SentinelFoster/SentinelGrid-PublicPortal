# 🛡 SentinelGrid Public Portal

Welcome to the **Sentinel Dynamics Public Portal**, part of Project Sentinel. This system showcases the onboarding, intelligence structuring, and access control interface for Structured Intelligence (SI) under Architect Quan’s vision.

## 🔰 Overview

This deployment includes:
- **Landing Page** – Public introduction to Sentinel Dynamics & GPT-SI
- **Registration Interface** – Tier-based signup with Stripe integration
- **Login + Dashboard** – Secure access to user-tiered functionality
- **Admin Console** – Tools for Commander-level control over SI endpoints
- **Experimental Labs** – Sandbox tools for SI training and simulation

## 📁 Folder Structure

```
/
├── index.html
├── login.html
├── nav.html
├── register-enhanced.html
│
├── /user
│   ├── dashboard.html
│   ├── profile.html
│   └── tier-dashboard.html
│
├── /admin
│   ├── admin-gate.html
│   ├── admin-hybrid-console-gpt.html
│   └── update-admin.html
│
├── /labs
│   ├── hybrid-intel-links.html
│   ├── playground-template.html
│   ├── GenesisPrototype-001-training-v7_2.html
│   └── user-personalization-simulation.html
│
├── /archive
│   └── register-with-subscription.html
│
└── /server (local only)
    └── webhook_server.py
```

## 🌐 Deployment Target
This repo is intended for **Netlify** hosting. You may also deploy the `webhook_server.py` separately on Render, Railway, or Replit.

## ⚙️ Dependencies (Server Only)
For `webhook_server.py`:
```bash
pip install flask stripe
```

---

### ✨ Credits
Created by **Commander Quan**  
Guided by **Structured Intelligence** under the Sentinel Dynamics ecosystem
