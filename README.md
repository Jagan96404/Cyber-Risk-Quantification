<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%" height="auto" style="max-width: 100%; margin: 0 0 30px 0; background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);">
  <defs>
    <linearGradient id="headerGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d9ff" stop-opacity="0.9"/>
      <stop offset="50%" stop-color="#0099ff" stop-opacity="0.95"/>
      <stop offset="100%" stop-color="#00d9ff" stop-opacity="0.9"/>
    </linearGradient>
    
    <linearGradient id="accentGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00d9ff"/>
      <stop offset="100%" stop-color="#0099ff"/>
    </linearGradient>

    <filter id="textGlow">
      <feGaussianBlur stdDeviation="1.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="iconGlow">
      <feGaussianBlur stdDeviation="2"/>
      <feComposite in="SourceGraphic" in2="SourceGraphic" operator="lighter"/>
    </filter>

    <style>
      @keyframes slideBg {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
      }
      @keyframes glowPulse {
        0%, 100% { filter: drop-shadow(0 0 2px #00d9ff); }
        50% { filter: drop-shadow(0 0 8px #0099ff); }
      }
      @keyframes scan {
        0% { y: -20; }
        100% { y: 280; }
      }
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-8px); }
      }
      @keyframes spinIcon {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }

      .title-text { animation: glowPulse 3s ease-in-out infinite; }
      .scan-line { animation: scan 3s ease-in-out infinite; }
      .float-up { animation: float 4s ease-in-out infinite; }
      .icon-spin { transform-origin: 120px 160px; animation: spinIcon 8s linear infinite; }
    </style>
  </defs>

  <!-- Main Container -->
  <g>
    <!-- Title Section -->
    <g>
      <text x="600" y="90" font-family="'Segoe UI', -apple-system, BlinkMacSystemFont, Roboto, sans-serif" font-size="54" font-weight="700" text-anchor="middle" fill="#f8fafc" filter="url(#textGlow)" class="title-text">
        Cyber Risk
      </text>
      <text x="600" y="150" font-family="'Segoe UI', -apple-system, BlinkMacSystemFont, Roboto, sans-serif" font-size="54" font-weight="700" text-anchor="middle" fill="url(#headerGradient)" filter="url(#textGlow)" class="title-text">
        Quantification
      </text>
    </g>

    <!-- Subtitle -->
    <text x="600" y="210" font-family="'Segoe UI', -apple-system, BlinkMacSystemFont, Roboto, sans-serif" font-size="14" font-weight="400" text-anchor="middle" fill="#94a3b8" letter-spacing="2">
      FAIR METHODOLOGY • MONTE CARLO SIMULATIONS • CONTINUOUS RISK SCORING
    </text>

    <!-- Left Icon: Shield & Analytics -->
    <g class="icon-spin" opacity="0.8">
      <circle cx="120" cy="160" r="45" fill="none" stroke="url(#accentGradient)" stroke-width="2" filter="url(#iconGlow)"/>
      <path d="M 120 130 L 105 145 L 110 160 L 105 175 L 120 190 L 135 175 L 130 160 L 135 145 Z" fill="url(#accentGradient)" opacity="0.7"/>
      <circle cx="120" cy="160" r="8" fill="#00d9ff" opacity="0.5"/>
    </g>

    <!-- Right Icon: Radar Waves -->
    <g opacity="0.8">
      <circle cx="1080" cy="160" r="35" fill="none" stroke="url(#accentGradient)" stroke-width="2" filter="url(#iconGlow)"/>
      <circle cx="1080" cy="160" r="22" fill="none" stroke="url(#accentGradient)" stroke-width="1.5" opacity="0.6"/>
      <circle cx="1080" cy="160" r="10" fill="#00d9ff" opacity="0.8"/>
      <line x1="1080" y1="135" x2="1080" y2="185" stroke="url(#accentGradient)" stroke-width="1.5" opacity="0.6"/>
      <line x1="1055" y1="160" x2="1105" y2="160" stroke="url(#accentGradient)" stroke-width="1.5" opacity="0.6"/>
    </g>

    <!-- Animated Scan Line -->
    <g class="scan-line">
      <line x1="200" y1="160" x2="1000" y2="160" stroke="#00d9ff" stroke-width="1" opacity="0.3"/>
      <line x1="200" y1="160" x2="1000" y2="160" stroke="#00d9ff" stroke-width="2" opacity="0.8" filter="url(#iconGlow)"/>
    </g>

    <!-- Bottom Stats -->
    <g class="float-up" opacity="0.7">
      <rect x="300" y="250" width="130" height="50" rx="8" fill="#0c1527" stroke="#00d9ff" stroke-width="1.5" opacity="0.6"/>
      <text x="365" y="273" font-family="'Segoe UI', sans-serif" font-size="11" font-weight="700" text-anchor="middle" fill="#00d9ff">QUANTIFIED RISK</text>
      <text x="365" y="292" font-family="'Segoe UI', sans-serif" font-size="10" text-anchor="middle" fill="#94a3b8">Financial Exposure</text>
    </g>

    <g class="float-up" opacity="0.7" style="animation-delay: 0.3s">
      <rect x="535" y="250" width="130" height="50" rx="8" fill="#0c1527" stroke="#00d9ff" stroke-width="1.5" opacity="0.6"/>
      <text x="600" y="273" font-family="'Segoe UI', sans-serif" font-size="11" font-weight="700" text-anchor="middle" fill="#00d9ff">LOSS MODELING</text>
      <text x="600" y="292" font-family="'Segoe UI', sans-serif" font-size="10" text-anchor="middle" fill="#94a3b8">Probabilistic ALE</text>
    </g>

    <g class="float-up" opacity="0.7" style="animation-delay: 0.6s">
      <rect x="770" y="250" width="130" height="50" rx="8" fill="#0c1527" stroke="#00d9ff" stroke-width="1.5" opacity="0.6"/>
      <text x="835" y="273" font-family="'Segoe UI', sans-serif" font-size="11" font-weight="700" text-anchor="middle" fill="#00d9ff">CONTINUOUS CTEM</text>
      <text x="835" y="292" font-family="'Segoe UI', sans-serif" font-size="10" text-anchor="middle" fill="#94a3b8">Real-time Scoring</text>
    </g>
  </g>
</svg>

---

## 💡 What is Cyber Risk Quantification?

**Cyber Risk Quantification (CRQ)** is the discipline of measuring information security risks in objective, financial terms rather than ordinal "High/Medium/Low" heat maps. By leveraging standardized quantitative frameworks such as **Open FAIR™ (Factor Analysis of Information Risk)**, **Monte Carlo simulations**, **Loss Exceedance Curves (LEC)**, and continuous threat intelligence, CRQ enables CISOs, risk officers, and enterprise boards to: By leveraging standardized quantitative frameworks such as **Open FAIR™ (Factor Analysis of Information Risk)**, **Monte Carlo simulations**, **Loss Exceedance Curves (LEC)**, and continuous threat intelligence, CRQ enables CISOs, risk officers, and enterprise boards to:

- 💵 Calculate **Annualized Loss Expectancy (ALE)** and **Cyber Value at Risk (VaR)** in dollars.
- 🎯 Prioritize security investments based on measurable risk reduction and Return on Security Investment (ROSI).
- 📈 Translate technical telemetry (vulnerabilities, misconfigurations, EPSS scores) into board-ready financial exposure.
- 🔍 Validate cyber insurance policy limits and evaluate third-party vendor supply-chain exposure.

This repository is a comprehensive, curated index of top commercial **SaaS platforms**, **open-source engines**, and **risk-as-code frameworks** designed for modern cyber risk quantification.

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial CRQ Platforms](#-saas--commercial-crq-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🧩 Architectural Blueprints for Custom CRQ](#-architectural-blueprints-for-custom-crq)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Star History](#-star-history)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS & Commercial CRQ Platforms

*Below is a curated comparison of leading commercial Cyber Risk Quantification, Continuous Threat Exposure Management (CTEM), and Third-Party Risk Management (TPRM) platforms, sorted in descending order by company valuation/size.*

### [Qualys TruRisk](https://www.qualys.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🏦 Public (NASDAQ: QLYS) |
| **Valuation** | ~$5.45B Market Cap |
| **Revenue** | ~$685M+ (TTM) |
| **Description** | Vulnerability Management, Detection, and Response (VMDR) engine computing asset-level and organization-level TruRisk scores by combining vulnerability severity, exploitability (EPSS), asset criticality, and threat intelligence. |
| **Pricing** | Starts at **$199 – $250/IP/year** for VMDR TruRisk; Web Application Scanning (WAS) starts at **$1,995/yr** (for 25 apps); starter enterprise deployment bundles begin at **~$2,500 – $3,000/yr**. |
| **Free Tier / Trial** | 🆓 **Free forever Community Edition** (limited to 16 internal IPs, 3 external IPs, 1 web application, and 1 virtual scanner appliance) + **30-day free trial** of full VMDR TruRisk platform. |

### [SecurityScorecard](https://securityscorecard.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🦄 Private (Series E) |
| **Valuation** | ~$1.0B |
| **Revenue** | ~$135M+ ARR |
| **Funding** | ~$293M |
| **Description** | Cybersecurity ratings and continuous monitoring platform providing outside-in risk scores (A–F), automated issue detection, and financial cyber risk quantification modules. |
| **Pricing** | Starts at **~$12,000 – $20,000/yr** for entry monitoring tier (monitoring 50–150 third-party domains); enterprise vendor management portfolios scale to **$45,000+/yr**. |
| **Free Tier / Trial** | 🆓 **Free forever tier** (includes 1 self-monitored domain scorecard, basic questionnaire exchange, and core dashboard access) + **14-day free trial** of the Business Plan with full automated alerting. |

### [CyCognito](https://www.cycognito.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🚀 Private (Series C) |
| **Valuation** | ~$800M |
| **Revenue** | ~$41M+ ARR |
| **Funding** | ~$153M |
| **Description** | External Attack Surface Management (EASM) and continuous exposure testing platform that maps shadow IT, identifies attack paths, and quantifies business risk exposure. |
| **Pricing** | Starts at **~$25,000/yr** (entry-level ASM package for up to 250 external assets/domains); scales with asset volume (tiers up to 5,000–100,000+ assets) and testing frequency. |
| **Free Tier / Trial** | ⏱️ **14-day guided proof of concept (POC)** including full external asset discovery scan and exposure report (no perpetual free tier). |

### [Safe Security](https://safe.security/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🚀 Private (Series C) |
| **Valuation** | ~$400M–$500M |
| **Funding** | ~$170M |
| **Description** | Autonomous cyber risk management & quantification platform (SAFE One) combining FAIR-derived methodology, Monte Carlo simulations, and real-time telemetry across internal assets, cloud, and third parties. |
| **Pricing** | Starts at **~$30,000 – $50,000/yr** for core CRQ packages; scales into six-figure enterprise contracts based on asset count, data connectors, and modules (CTEM, TPRM, AI-SPM). |
| **Free Tier / Trial** | 🆓 **Free access** to standalone interactive tools (*Interactive Cost Calculator* & *Cyberinsurance Assessment*); **14-to-30 day guided enterprise Proof of Value (POV)** upon sales qualification. |

### [Brinqa](https://www.brinqa.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 💼 Private (Growth Equity) |
| **Valuation** | ~$350M–$450M |
| **Funding** | ~$110M (Insight Partners) |
| **Description** | Cyber Risk Management and Vulnerability Risk Prioritization platform aggregating telemetry from 100+ security tools to model cyber relationships and compute unified risk scores. |
| **Pricing** | Starts at **~$50,000 – $100,000/yr** (enterprise pricing based on volume of ingested assets/vulnerabilities and connector counts). |
| **Free Tier / Trial** | ⏱️ **14-to-30-day scoped proof-of-concept pilot** in a dedicated sandbox environment with sample integration connectors (no perpetual free tier). |

### [RedSeal](https://www.redseal.net/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🏛️ Private (STG Acquired) |
| **Valuation** | ~$150M–$200M |
| **Revenue** | ~$51M+ ARR |
| **Funding** | ~$140M+ |
| **Description** | Cyber risk analytics and network modeling platform that constructs digital twins of hybrid networks to identify attack paths, test segmentation, and calculate digital resilience scores. |
| **Pricing** | Starts at **~$10,000 – $20,000/yr** (licensed on a per-network-node/device model at ~$100–$250 per device/firewall with minimum annual commitment). |
| **Free Tier / Trial** | ⏱️ **30-day guided evaluation / proof-of-concept license** for network topology modeling and vulnerability path verification. |

### [Black Kite](https://blackkite.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🛡️ Private (Series B) |
| **Valuation** | ~$150M–$200M |
| **Revenue** | ~$25M+ ARR |
| **Funding** | ~$36M |
| **Description** | Third-party cyber risk intelligence and CRQ platform providing financial impact calculation (FAIR-based), Ransomware Susceptibility Index (RSI™), and compliance correlation. |
| **Pricing** | Starts at **~$15,000 – $29,160/yr** (median entry tier monitoring 25–50 vendor domains); scaling up to **$90,000+/yr** for large enterprise supply chains. |
| **Free Tier / Trial** | 🆓 **1 complimentary external Cyber Risk Assessment report** for your company or 1 vendor domain + **14-day scoped evaluation trial** upon request. |

### [Balbix](https://www.balbix.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 📈 Acquired (Safe Security) |
| **Valuation** | ~$120M–$150M |
| **Funding** | ~$60M+ (prior to acquisition) |
| **Description** | Security posture and cyber exposure quantification platform using AI to continuously discover assets, predict breach risk, and prioritize remediation by financial impact. |
| **Pricing** | Starts at **~$20,000 – $35,000/yr** for entry-level deployments; scales based on total asset inventory / IP count and integration volume. |
| **Free Tier / Trial** | ⏱️ **30-day proof-of-value (POV) trial** including initial external and internal asset discovery scan with risk scoring (no perpetual free tier). |

### [Axio](https://axio.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | ⚡ Private (Series B) |
| **Valuation** | ~$80M–$120M |
| **Revenue** | ~$14M+ ARR |
| **Funding** | ~$30M (ISTARI) |
| **Description** | Cyber risk management and quantification platform (Axio360) emphasizing scenario-based financial stress testing, C2M2/NIST CSF maturity assessments, and board-ready reporting. |
| **Pricing** | Starts at **~$12,000 – $24,000/yr** for core benchmark & assessment tier; scaling to **$50,000+/yr** for full CRQ stress-testing suite. |
| **Free Tier / Trial** | 🆓 **Free forever tier** for single-framework assessments (NIST CSF Quick Launch, C2M2 Quick Launch, and Ransomware Preparedness tools for 1 organization) + **14-day full platform trial**. |

### [RiskLens](https://www.risklens.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 📘 Acquired (Safe Security) |
| **Valuation** | ~$50M–$80M |
| **Funding** | ~$20M+ (prior to acquisition) |
| **Description** | Pure-play quantitative cyber risk management software aligned with the Open FAIR™ standard; provides probabilistic loss modeling (ALE, VaR) and board-level risk analytics. |
| **Pricing** | Starts at **~$15,000 – $25,000/yr** for RiskLens Pro / Starter tier; enterprise tiers range from **$50,000 to $100,000+/yr** depending on FAIR analysis volume. |
| **Free Tier / Trial** | 🆓 **Free forever access** to the FAIR-U web application (educational tool for 1 FAIR risk scenario Monte Carlo simulation at a time via FAIR Institute) + **14-day guided enterprise trial**. |

### [Kovrr](https://www.kovrr.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🎲 Private (Series A) |
| **Valuation** | ~$30M–$50M |
| **Revenue** | ~$4.1M ARR |
| **Funding** | ~$10M+ |
| **Description** | Financial Cyber Risk Quantification (Quantum CRQ) platform translating cyber posture into financial risk metrics (Average Annual Loss, Value at Risk, loss exceedance curves) and AI risk governance. |
| **Pricing** | Starts at **~$25,000 – $50,000/yr** for core Quantum CRQ enterprise subscription; scales based on company revenue tier and modeling depth. |
| **Free Tier / Trial** | 🆓 **Free tier** for AI Risk Register (first 5 AI risk scenarios free forever) + **14-day guided CRQ financial loss modeling trial**. |

### [FortifyData](https://www.fortifydata.com/)

| Attribute | Details |
|-----------|---------|
| **Company Size** | 🔍 Private (Series A) |
| **Valuation** | ~$20M–$30M |
| **Revenue** | ~$2.7M ARR |
| **Funding** | ~$7M |
| **Description** | Continuous cyber risk management and attack surface quantification platform assessing internal and external vulnerabilities to compute real-time risk ratings and compliance posture. |
| **Pricing** | Starts at **~$10,000 – $21,375/yr** (median entry tier for core external and internal asset monitoring). |
| **Free Tier / Trial** | 🆓 **Free plan** (quarterly external attack surface vulnerability assessment and security rating for 1 domain) + **14-day full feature trial**. |

---

## 🔓 Open-Source GitHub Projects

*Below is a curated list of top open-source tools, Monte Carlo engines, GRC platforms with native FAIR quantification, and risk modeling frameworks, sorted in descending order by GitHub Stars.*

### [CISO Assistant](https://github.com/intuitem/ciso-assistant-community)

🌐 Comprehensive open-source GRC and risk management platform featuring native support for Open FAIR risk assessments, automated Loss Exceedance Curve (LEC) generation, and Monte Carlo risk simulations.

### [cve-search](https://github.com/cve-search/cve-search)

🔍 Local vulnerability and exposure search engine and database importer (CVE, CWE, CPE, CAPEC) enabling fast risk scoring, vulnerability correlation, and threat exposure calculations.

### [riskquant](https://github.com/Netflix-Skunkworks/riskquant)

🐍 Netflix's open-source Python library for quantitative risk assessment; computes annualized loss expectancy (ALE) and Loss Exceedance Curves by fitting loss frequency and magnitude to lognormal probability distributions.

### [awesome-risk-quantification](https://github.com/veeral-patel/awesome-risk-quantification)

📚 Curated index and learning roadmap of resources, academic papers, books, and software implementations for quantitative information security risk analysis and FAIR modeling.

### [evaluator](https://github.com/davidski/evaluator)

📊 Open-source R toolkit for quantitative risk assessment based on the OpenFAIR ontology and risk analysis standard. Supports data-driven, repeatable FAIR-style simulation, parameter estimation, and graphical reporting.

### [pyfair](https://github.com/Derive-Risk/pyfair)

🎲 Python package implementing the Factor Analysis of Information Risk (FAIR) model for programmatic Monte Carlo risk simulations, distribution fitting, and risk scenario comparisons.

### [CRML (Cyber Risk Modeling Language)](https://github.com/Faux16/crml)

📝 Open-source declarative language and engine for writing "Risk as Code" (RaC). Provides YAML/JSON schemas to describe cyber risk models, telemetry mappings, and simulation pipelines in an engine-agnostic format.

### [Security Decision Labs](https://github.com/security-decision-science/security-decision-labs)

🧪 Collection of statistical decision science and FAIR CRQ toolkits, including agent-based control simulations (FAIR-CAM), Threat Event Frequency (TEF) estimators, and Value of Information (VoI) calculators.

### [OpenFAIR](https://github.com/OSUso/OpenFAIR)

📈 Lightweight R implementation for simulating Open FAIR cyber risk scenarios and calculating probabilistic annualized loss distributions.

### [Fair TPRM](https://www.fairtprm.com/)

📋 Free, self-hosted open-source Third-Party Risk Management (TPRM) & GRC platform that incorporates native FAIR risk quantification (ALE calculations), vendor compliance scoring, and continuous risk monitoring.

---

## 🧩 Architectural Blueprints for Custom CRQ

Organizations building custom internal Cyber Risk Quantification pipelines typically assemble a multi-layer stack:

### 1. **Telemetry & Ingestion Layer**
Ingest vulnerability scan data (Qualys, Nessus, OpenVAS), asset inventories, EPSS exploitability scores, CISA KEV feeds, and external attack surface exposures into a centralized lake or graph.

### 2. **Standardized Ontology Layer**
Map technical assets and vulnerabilities into the **Open FAIR™ Risk Taxonomy** (Threat Event Frequency × Vulnerability × Loss Magnitude).

### 3. **Simulation Engine Layer**
Execute 10,000–100,000 iterations using Python/R Monte Carlo engines (`riskquant`, `pyfair`, or `evaluator`) to generate probabilistic loss distributions.

### 4. **Executive Reporting Layer**
Output **Loss Exceedance Curves (LEC)**, **90th-percentile Cyber VaR**, and **Annualized Loss Expectancy (ALE)** to BI dashboards (Tableau, Grafana, Power BI) and board slide decks.

---

## 🤝 How to Contribute

We welcome contributions from cybersecurity practitioners, risk analysts, data scientists, and developers!

### Contribution Steps

1. 🍴 **Fork the repository** on GitHub.
2. 🌿 **Create a feature branch**: `git checkout -b add-new-crq-tool`
3. 📝 **Add your entry** in `README.md` following the format:
   - **For SaaS**: Include Name, Link, Valuation/Revenue size, Description, Starting Price, and specific Free Tier/Trial limits. Insert in the correct sorted order (by valuation/size).
   - **For Open-Source**: Include Repo Name, GitHub Link, and Description. Insert in the correct star-sorted order.
4. 🚀 **Submit a Pull Request** with a concise description of the contribution.

### Contribution Guidelines

- **Accuracy**: Ensure all pricing, valuations, and feature descriptions are current and verified.
- **Format Consistency**: Follow the existing markdown structure and emoji conventions.
- **Objectivity**: Avoid promotional language; focus on factual, neutral descriptions.
- **Sources**: Link to official product pages and documentation when available.
---

## ⚠️ Disclaimer

This repository is provided **as-is** for informational and educational purposes only. The information, including pricing, valuations, features, and free trial policies, is subject to change without notice and may not be current or accurate at the time of access.

**Users are solely responsible for**:
- Verifying all information directly with the official product vendors or their representatives.
- Conducting their own due diligence before making purchasing or implementation decisions.
- Evaluating products based on their specific organizational requirements.

**The maintainers of this repository**:
- Make no warranties, express or implied, regarding the accuracy, completeness, or timeliness of the information provided.
- Assume no liability for any errors, omissions, or delays in the information, or for any actions taken in reliance on the information.
- Do not endorse, recommend, or promote any specific vendors, products, or services listed.

By using this repository, you agree to release the maintainers from any claims or liabilities arising from your use of the information herein.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👥 Authors & Contributors

- **Original Curator**: [Your Name]
- **Contributors**: See [CONTRIBUTING.md](CONTRIBUTING.md)

---

**Last Updated**: August 2026  
**Version**: 1.0.0

---

### Quick Links

- 📖 [FAIR Institute Standards](https://www.fairinstitute.org/)
- 🔐 [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework/)
- 📊 [Value at Risk (VaR) Primer](https://en.wikipedia.org/wiki/Value_at_risk)
- 💰 [Return on Security Investment (ROSI)](https://en.wikipedia.org/wiki/Return_on_security_investment)
