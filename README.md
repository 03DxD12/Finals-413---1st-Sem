# ITEP 413: Information Assurance and Security 2 – Finals Reviewer
### Laguna State Polytechnic University | College of Computer Studies

[![Mobile Friendly](https://img.shields.io/badge/Mobile-Optimized-success?style=flat-square&logo=android)](https://03dxd12.github.io/Finals-413---1st-Sem/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Topics](https://img.shields.io/badge/Topics-Ethics%20%7C%20Compliance%20%7C%20FISMA%20%7C%20Certifications-orange?style=flat-square)](#table-of-contents)

> **Quick Study Web App:** An interactive, mobile-ready web app with interactive quizzes, flashcards, and searchable reference tables is included in [`index.html`](index.html).

---

## 📱 Table of Contents
1. [Quick Practice Scenarios (Top 10 Q&A with Tap-to-Reveal)](#-1-practice-scenarios-top-10-exam-questions)
2. [Professional Education, Training, and Certification](#-2-professional-education-training-and-certification)
   - [Awareness vs. Training vs. Education](#awareness-training-and-education)
   - [NIST Learning Cycle & Self-Study Rules](#nist-learning-cycle--self-study-rules)
   - [Certifications (Vendor-Neutral vs. Vendor-Specific)](#certifications-comparison)
   - [Workforce Frameworks (DoD 8140 & NICE)](#cybersecurity-workforce-frameworks)
3. [Ethics, Compliance, and FISMA](#-3-ethics-compliance-and-fisma)
   - [Law vs. Ethics & ISC2 Canons](#law-versus-ethics)
   - [Compliance Matrix (FISMA, HIPAA, GLBA, SOX, FERPA, CIPA, PCI DSS)](#regulatory-compliance-matrix)
   - [FISMA Deep Dive & 2015 OPM Breach](#fisma-federal-information-security-modernization-act)
   - [Philippine Cyber Laws (RA 10173 & RA 10175)](#philippine-cyber-laws)
4. [Must-Know Acronyms Reference (47 Essential Acronyms)](#-4-must-know-acronyms-reference)
5. [GitHub Repository & Hosting Setup](#-5-github-repository-setup)

---

## 🎯 1. Practice Scenarios (Top 10 Exam Questions)

> **Tip for Mobile Review:** Tap each question below to reveal the verified answer and explanation!

<details>
<summary><b>1. A poster for all staff, a vendor course for firewall administrators, and a master's degree in cybersecurity: label each as awareness, training, or education.</b></summary>
<br>

- **Poster:** **Awareness** *(Short messages, general reminders for everyone to notice security).*
- **Vendor course:** **Training** *(Hands-on technical skills for a specific job).*
- **Master's degree:** **Education** *(Deep academic theory, long-term learning building understanding and judgment).*

**Memory Aid:**
- *Awareness* tells you **that**
- *Training* teaches you **how**
- *Education* helps you understand **why**
</details>

<details>
<summary><b>2. A friend offers you a copy of the real exam answers. Which ISC2 canon is at stake and what do you do?</b></summary>
<br>

- **Canon at Stake:** **Canon 2** — *Act honorably, honestly, justly, responsibly, and legally.*
- **Proper Action:** Refuse the exam answers immediately, do not view or download them, and report the security breach to ISC2.
</details>

<details>
<summary><b>3. Which U.S. law requires financial institutions to keep a written information security program for customer information?</b></summary>
<br>

- **Law:** **Gramm-Leach-Bliley Act (GLBA)** (specifically the **GLBA Safeguards Rule**).
- **Protects:** Nonpublic Personal Information (NPI).
</details>

<details>
<summary><b>4. A company asks a university for a student's grades. Which law controls whether the school may release them, and what is usually needed?</b></summary>
<br>

- **Governing Law:** **Family Educational Rights and Privacy Act (FERPA)**.
- **Requirement:** **Signed, written consent from the student** (or a specific legal exception).
</details>

<details>
<summary><b>5. A public company's chief executive must certify its financial reports. Which law requires this?</b></summary>
<br>

- **Law:** **Sarbanes-Oxley Act of 2002 (SOX)** (specifically **Section 302**).
- **Target:** Corporate officers must certify accuracy and the adequacy of internal financial controls.
</details>

<details>
<summary><b>6. Is PCI DSS a law with criminal penalties? Explain.</b></summary>
<br>

- **Answer:** **No.**
- **Explanation:** PCI DSS is an **industry contractual standard** created by major payment card brands (Visa, Mastercard, AMEX, Discover, JCB), not a legislative law.
- **Consequences:** Violations do not result in criminal jail time; instead, they trigger bank fines, increased transaction fees, audits, or complete revocation of credit card processing privileges.
</details>

<details>
<summary><b>7. After an incident, a manager wants to punish the employee who reported it. How does this hurt a security program?</b></summary>
<br>

- **Impact:** It creates a toxic **culture of fear** where employees hide mistakes, conceal system compromises, and avoid reporting anomalies.
- **Result:** This delays incident detection, allows attackers to maintain persistence, and causes far greater organizational damage.
</details>

<details>
<summary><b>8. A Philippine startup collects customers' email addresses. Name the three principles of RA 10173 it must follow.</b></summary>
<br>

The three core principles under the **Data Privacy Act of 2012 (RA 10173)** are:
1. **Transparency:** The data subject must be aware of the nature, purpose, and extent of data processing.
2. **Legitimate Purpose:** Processing must be compatible with declared, specified, and lawful purposes.
3. **Proportionality:** Processing must be adequate, relevant, suitable, necessary, and not excessive in relation to declared purposes.
</details>

<details>
<summary><b>9. An agency says last year's FISMA review was fine, so it can stop monitoring this year. What is wrong with this thinking?</b></summary>
<br>

- **Correction:** FISMA mandates **continuous monitoring**, not a one-time checklist audit.
- **Reason:** IT environments, software patches, system configurations, and adversary tactics change continuously. A pass last year provides zero guarantee of security today.
</details>

<details>
<summary><b>10. While browsing a company's website, you notice a flaw that exposes customer data. List what you should and should not do.</b></summary>
<br>

- **What you SHOULD do:**
  1. Stop browsing/testing immediately.
  2. Note only the basic URL and high-level indicator without collecting data.
  3. Responsibly and privately report the vulnerability to the organization's security team.
- **What you should NOT do:**
  1. **Do not** download, copy, or view sensitive customer records.
  2. **Do not** run automated scans or exploit the vulnerability further.
  3. **Do not** post the vulnerability publicly on social media or forums.
  4. **Do not** extort money or demand bug bounties under threat of disclosure.
</details>

---

## 🎓 2. Professional Education, Training, and Certification

### Awareness, Training, and Education
| Level | Meaning | Example |
| :--- | :--- | :--- |
| **Awareness** | Short messages that make everyone notice security and know what to do. | A warning reminder sent to all employees about a new SMS phishing campaign. |
| **Training** | Hands-on teaching of a specific skill for a specific job role. | A hands-on lab on restoring production Linux/Windows servers from immutable backups. |
| **Education** | Long-term academic learning that builds understanding and professional judgment. | A bachelor's or master's degree program in IT / Cybersecurity. |

- 💡 **Memory Aid:** Awareness tells you **that**, Training teaches you **how**, Education helps you understand **why**.
- **NIST SP 800-50 Rev. 1 (2024):** A learning program is a continuous four-step cycle:
  $$\text{Plan} \longrightarrow \text{Deliver} \longrightarrow \text{Measure Results} \longrightarrow \text{Improve}$$
  *(Crucial note: Completing a training module is never proof that user behavior has actually changed!)*
- **Self-Study and Ethical Practice:**
  - Practice strictly on systems you own or on authorized sandboxes: **OWASP Juice Shop**, **WebGoat**, or sanctioned **Capture The Flag (CTF)** competitions.
  - *Unauthorized testing is illegal even with good intentions.*
  - *Verbal permission is never legally sufficient*—always obtain explicit written authorization.

---

### Certifications Comparison
| Type | Focus / Meaning | Notable Examples |
| :--- | :--- | :--- |
| **Vendor-Neutral** | Universal principles and security concepts applicable across all platforms and products. | CompTIA Security+, ISC2 (CC, SSCP, CISSP), ISACA (CISA, CISM), GIAC. |
| **Vendor-Specific** | Operational skills tuned to a single manufacturer's proprietary technologies. | Fortinet NSE, Cisco (CCNA/CCNP), Microsoft Azure Security, AWS Certified Security. |

- **Choosing a Credential:**
  - Choose **vendor-neutral** to establish foundational competence or demonstrate broad conceptual mastery.
  - Choose **vendor-specific** when a job or infrastructure relies on that company's equipment.
- **Maintenance & CPEs:** Credentials require **Continuing Professional Education (CPE)** credits and annual maintenance fees to maintain active standing.
- **Associate of ISC2:** Candidates who pass exams like the CISSP but lack the required 5 years of verified professional experience earn the *Associate of ISC2* designation while accumulating experience.
- **Recommended Career Roadmap:**
  $$\text{Degree (BSIT)} \longrightarrow \text{Entry Vendor-Neutral (CC/Sec+)} \longrightarrow \text{Practitioner/Vendor (SSCP/NSE)} \longrightarrow \text{Advanced/Management (CISSP/CISM)}$$

---

### Cybersecurity Workforce Frameworks
- **DoD Manual 8140.03 (Feb 2023):** Formally replaced DoD 8570.01-M. It ties baseline qualification requirements directly to defined **work roles** in the DoD Cyber Workforce Framework rather than relying solely on certification exams.
- **NICE Workforce Framework (NIST SP 800-181):** Provides a universal common taxonomy and lexicon for cybersecurity work roles, tasks, knowledge, and skills. Used globally for job descriptions, talent development, and curriculum mapping.
- **Fortinet Micro-Credentials:** Follow the official Fortinet Training Institute syllabus. Course codes and titles change periodically; never share account credentials or exam dumps.

---

## ⚖️ 3. Ethics, Compliance, and FISMA

### Law versus Ethics
- **Law:** Formal statutes enacted by government bodies and enforced by judicial courts. Penalties: financial fines, injunctions, or imprisonment.
- **Ethics:** Guiding values, morals, and professional codes. Penalties: loss of professional credibility, expulsion from certification bodies, or employment termination.
- **Key Principle:** An action can be **legal but unethical** (e.g., browsing a celebrity's medical records without clinical reason if access control wasn't technically restricted). Professional codes hold members to higher standards than the law alone.

#### ISC2 Code of Ethics (Strict Priority Order)
When ethical duties conflict, the earlier canon **always takes precedence**:
1. **First Canon:** Protect society, the common good, and public trust.
2. **Second Canon:** Act honorably, honestly, justly, responsibly, and legally.
3. **Third Canon:** Provide diligent and competent service.
4. **Fourth Canon:** Advance and protect the profession.

#### Professional Practice Standards
- **Responsible Disclosure:** Immediately halt probing upon discovering a bug, refrain from collecting/exfiltrating data, and report findings privately to the system owner.
- **Conflict of Interest:** Promptly disclose any personal or financial conflicts and **recuse** yourself from decision-making.
- **Improper Instructions:** Explicitly refuse unethical orders (e.g., falsifying audit trails or hiding breaches from regulators) and escalate through proper whistleblowing/compliance channels.

---

### Regulatory Compliance Matrix
> **Remember:** *Compliance is not security.* Compliance is merely a minimum regulatory baseline. An organization can pass an audit and still suffer catastrophic breaches!

| Framework / Law | Who It Covers | What It Protects | Core Mandates & Mechanisms |
| :--- | :--- | :--- | :--- |
| **FISMA** | U.S. Federal Agencies & Contractors | Federal information & IT assets | Risk-based continuous monitoring using NIST RMF (SP 800-37) & controls (SP 800-53). |
| **HIPAA** | Health plans, healthcare clearinghouses, & healthcare providers | Protected Health Information (PHI) | Privacy Rule, Security Rule (Administrative, Physical, Technical Safeguards), and Breach Notification Rule. |
| **GLBA** | Financial institutions (banks, lenders, insurance) | Nonpublic Personal Information (NPI) | Privacy notices and a mandatory written Information Security Program (**GLBA Safeguards Rule**). |
| **SOX** | U.S. publicly traded corporations | Accuracy & integrity of financial records | Strict internal financial controls, auditor independence, and **Section 302** executive certification. |
| **FERPA** | Educational institutions receiving U.S. federal funds | Student education records & transcripts | Prevents disclosure of student records without prior signed, written consent. |
| **CIPA** | K-12 schools & public libraries utilizing E-Rate discounts | Minors accessing the internet | Mandatory Internet Safety Policy and technical content filtering against harmful material. |
| **PCI DSS** | Any entity storing, processing, or transmitting card data | Cardholder Data (CHD) & sensitive authentication data | Industry standard (not law), 12 core requirements, tokenization reduces audit scope. Current: **v4.0.1** (v3.2.1 retired Mar 2024). |

---

### FISMA (Federal Information Security Modernization Act)
- Enacted in 2002; comprehensively modernized in 2014.
- **Oversight Roles:**
  - **OMB (Office of Management and Budget):** Formulates overarching federal cybersecurity policy and receives annual reports.
  - **DHS / CISA:** Directs day-to-day operational defense and directives across civil agencies.
  - **NIST:** Authors mandatory standards and guidance (**FIPS 199/200**, **SP 800-37 RMF**, **SP 800-53** controls).
  - **Inspectors General (IG):** Conduct independent, objective annual evaluations of agency cybersecurity posture.
- **2015 OPM (Office of Personnel Management) Breach Case Study:** Over 21 million sensitive background records stolen.
  - **Key Lessons:**
    1. Maintain an exhaustive, real-time hardware/software inventory.
    2. Enforce strong multi-factor authentication (MFA/PIV).
    3. Patch critical vulnerabilities promptly across legacy architectures.

---

### Philippine Cyber Laws
- **RA 10173 – Data Privacy Act of 2012:**
  - **Three Core Pillars:** Transparency, Legitimate Purpose, Proportionality.
  - **Enforcement Body:** National Privacy Commission (**NPC**).
  - **Data Breach Notification:** Must report qualifying security incidents to the NPC and affected data subjects within **72 hours** of acquiring knowledge.
- **RA 10175 – Cybercrime Prevention Act of 2012:**
  - Defines and criminalizes offenses including illegal access (hacking), illegal interception, data interference, system interference, and cyber libel.

---

## 🔤 4. Must-Know Acronyms Reference

| Acronym | Complete Meaning | Category |
| :--- | :--- | :--- |
| **ACM / IEEE** | Association for Computing Machinery / Institute of Electrical and Electronics Engineers | Frameworks & Agencies |
| **AWS** | Amazon Web Services | Frameworks & Agencies |
| **BSIT** | Bachelor of Science in Information Technology | Frameworks & Agencies |
| **CC** | Certified in Cybersecurity (ISC2 entry-level) | Certifications & Orgs |
| **CCSP** | Certified Cloud Security Professional (ISC2) | Certifications & Orgs |
| **CEH** | Certified Ethical Hacker (EC-Council) | Certifications & Orgs |
| **CIPA** | Children's Internet Protection Act | Laws & Compliance |
| **CISA** | Certified Information Systems Auditor (ISACA) / Cybersecurity and Infrastructure Security Agency | Certifications & Orgs |
| **CISM** | Certified Information Security Manager (ISACA) | Certifications & Orgs |
| **CISSP** | Certified Information Systems Security Professional (ISC2) | Certifications & Orgs |
| **CompTIA** | Computing Technology Industry Association | Certifications & Orgs |
| **CPE** | Continuing Professional Education | Certifications & Orgs |
| **CSSLP** | Certified Secure Software Lifecycle Professional (ISC2) | Certifications & Orgs |
| **CTF** | Capture the Flag | Frameworks & Agencies |
| **DHS** | Department of Homeland Security | Frameworks & Agencies |
| **DoD** | Department of Defense | Frameworks & Agencies |
| **DoDM / DoDD** | DoD Manual / DoD Directive | Frameworks & Agencies |
| **EC-Council** | International Council of E-Commerce Consultants | Certifications & Orgs |
| **FERPA** | Family Educational Rights and Privacy Act | Laws & Compliance |
| **FISMA** | Federal Information Security Modernization Act | Laws & Compliance |
| **FTC** | Federal Trade Commission | Frameworks & Agencies |
| **GIAC** | Global Information Assurance Certification | Certifications & Orgs |
| **GLBA** | Gramm-Leach-Bliley Act | Laws & Compliance |
| **HIPAA** | Health Insurance Portability and Accountability Act | Laws & Compliance |
| **ISACA** | Information Systems Audit and Control Association | Certifications & Orgs |
| **ISC2** | International Information System Security Certification Consortium | Certifications & Orgs |
| **IT** | Information Technology | Frameworks & Agencies |
| **NCAE-C** | National Centers of Academic Excellence in Cybersecurity | Frameworks & Agencies |
| **NICE** | National Initiative for Cybersecurity Education (NICE Workforce Framework) | Frameworks & Agencies |
| **NIST** | National Institute of Standards and Technology | Frameworks & Agencies |
| **NPC** | National Privacy Commission (Philippines) | Frameworks & Agencies |
| **NPI** | Nonpublic Personal Information | Laws & Compliance |
| **NSA** | National Security Agency | Frameworks & Agencies |
| **NSE** | Network Security Expert (Fortinet program) | Certifications & Orgs |
| **OMB** | Office of Management and Budget | Frameworks & Agencies |
| **OPM** | Office of Personnel Management | Frameworks & Agencies |
| **OWASP** | Open Worldwide Application Security Project | Frameworks & Agencies |
| **PBA** | Performance-Based Assessment | Frameworks & Agencies |
| **PCAOB** | Public Company Accounting Oversight Board | Frameworks & Agencies |
| **PCI DSS** | Payment Card Industry Data Security Standard | Laws & Compliance |
| **PHI** | Protected Health Information | Laws & Compliance |
| **RA** | Republic Act (e.g., RA 10173, RA 10175) | Laws & Compliance |
| **RMF** | Risk Management Framework (NIST SP 800-37) | Frameworks & Agencies |
| **SANS** | SysAdmin, Audit, Network, and Security (Institute) | Certifications & Orgs |
| **SOX** | Sarbanes-Oxley Act | Laws & Compliance |
| **SP** | Special Publication (e.g., SP 800-50, SP 800-181, SP 800-53) | Frameworks & Agencies |
| **SSCP** | Systems Security Certified Practitioner (ISC2) | Certifications & Orgs |

---

## 🚀 5. GitHub Repository Setup

To push this repository to GitHub under your account:

```bash
# 1. Initialize git
git init -b main

# 2. Add remote repository
git remote add origin https://github.com/03DxD12/Finals-413---1st-Sem.git

# 3. Stage and commit
git add .
git commit -m "feat: Add comprehensive mobile-optimized IAS2 finals study guide and interactive reviewer"

# 4. Push to GitHub
git push -u origin main
```

### Enable GitHub Pages for Free Mobile Web Access:
1. Navigate to **Settings** > **Pages** in `https://github.com/03DxD12/Finals-413---1st-Sem`.
2. Under **Branch**, select `main` and root `/ (root)`.
3. Click **Save**. Within 1–2 minutes, your reviewer will be live at:  
   👉 **`https://03DxD12.github.io/Finals-413---1st-Sem/`**
