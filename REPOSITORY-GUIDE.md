# 📁 Repository Structure & File Guide

A complete overview of all files and directories in the Cyber Risk Quantification repository.

---

## 🗂️ Directory Tree

```
Cyber-Risk-Quantification/
│
├── README.md                          # Main repository overview and platform comparisons
├── GLOSSARY.md                        # Terminology, acronyms, and definitions
├── CONTRIBUTING.md                    # Contribution guidelines and submission process
├── CODE_OF_CONDUCT.md                 # Community standards and conduct expectations
├── LICENSE                            # MIT License
├── SUBMISSION_TEMPLATE.md             # Template for proposing new platforms/tools
├── .gitignore                         # Git ignore rules for version control
│
└── resources/                         # Additional educational and reference materials
    ├── QUICK-START.md                # Quick start guide for different user roles
    ├── frameworks.md                 # Deep dive into FAIR, NIST CSF, ISO/IEC standards
    └── learning-resources.md         # Curated educational materials, courses, papers
```

---

## 📄 File Descriptions

### Root Level Files

#### `README.md` ⭐ **START HERE**
- **Purpose**: Main repository entry point and comprehensive platform guide
- **Content**: 
  - Introduction to CRQ concepts
  - Table of contents
  - SaaS & Commercial platforms comparison (13+ platforms)
  - Open-source GitHub projects (10+ tools)
  - Architectural blueprints for custom implementations
  - Contribution guidelines
- **Audience**: Everyone (CISOs, analysts, developers, students)
- **Length**: ~15–20 minutes to read
- **Key Sections**:
  - [🏢 SaaS & Commercial CRQ Platforms](README.md#-saas--commercial-crq-platforms)
  - [🔓 Open-Source GitHub Projects](README.md#-open-source-github-projects)
  - [🧩 Architectural Blueprints](README.md#-architectural-blueprints-for-custom-crq)

---

#### `GLOSSARY.md` 📚 **TERMINOLOGY REFERENCE**
- **Purpose**: Comprehensive dictionary of CRQ and cybersecurity terms
- **Content**:
  - Alphabetical glossary (A–Z)
  - 60+ terms and acronyms
  - Clear, concise definitions
  - Cross-references between related terms
  - Reference table of all acronyms
- **Audience**: Learners, newcomers, non-technical stakeholders
- **Use Case**: Quick lookup for unfamiliar terms while reading other materials
- **Key Sections**:
  - Individual term definitions (ALE, FAIR, NIST CSF, VaR, etc.)
  - Acronyms reference table

---

#### `CONTRIBUTING.md` 🤝 **CONTRIBUTION GUIDE**
- **Purpose**: Instructions for contributing to the repository
- **Content**:
  - Code of conduct and principles
  - How to report issues
  - Contribution guidelines for SaaS and open-source entries
  - Step-by-step submission process (fork, commit, PR)
  - Pull request checklist
  - Review process and timeline
- **Audience**: Contributors, maintainers, community members
- **Use Case**: Before submitting changes, additions, or corrections
- **Key Sections**:
  - [Code of Conduct](CONTRIBUTING.md#code-of-conduct)
  - [Contribution Guidelines](CONTRIBUTING.md#contribution-guidelines)
  - [Submission Process](CONTRIBUTING.md#submission-process)
  - [Pull Request Checklist](CONTRIBUTING.md#pull-request-checklist)

---

#### `CODE_OF_CONDUCT.md` ⚖️ **COMMUNITY STANDARDS**
- **Purpose**: Establish inclusive, respectful community expectations
- **Content**:
  - Community commitment statement
  - Standards for acceptable behavior
  - Examples of unacceptable behavior
  - Enforcement and consequences
  - Violation reporting process
  - Scope and applicability
- **Audience**: All community members
- **Use Case**: Reference for community interactions on GitHub
- **Attribution**: Based on Contributor Covenant 2.1

---

#### `LICENSE` 📜 **LEGAL TERMS**
- **Purpose**: Open-source license for the repository
- **Type**: MIT License (permissive, allows commercial use)
- **Key Terms**:
  - Free to use, modify, distribute
  - Must include copyright notice
  - No liability or warranty
- **Audience**: Legal/compliance teams, contributors

---

#### `SUBMISSION_TEMPLATE.md` 📋 **CONTRIBUTOR TEMPLATE**
- **Purpose**: Structured template for proposing new platforms/tools
- **Content**:
  - SaaS platform submission form
  - Open-source project submission form
  - Required fields and validation checks
  - Submission checklist
  - Verification requirements
- **Audience**: Contributors adding new entries
- **Use Case**: Ensure consistent, accurate information in submissions
- **Key Sections**:
  - [SaaS Platform Template](SUBMISSION_TEMPLATE.md#-saas-platform-submission-template)
  - [Open-Source Project Template](SUBMISSION_TEMPLATE.md#-open-source-project-submission-template)
  - [Submission Checklist](SUBMISSION_TEMPLATE.md#-submission-checklist)

---

#### `.gitignore` 🚫 **GIT CONFIGURATION**
- **Purpose**: Define files and directories to exclude from version control
- **Content**:
  - OS files (macOS .DS_Store, Windows Thumbs.db)
  - IDE settings (.vscode, .idea, .sublime-project)
  - Language-specific directories (node_modules, __pycache__, venv)
  - Build and temporary files
  - Environment variables and sensitive data
- **Use Case**: Automatic Git ignore rules

---

### Resources Directory

#### `resources/QUICK-START.md` 🚀 **RECOMMENDED SECOND STOP**
- **Purpose**: Guided introduction tailored to different user roles
- **Content**:
  - "Choose your path" based on role (CISO, analyst, engineer, student)
  - 2-minute CRQ concept overview
  - Quick reference: tools and platforms
  - Navigation guide to all repository files
  - Learning paths by time commitment (30 min to 1 month)
  - FAQ with common questions
  - Next steps for each role
- **Audience**: First-time visitors, specific professional roles
- **Length**: ~10–15 minutes to read
- **Key Sections**:
  - [Choose Your Path](resources/QUICK-START.md#-choose-your-path)
  - [Understanding Key Concepts](resources/QUICK-START.md#-understanding-key-concepts-2-minute-overview)
  - [Learning Path by Time Commitment](resources/QUICK-START.md#-learning-path-by-time-commitment)
  - [FAQ](resources/QUICK-START.md#-faq-common-questions)

---

#### `resources/frameworks.md` 📊 **DEEP DIVE INTO STANDARDS**
- **Purpose**: Comprehensive guide to CRQ frameworks and standards
- **Content**:
  - **Open FAIR™**: Full framework explanation, risk equation, taxonomy, process, outputs
  - **NIST Cybersecurity Framework (CSF)**: Core functions, implementation tiers, comparison with FAIR
  - **ISO/IEC Standards**: 27001, 27005, 31000 overview
  - **NIST Risk Management Framework (RMF)**: Six-step process and continuous monitoring
  - **NIST Incident Response Framework**: Four phases
  - **C2M2**: Cybersecurity Capability Maturity Model
  - **FAIR Institute SCRM**: Supply chain risk management
  - **Threat Modeling**: STRIDE, Attack Trees, CVSS
  - **Quantitative vs. Qualitative**: Comparison and recommendations
  - **Framework Interoperability**: How frameworks work together
  - **Modern Trends**: Continuous risk management, Risk as Code, AI-assisted quantification
  - **Implementation Roadmap**: Phased approach (4 phases over 1 year)
- **Audience**: Risk officers, analysts, practitioners, technical teams
- **Length**: ~30–45 minutes to read thoroughly
- **Key Sections**:
  - [Open FAIR™](resources/frameworks.md#-open-fair-factor-analysis-of-information-risk)
  - [NIST Cybersecurity Framework](resources/frameworks.md#-nist-cybersecurity-framework-csf)
  - [ISO/IEC Standards](resources/frameworks.md#-isoiec-standards)
  - [Framework Interoperability](resources/frameworks.md#-framework-interoperability)
  - [Implementing CRQ in Your Organization](resources/frameworks.md#-implementing-crq-frameworks-in-your-organization)

---

#### `resources/learning-resources.md` 📚 **EDUCATIONAL MATERIALS**
- **Purpose**: Curated collection of training, courses, papers, and resources
- **Content**:
  - **Books & Textbooks**: Foundational texts (Hubbard, NIST, FAIR Institute)
  - **Online Courses & Certifications**: FAIR-C/SP, Coursera, LinkedIn Learning, SANS
  - **Academic Papers**: NIST publications, FAIR methodology papers
  - **Standards & Frameworks**: Official FAIR, NIST CSF, ISO/IEC documents
  - **Webinars & Presentations**: FAIR Institute events, RSA, Black Hat
  - **Tools & Software Tutorials**: pyfair, evaluator, Qualys University
  - **Industry Publications**: Gartner, Forrester, SecurityMetrics blogs
  - **Professional Organizations**: FAIR Institute, ISACA communities
  - **Online Communities**: Reddit, Slack, GitHub discussions
  - **Data Sources**: CVE, EPSS, CISA KEV, cyber insurance reports
  - **University Programs**: Carnegie Mellon SEI, UC Davis, Maryland
  - **Getting Started Path**: Recommended 4-week learning sequence
- **Audience**: Students, learners, practitioners seeking deeper knowledge
- **Length**: Reference material (30+ minutes to browse)
- **Key Sections**:
  - [Books & Textbooks](resources/learning-resources.md#-books--textbooks)
  - [Online Courses & Certifications](resources/learning-resources.md#-online-courses--certifications)
  - [Academic Papers](resources/learning-resources.md#-academic-papers--research)
  - [Getting Started Path](resources/learning-resources.md#-getting-started-path)

---

## 🗺️ Navigation Recommendations

### By Use Case

**Planning a CRQ Program?**
1. Start: [README.md](README.md) (introduction)
2. Read: [QUICK-START.md](resources/QUICK-START.md) (role-specific guidance)
3. Study: [frameworks.md](resources/frameworks.md) (understand standards)
4. Explore: [SaaS platforms section](README.md#-saas--commercial-crq-platforms) (vendor evaluation)

**Implementing a Custom CRQ Pipeline?**
1. Start: [README.md](README.md) (overview)
2. Read: [Architectural Blueprints](README.md#-architectural-blueprints-for-custom-crq)
3. Explore: [Open-source projects](README.md#-open-source-github-projects)
4. Study: [frameworks.md](resources/frameworks.md#-open-fair-factor-analysis-of-information-risk) (FAIR deep dive)
5. Learn: [learning-resources.md](resources/learning-resources.md#-tools--software-tutorials) (tool tutorials)

**Learning CRQ from Scratch?**
1. Start: [QUICK-START.md](resources/QUICK-START.md#-i-m-a-student--educator) (learning path)
2. Study: [GLOSSARY.md](GLOSSARY.md) (terminology)
3. Read: [frameworks.md](resources/frameworks.md) (foundational concepts)
4. Explore: [learning-resources.md](resources/learning-resources.md) (courses & books)
5. Practice: [Open-source tools](README.md#-open-source-github-projects) (hands-on experience)

**Contributing to the Repository?**
1. Read: [CONTRIBUTING.md](CONTRIBUTING.md) (guidelines)
2. Review: [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) (standards)
3. Use: [SUBMISSION_TEMPLATE.md](SUBMISSION_TEMPLATE.md) (template)
4. Follow: [PR checklist](CONTRIBUTING.md#pull-request-checklist)

---

## 📊 File Statistics

| File | Type | Length | Purpose |
|------|------|--------|---------|
| README.md | Markdown | ~8KB | Main overview & platform guide |
| GLOSSARY.md | Markdown | ~12KB | Terminology reference |
| CONTRIBUTING.md | Markdown | ~8KB | Contribution guidelines |
| CODE_OF_CONDUCT.md | Markdown | ~4KB | Community standards |
| SUBMISSION_TEMPLATE.md | Markdown | ~10KB | Contributor template |
| resources/QUICK-START.md | Markdown | ~12KB | Quick-start guide |
| resources/frameworks.md | Markdown | ~15KB | Framework deep dive |
| resources/learning-resources.md | Markdown | ~14KB | Educational materials |

---

## 🔄 Content Relationships

```
README.md (Entry Point)
├─→ QUICK-START.md (Role-based guidance)
├─→ GLOSSARY.md (Terminology)
├─→ CONTRIBUTING.md (How to contribute)
│   └─→ SUBMISSION_TEMPLATE.md (Submission form)
│   └─→ CODE_OF_CONDUCT.md (Community standards)
└─→ resources/
    ├─→ frameworks.md (Technical deep dives)
    └─→ learning-resources.md (Education & training)
```

---

## 🎯 Quick Links by Role

### For CISOs & Risk Officers
- [README.md](README.md) - Platform overview
- [QUICK-START.md](resources/QUICK-START.md#👔-im-a-risk-officer--ciso) - Role-specific guide
- [SaaS Platforms](README.md#-saas--commercial-crq-platforms) - Vendor evaluation

### For Data Scientists & Analysts
- [frameworks.md](resources/frameworks.md#-open-fair-factor-analysis-of-information-risk) - FAIR methodology
- [Open-source Projects](README.md#-open-source-github-projects) - Tools & libraries
- [learning-resources.md](resources/learning-resources.md#-tools--software-tutorials) - Tutorials

### For Engineers & DevOps
- [Architectural Blueprints](README.md#-architectural-blueprints-for-custom-crq) - Pipeline design
- [Open-source Projects](README.md#-open-source-github-projects) - Technical tools
- [CRML Project](https://github.com/Faux16/crml) - Risk as Code

### For Students & Educators
- [QUICK-START.md](resources/QUICK-START.md#-im-a-student--educator) - Learning path
- [GLOSSARY.md](GLOSSARY.md) - Key terms
- [learning-resources.md](resources/learning-resources.md) - Courses & certifications

---

## 📝 How to Use This Guide

1. **Locate your information need** in the "File Descriptions" section above
2. **Follow the recommended reading path** for your role
3. **Use Quick Links** for fast navigation
4. **Reference Content Relationships** to understand how files connect
5. **Check File Statistics** to estimate reading time

---

**Repository Version**: 1.0.0  
**Last Updated**: August 2026  
**Maintained By**: Cyber Risk Quantification Community
