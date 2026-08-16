# 🚀 Quick Start Guide to Cyber Risk Quantification

Welcome! This guide will help you navigate this repository and get started with Cyber Risk Quantification (CRQ).

---

## 📍 What Is This Repository?

This is a comprehensive, curated index of:

- **Commercial SaaS platforms** for CRQ (Qualys, SecurityScorecard, etc.)
- **Open-source tools** and libraries for risk quantification
- **Frameworks and standards** (Open FAIR, NIST CSF, ISO/IEC)
- **Learning resources** and educational materials
- **Best practices** for implementing CRQ in your organization

---

## 🎯 Choose Your Path

### 👔 I'm a Risk Officer / CISO
**Goal**: Understand CRQ concepts and evaluate commercial platforms.

1. **Start Here**: Read the [README.md](../README.md) introduction
2. **Learn Terminology**: Check [GLOSSARY.md](../GLOSSARY.md) for key terms
3. **Explore Platforms**: Review the [SaaS & Commercial CRQ Platforms](../README.md#-saas--commercial-crq-platforms) section
4. **Deep Dive**: Study [Frameworks Guide](frameworks.md) to understand methodologies
5. **Next Steps**: Schedule POC/POV trials with 2–3 leading platforms

### 👨‍💻 I'm a Data Scientist / Analyst
**Goal**: Implement quantitative risk models and run simulations.

1. **Start Here**: Read the [README.md](../README.md) introduction
2. **Learn FAIR**: Study [Open FAIR Framework](frameworks.md#-open-fair-factor-analysis-of-information-risk) section
3. **Explore Tools**: Check [Open-Source GitHub Projects](../README.md#-open-source-github-projects) for Python/R libraries
4. **Learn By Doing**: Follow tutorials for:
   - [pyfair](https://github.com/Derive-Risk/pyfair) (Python)
   - [evaluator](https://github.com/davidski/evaluator) (R)
   - [riskquant](https://github.com/Netflix-Skunkworks/riskquant) (Python)
5. **Advanced**: Explore [Architectural Blueprints](../README.md#-architectural-blueprints-for-custom-crq)

### 🔧 I'm a DevOps / Security Engineer
**Goal**: Build custom CRQ pipelines and integrate with existing tools.

1. **Start Here**: Read [README.md](../README.md) introduction
2. **Understand Architecture**: Study [Architectural Blueprints](../README.md#-architectural-blueprints-for-custom-crq)
3. **Explore Risk as Code**: Check [CRML](https://github.com/Faux16/crml) and [RaC frameworks](frameworks.md)
4. **Tool Integration**: Review integration patterns with:
   - Vulnerability scanners (Qualys, Nessus, OpenVAS)
   - Threat intelligence feeds (CISA KEV, EPSS)
   - BI/Visualization tools (Tableau, Grafana, Power BI)
5. **Build Pipeline**: Use [pyfair](https://github.com/Derive-Risk/pyfair) or [riskquant](https://github.com/Netflix-Skunkworks/riskquant) as simulation engines

### 📚 I'm a Student / Educator
**Goal**: Learn quantitative cybersecurity risk analysis.

1. **Start Here**: Read [README.md](../README.md) introduction
2. **Study Foundations**: Review [Frameworks Guide](frameworks.md#-open-fair-factor-analysis-of-information-risk)
3. **Formal Learning**: Check [Learning Resources](learning-resources.md#-online-courses--certifications)
4. **Practice**: Try hands-on tutorials with open-source tools
5. **Certifications**: Pursue FAIR-C or FAIR-SP certification from [FAIR Institute](https://www.fairinstitute.org/certification)

---

## 📊 Understanding Key Concepts (2-Minute Overview)

### What Is Cyber Risk Quantification?

Instead of saying "Risk is HIGH," CRQ calculates: **"We face an estimated $5.2M loss at the 90th percentile annually."**

### The FAIR Formula

```
Risk = Threat Event Frequency (TEF) × Loss Magnitude (LM)
```

- **TEF**: How often will the attack occur? (e.g., 3 times/year)
- **LM**: What's the financial impact? (e.g., $2M per incident)
- **Risk**: 3 × $2M = $6M annually (expected value)

### Monte Carlo Simulations

Instead of single-point estimates, CRQ uses **10,000–100,000 simulations** to generate probability distributions:

- **Annualized Loss Expectancy (ALE)**: Average annual loss
- **Value at Risk (VaR)**: Worst-case loss at 90th percentile
- **Loss Exceedance Curve (LEC)**: Visual risk distribution

### Why Does This Matter?

✅ **Aligns risk with financial impact**  
✅ **Enables data-driven investment decisions**  
✅ **Communicates risk to board and executives**  
✅ **Prioritizes security improvements by ROI**  

---

## 🛠️ Quick Reference: Tools & Platforms

### Looking for a **Commercial SaaS Platform**?

See [SaaS & Commercial CRQ Platforms](../README.md#-saas--commercial-crq-platforms) for detailed comparison:

- Largest: **Qualys TruRisk** ($5.45B)
- Fastest Growing: **SecurityScorecard** ($1B)
- Best for FAIR: **RiskLens** or **Axio**
- Best for Third-Party Risk: **Black Kite**

### Looking for an **Open-Source Tool**?

See [Open-Source GitHub Projects](../README.md#-open-source-github-projects):

- **Best for Learning**: [pyfair](https://github.com/Derive-Risk/pyfair) (Python)
- **Best for Enterprise GRC**: [CISO Assistant](https://github.com/intuitem/ciso-assistant-community)
- **Best for Netflix-Style Analysis**: [riskquant](https://github.com/Netflix-Skunkworks/riskquant)
- **Best for Risk as Code**: [CRML](https://github.com/Faux16/crml)

### Looking for a **Framework**?

See [Frameworks Guide](frameworks.md):

- **FAIR**: Pure quantitative risk modeling
- **NIST CSF**: Strategic governance framework
- **ISO/IEC 27001**: ISMS implementation standard
- **C2M2**: Maturity assessment tool

---

## 📖 Navigation Guide

| File/Section | Purpose | Best For |
|--------------|---------|----------|
| [README.md](../README.md) | Main overview and platform comparison | Everyone |
| [GLOSSARY.md](../GLOSSARY.md) | Terminology and acronyms | Learning key terms |
| [CONTRIBUTING.md](../CONTRIBUTING.md) | How to contribute | Contributors |
| [CODE_OF_CONDUCT.md](../CODE_OF_CONDUCT.md) | Community guidelines | All members |
| [Frameworks Guide](frameworks.md) | Deep dive into FAIR, NIST CSF, ISO | Practitioners |
| [Learning Resources](learning-resources.md) | Courses, books, webinars | Students & learners |
| [Quick Start](.) | This guide! | First-time visitors |

---

## 🎓 Learning Path by Time Commitment

### ⏱️ 30 Minutes
- Read this Quick Start guide
- Skim [README.md](../README.md) introduction
- Review [GLOSSARY.md](../GLOSSARY.md) for key terms

### ⏱️ 2 Hours
- Study [Frameworks Guide](frameworks.md#-open-fair-factor-analysis-of-information-risk) FAIR section
- Compare 3–4 commercial platforms from [SaaS section](../README.md#-saas--commercial-crq-platforms)
- Review open-source tools and star counts

### ⏱️ 1 Day
- Read NIST Cybersecurity Framework section
- Explore FAIR certification requirements from [FAIR Institute](https://www.fairinstitute.org/)
- Try a tutorial with [pyfair](https://github.com/Derive-Risk/pyfair) or [evaluator](https://github.com/davidski/evaluator)

### ⏱️ 1 Week
- Complete a FAIR online course
- Implement a proof-of-concept risk model
- Evaluate 2–3 commercial platforms via trial/POC

### ⏱️ 1 Month
- Deep dive into FAIR certification training
- Build a custom CRQ pipeline
- Present findings to stakeholders

---

## 🤔 FAQ: Common Questions

### **Q: What's the difference between FAIR and NIST CSF?**

**A:** 
- **FAIR**: Quantifies risk into dollar amounts ($)
- **NIST CSF**: Provides governance framework for security programs
- **Use Together**: NIST CSF sets strategy, FAIR quantifies risk

*See [Frameworks Guide](frameworks.md) for details.*

### **Q: Should I use open-source tools or commercial platforms?**

**A:**
- **Open-Source**: ✅ Free, ✅ Customizable, ❌ Requires expertise
- **Commercial**: ✅ Support & automation, ✅ Scalable, ❌ Costly
- **Best Approach**: Start with open-source pilot, scale with commercial

*See [Architectural Blueprints](../README.md#-architectural-blueprints-for-custom-crq) for recommendations.*

### **Q: How do I get started with FAIR?**

**A:**
1. Read [FAIR Framework section](frameworks.md#-open-fair-factor-analysis-of-information-risk)
2. Explore [Learning Resources](learning-resources.md)
3. Try [pyfair](https://github.com/Derive-Risk/pyfair) tutorial
4. Consider FAIR-C certification from [FAIR Institute](https://www.fairinstitute.org/certification)

### **Q: How often should we update risk assessments?**

**A:** Industry best practice is **quarterly to annually**:
- **Continuous monitoring** for real-time threat changes
- **Formal reassessment** at minimum annually
- **Trigger-based updates** after security incidents, policy changes, or major system changes

---

## ✅ Next Steps

### For Executives / CISOs:
1. ✅ Schedule a meeting with your risk/analytics team
2. ✅ Review 2–3 commercial platforms from the [SaaS section](../README.md#-saas--commercial-crq-platforms)
3. ✅ Plan a pilot CRQ program (3–6 months)
4. ✅ Allocate budget for tools or training

### For Technical Teams:
1. ✅ Clone and explore [pyfair](https://github.com/Derive-Risk/pyfair) or [evaluator](https://github.com/davidski/evaluator)
2. ✅ Develop a proof-of-concept risk model
3. ✅ Identify data sources (vulnerability scans, asset inventory, threat feeds)
4. ✅ Build a Monte Carlo simulation pipeline

### For Everyone:
1. ✅ Review the [GLOSSARY.md](../GLOSSARY.md) to learn terminology
2. ✅ Explore [Learning Resources](learning-resources.md) for deeper knowledge
3. ✅ Join the [FAIR Institute](https://www.fairinstitute.org/) or open-source communities
4. ✅ Contribute to this repository with your findings!

---

## 💬 Have Questions or Feedback?

- **File an Issue**: Report problems or suggest improvements
- **Submit a Pull Request**: Add resources, fix errors, or expand content
- **Join Community**: Connect with other CRQ practitioners

See [CONTRIBUTING.md](../CONTRIBUTING.md) for details.

---

## 🌟 Recommended Reading Order

1. 📖 [README.md](../README.md) - Overview
2. 📖 [GLOSSARY.md](../GLOSSARY.md) - Terminology
3. 📖 [Quick Start Guide](#) - This guide
4. 📖 [Frameworks Guide](frameworks.md) - Deep dive into FAIR
5. 📖 [Learning Resources](learning-resources.md) - Courses & certifications
6. 📖 [CONTRIBUTING.md](../CONTRIBUTING.md) - How to help

---

## 🎯 Good Luck!

CRQ is a powerful discipline for bringing objectivity and financial clarity to cybersecurity risk. Whether you're evaluating platforms, learning quantitative methods, or building custom solutions, this repository is here to support your journey.

**Let's make cybersecurity more quantifiable, defensible, and strategic.** 🚀

---

**Last Updated**: August 2026  
**Questions?** Open an issue or discussion on GitHub!
