# Cyber Risk Quantification Frameworks & Standards

A comprehensive guide to the key frameworks, standards, and methodologies used in Cyber Risk Quantification.

---

## 📊 Open FAIR™ (Factor Analysis of Information Risk)

### Overview

**Open FAIR** is the gold standard, open-source quantitative risk analysis framework adopted globally for cyber risk quantification. It decomposes risk into measurable components that can be analyzed probabilistically.

### FAIR Risk Equation

```
Risk = Threat Event Frequency (TEF) × Loss Magnitude (LM)
```

Where:

- **Threat Event Frequency (TEF)**: How often a threat event is likely to occur (measured per year or time period)
- **Loss Magnitude (LM)**: The financial impact if the event occurs

### FAIR Risk Taxonomy

```
Risk
├── Threat Event Frequency (TEF)
│   ├── Threat Agent
│   ├── Vulnerability
│   └── Contact Frequency
│
└── Loss Magnitude (LM)
    ├── Primary Loss
    │   ├── Replacement/Recovery Costs
    │   ├── Productivity Loss
    │   └── Response Costs
    │
    └── Secondary Loss
        ├── Reputation/Market Value
        ├── Legal/Regulatory
        ├── Customer Defection
        └── Competitive Disadvantage
```

### FAIR Analysis Process

1. **Define Scope**: Identify the asset, threat, and scenario to be analyzed.
2. **Gather Data**: Collect quantitative data on vulnerabilities, threats, and impacts.
3. **Estimate Parameters**: Use expert judgment and statistical distributions to estimate FAIR factors.
4. **Run Simulations**: Execute 10,000–100,000 Monte Carlo iterations.
5. **Generate Results**: Produce probabilistic loss distributions (ALE, VaR, LEC).
6. **Report Findings**: Communicate results to stakeholders and executives.

### FAIR Outputs

- **Annualized Loss Expectancy (ALE)**: Average annual loss ($)
- **Value at Risk (VaR)**: Loss at a given confidence level (e.g., 90th percentile)
- **Loss Exceedance Curve (LEC)**: Probability distribution of losses
- **Risk Scenarios**: Comparative analysis of multiple risk scenarios

### FAIR Resources

- **FAIR Institute Official Site**: https://www.fairinstitute.org/
- **Open FAIR Standard**: https://www.fairinstitute.org/open-fair
- **FAIR Certification**: https://www.fairinstitute.org/certification

---

## 🛡️ NIST Cybersecurity Framework (CSF)

### Overview

The **NIST Cybersecurity Framework** is a flexible, market-driven framework providing guidelines for managing cybersecurity risk and compliance.

### Core Functions

| Function | Description |
|----------|-------------|
| **Identify** | Understand business context, resources, and risks |
| **Protect** | Implement safeguards and protective measures |
| **Detect** | Monitor and detect cybersecurity events |
| **Respond** | Contain, mitigate, and recover from incidents |
| **Recover** | Restore operations and services |

### Implementation Tiers

- **Tier 1 (Partial)**: Risk management is ad hoc and reactive.
- **Tier 2 (Risk Informed)**: Risk management processes are approved and understood.
- **Tier 3 (Repeatable)**: Risk management policies are formalized and documented.
- **Tier 4 (Adaptive)**: Risk management is continuous and adaptive.

### NIST CSF vs. FAIR

| Aspect | NIST CSF | FAIR |
|--------|----------|------|
| **Purpose** | Governance and compliance | Quantitative risk analysis |
| **Output** | Maturity levels | Financial loss estimates |
| **Use Case** | Strategic planning | Risk prioritization |
| **Integration** | Often used together with FAIR |

### NIST CSF Resources

- **Official Framework**: https://www.nist.gov/cyberframework/
- **Crosswalk with ISO/IEC 27001**: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5

---

## 📐 ISO/IEC Standards

### ISO/IEC 27001:2022 - Information Security Management

International standard for establishing and maintaining information security management systems (ISMS).

**Key Components**:
- Information security policies and processes
- Risk assessment and treatment
- Compliance and certification

### ISO/IEC 27005:2022 - Information Security Risk Management

Guidelines for implementing systematic risk management processes in information security.

**Risk Management Process**:
1. Context establishment
2. Risk assessment
3. Risk treatment
4. Risk monitoring and review

### ISO/IEC 31000:2018 - Risk Management Guidelines

Universal enterprise risk management framework applicable across all industries.

**Principles**:
- Creates and protects value
- Integral to organizational processes
- Improves decision-making
- Addresses uncertainty

---

## 🏆 NIST Risk Management Framework (RMF)

### Overview

The **NIST RMF** is a six-step process for managing cybersecurity risk in federal agencies and critical infrastructure.

### Six Steps

| Step | Activity |
|------|----------|
| 1. **Prepare** | Establish risk management foundation |
| 2. **Categorize** | Classify information and systems |
| 3. **Select** | Choose security controls |
| 4. **Implement** | Deploy and document controls |
| 5. **Assess** | Evaluate control effectiveness |
| 6. **Authorize** | Make risk-based authorization decision |

### Continuous Monitoring

- Ongoing assessment of control effectiveness
- Regular vulnerability and compliance scanning
- Threat intelligence integration
- Risk reassessment at defined intervals

---

## 🎯 NIST Incident Response Framework

### Four Phases

1. **Preparation**: Establish incident response capability
2. **Detection and Analysis**: Identify and investigate incidents
3. **Containment, Eradication, and Recovery**: Stop, remove, and restore
4. **Post-Incident Activity**: Review and improve

---

## 📋 C2M2 (Cybersecurity Capability Maturity Model)

### Overview

A self-assessment model developed by CISA for measuring cybersecurity capabilities across organizations.

### Key Features

- **22 Key Practices** across 5 functional domains
- **5 Maturity Levels** (Ad Hoc to Optimized)
- **Self-Assessment** tool for organizations
- **Prioritization** for investments and improvements

### Five Functional Domains

1. **Asset and Configuration Management**
2. **Incident Response and Management**
3. **Access Control Management**
4. **Risk and Vulnerability Management**
5. **Security Architecture and Program Management**

### C2M2 Resources

- **CISA C2M2 Tool**: https://www.cisa.gov/c2m2

---

## 🏭 FAIR Institute Supply Chain Risk Management (SCRM)

### Overview

Adaptation of FAIR methodology for assessing risks in supply chain and third-party relationships.

### Key Considerations

- **Vendor Risk Quantification**: FAIR-based scoring of supplier risks
- **Inherent vs. Residual Risk**: Risk before and after controls
- **Risk Aggregation**: Cumulative risk from multiple vendors
- **Risk Tolerance**: Organizational risk appetite and thresholds

---

## 💡 Threat Modeling Frameworks

### STRIDE

**Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege**

- Systematic approach to identifying threats
- Often combined with FAIR for quantification

### Attack Trees

Visual representation of attack paths and scenarios.

**Benefits**:
- Identifies critical vulnerabilities
- Helps prioritize controls
- Supports FAIR-based quantification

### CVSS (Common Vulnerability Scoring System)

Standardized scoring system for vulnerability severity (0–10 scale).

**Versions**:
- **CVSS v3.1**: Current standard
- **CVSS v4.0**: Emerging standard with improved context awareness

---

## 📊 Quantitative vs. Qualitative Risk Assessment

### Quantitative Approach (Recommended for CRQ)

| Aspect | Details |
|--------|---------|
| **Methodology** | FAIR, Monte Carlo simulations |
| **Outputs** | Dollar amounts ($), percentiles (VaR), curves (LEC) |
| **Precision** | High (objective financial metrics) |
| **Stakeholder Appeal** | Board and C-suite friendly |
| **Example** | "We face a 90th percentile loss of $5.2M annually" |

### Qualitative Approach (Traditional)

| Aspect | Details |
|--------|---------|
| **Methodology** | Expert judgment, heat maps |
| **Outputs** | Ratings (High/Medium/Low) |
| **Precision** | Low (subjective ordinal scales) |
| **Stakeholder Appeal** | Limited executive adoption |
| **Example** | "Threat to confidential data is rated High" |

---

## 🔗 Framework Interoperability

### How Frameworks Work Together

```
NIST CSF (Strategic Framework)
        ↓
ISO/IEC 27001 (Governance)
        ↓
NIST RMF (Implementation Process)
        ↓
FAIR (Quantitative Analysis)
        ↓
C2M2 (Maturity Measurement)
```

### Example Workflow

1. Use **NIST CSF** to define governance strategy
2. Implement **ISO/IEC 27001** ISMS controls
3. Follow **NIST RMF** authorization process
4. Apply **FAIR** for quantitative risk analysis
5. Measure progress using **C2M2** maturity levels

---

## 📈 Modern Risk Management Trends

### Continuous Risk Management (CRM)

- Real-time monitoring and assessment
- Automated data ingestion and analysis
- Dynamic risk scoring and prioritization
- Integration with threat intelligence feeds

### Risk as Code (RaC)

- Declarative risk models in version control
- Reproducible and auditable simulations
- Programmatic integration with security tools
- DevSecOps alignment

### AI-Assisted Risk Quantification

- Machine learning for parameter estimation
- Anomaly detection in risk patterns
- Predictive risk modeling
- Natural language processing for threat intelligence

---

## 🎓 Implementing CRQ Frameworks in Your Organization

### Phase 1: Foundation (Months 1–3)
- Select framework (FAIR recommended)
- Establish governance and ownership
- Train core team
- Define risk scenarios

### Phase 2: Pilot (Months 4–6)
- Run pilot risk analyses
- Gather baseline data
- Validate assumptions
- Refine processes

### Phase 3: Deployment (Months 7–12)
- Integrate with existing tools
- Scale to enterprise
- Automate data collection
- Establish reporting cadence

### Phase 4: Continuous Improvement (Ongoing)
- Monitor and validate results
- Update models and parameters
- Benchmark against industry
- Maintain stakeholder engagement

---

## 📚 Additional Resources

- **NIST Publications**: https://csrc.nist.gov/publications/
- **ISO/IEC Standards**: https://www.iso.org/isoiec-27001-information-security.html
- **FAIR Institute**: https://www.fairinstitute.org/
- **CISA Resources**: https://www.cisa.gov/

---

**Last Updated**: August 2026
