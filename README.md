# OSINT-Based Threat Intelligence Assessment – Ping Identity

---

## 📌 Lab Concept
This project is an Open-Source Intelligence (OSINT) Cyber Threat Intelligence (CTI) assessment focused on evaluating the external threat exposure and risk profile of Ping Identity, a global Identity and Access Management (IAM) provider.

The lab demonstrates how SOC and CTI analysts can use passive intelligence collection to identify phishing risk, brand impersonation exposure, infrastructure visibility, and identity-centric threat vectors without interacting with or testing target systems.

The emphasis is on defensive intelligence, understanding business risk, and attacker tradecraft, rather than exploitation.

---

## 🎯 Objectives
- Conduct a structured OSINT-based threat intelligence assessment
- Identify phishing, brand impersonation, and identity-centric risks
- Assess publicly observable infrastructure exposure
- Evaluate potential attacker tradecraft and abuse scenarios
- Translate technical findings into business-relevant risk
- Produce ethical, defensible intelligence suitable for decision-making

---

## 🧠 Project Overview
This assessment applies the Cyber Threat Intelligence lifecycle to a real-world IAM organization using only publicly available data.  
It simulates how SOC and CTI teams support organizations by monitoring external attack surfaces, trusted brands, and identity ecosystems for early indicators of threat activity.

No scanning, exploitation, or intrusive techniques were used at any stage.

---

## 🛠 Tools & Methodologies Used

### OSINT & CTI Methodology
- Intelligence Requirements & Scoping
- Passive Collection
- Processing & Validation
- Threat Analysis
- Risk Assessment
- Intelligence Dissemination

### Tools Utilized
| Category | Tools |
|------|------|
| Search & Discovery | Google Dorks |
| Enumeration | theHarvester |
| Reputation Analysis | VirusTotal, AbuseIPDB |
| Exposure Mapping | Shodan |
| Email Security Analysis | MXToolbox |
| Historical Analysis | Wayback Machine |
| Frameworks | MITRE ATT&CK |

---

## 🔍 Key Findings
- No evidence of active compromise or data leakage
- No confirmed malicious look-alike domains or cloned portals
- Infrastructure exposure consistent with a mature SaaS IAM provider
- Email and DNS posture assessed as low risk
- Primary threat driver is trust, not technical weakness

---

## ⚠️ Threat Intelligence Insights
From an attacker perspective, Ping Identity is more likely to be targeted via indirect attack paths, including:

- Phishing and brand impersonation
- Credential harvesting via spoofed authentication flows
- MFA fatigue and social engineering
- Abuse of downstream customer trust relationships

Relevant MITRE ATT&CK techniques include:
- Phishing (T1566)
- Acquire Infrastructure – Domains (T1583.001)
- Active Scanning (T1595)
- MFA Request Generation (T1621)

---

## 📊 Risk Assessment
- **Technical Risk:** Low  
- **Business Impact:** Potentially High  
- **Overall Risk:** Low–High (trust-driven)

While infrastructure exposure is well managed, the impact of identity-centric attacks could be significant due to Ping Identity’s role in securing authentication for downstream customers.

---

## ✅ Key Takeaways
- Strong security posture does not eliminate intelligence-led risk
- IAM providers are high-value targets for trust exploitation
- OSINT is critical for early detection of phishing and brand abuse
- Passive intelligence supports proactive defense without intrusion
- Business risk often outweighs technical severity

---

## 🛡 Recommendations (High-Level)
- Continuous brand and domain monitoring
- Strict SPF, DKIM, and DMARC enforcement
- IAM-specific phishing awareness training
- Ongoing external attack surface monitoring
- Phishing-resistant MFA and risk-based access controls

---

## 📄 Full Report
The complete intelligence assessment, including methodology, evidence logs, analysis, and recommendations, is available here:

👉 **[Ping Identity OSINT CTI Report (PDF)](https://drive.google.com/file/d/1YXW0VZXsWVRbuCRtBFFqgnh-3HYcFDqG/view?usp=sharing)**

---

## 🧾 Ethical Considerations
This project was conducted using passive OSINT techniques only.  
No scanning, exploitation, or unauthorized access was performed.  
All findings are based on publicly available information and are presented for educational and defensive purposes.

---

## 🧠 Conclusion
This lab demonstrates how OSINT-driven threat intelligence supports SOC and CTI teams by identifying early-stage, trust-based threats before technical compromise occurs.

It highlights that for identity providers, visibility, monitoring, and intelligence-led defense are essential to protecting both the organization and its customers.

---

> “Security is not the absence of threats, but the discipline of noticing them.”  
> — Oluwamuyiwa Aikomo


---
