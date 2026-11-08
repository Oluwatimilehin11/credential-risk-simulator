# 🛡️ Enterprise Credential Risk Simulator

A probabilistic threat-modeling tool analyzing corporate exposure across 20 mega-breaches (31M to 2B accounts) cataloged by Have I Been Pwned (HIBP) from 2024 to 2026.

## 📌 Overview

This project quantifies how breach size, breach type (single-service hack vs. infostealer log vs. credential stuffing compilation), and password reuse behaviors impact an organization's security posture.

### Key Insights
- **The Scale Problem:** In teams with 250+ employees, team exposure reaches **90%–100%** across large aggregated compilations.
- **The Infostealer Threat:** Unlike standard leaks, infostealer dumps expose active browser session tokens, bypassing simple password prompts.
- **The MFA Defense:** Enforcing Multi-Factor Authentication blocks **~99%** of automated credential-stuffing intrusions.

---

## 🚀 Quickstart (JupyterLab)

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Oluwatimilehin11/credential-risk-simulator.git](https://github.com/Oluwatimilehin11/credential-risk-simulator.git)
   cd credential-risk-simulator
