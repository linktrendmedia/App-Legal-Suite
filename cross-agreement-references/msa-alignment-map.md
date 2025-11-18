# MSA ALIGNMENT MAP — CROSS-AGREEMENT REFERENCES

**Version:** 1.0  
**Last Updated:** [Date]  
**Primary Agreement:** Master Service Agreement (MSA) v1.0

---

## PURPOSE

This document maps how the MSA aligns with other agreements in the App Legal Suite. It identifies shared clauses, dependencies, and cross-references to ensure consistency across the entire suite.

---

## 1. MSA ↔ SERVICE LEVEL AGREEMENT (SLA)

### Direct References in MSA

| MSA Section | Reference | SLA Section |
|-------------|-----------|-------------|
| 1.1(y) | Definition of "SLA" | Entire SLA |
| 1.1(aa) | Definition of "Support Services" | SLA Section 3 |
| 2.1 | Provision of Services governed by SLA | SLA Sections 2-5 |
| 2.3(b) | MSA prevails over SLA in hierarchy | N/A |
| Schedule 1, Section 8 | SLA key variables | SLA Sections 2, 3, 4 |

### Shared Clauses

- **Definitions:** Authorized Users, Client, Client Data, Services, Subscription Term
- **Security Obligations:** Must align with MSA Section 13
- **Security Incident Notification:** Must align with MSA Section 14
- **Data Protection:** Must reference DPA and MSA Section 12
- **Confidentiality:** Must align with MSA Section 11
- **Limitation of Liability:** Must align with MSA Section 18
- **Governing Law:** Must reference Schedule 1

### Dependencies

- SLA uptime commitments must be specified in MSA Schedule 1
- SLA support response times must be specified in MSA Schedule 1
- SLA maintenance windows must be specified in MSA Schedule 1
- Service Credits in SLA must reference MSA Fees

---

## 2. MSA ↔ DATA PROCESSING ADDENDUM (DPA)

### Direct References in MSA

| MSA Section | Reference | DPA Section |
|-------------|-----------|-------------|
| 1.1(p) | Definition of "DPA" | Entire DPA |
| 1.1(v) | Definition of "Processing" | DPA Section 1 |
| 10.4 | Subprocessors governed by DPA | DPA Section 7 |
| 12.2 | Data Processing governed by DPA | Entire DPA |
| 12.4 | Data Residency (cross-reference) | DPA Section 5 |

### Shared Clauses

- **Definitions:** Client Data, Processing, Security Incident, Applicable Law
- **Security Obligations:** DPA must align with MSA Section 13
- **Security Incident Notification:** DPA must align with MSA Section 14
- **Data Residency:** DPA must reference MSA Schedule 1
- **Subprocessors:** DPA must align with MSA Section 10.4
- **Confidentiality:** DPA must align with MSA Section 11
- **Governing Law:** DPA must reference MSA Schedule 1

### Dependencies

- DPA must incorporate all data protection laws listed in MSA Section 12.1
- DPA data residency requirements must match MSA Schedule 1
- DPA subprocessor notice period must match MSA Section 10.4(b) (30 days)
- DPA must reference MSA liability cap in Schedule 1

---

## 3. MSA ↔ ACCEPTABLE USE POLICY (AUP)

### Direct References in MSA

| MSA Section | Reference | AUP Section |
|-------------|-----------|-------------|
| 3.1(a) | Authorized Users must comply with AUP | Entire AUP |
| 3.5 | Client must comply with AUP | Entire AUP |
| 4.2(d) | Prohibited activities reference AUP | AUP Section 2 |
| 4.4(d) | API usage restrictions reference AUP | AUP Section 3 |
| 17.2(c) | Client indemnity for AUP violations | Entire AUP |
| 19.1(c) | Suspension for AUP violations | Entire AUP |

### Shared Clauses

- **Definitions:** Services, Authorized Users, Client Data
- **Prohibited Activities:** AUP must align with MSA Section 4.2
- **API Usage:** AUP must align with MSA Section 4.4

### Dependencies

- AUP prohibited activities must be consistent with MSA Section 4.2
- AUP must reference MSA suspension rights (Section 19)
- AUP must reference MSA termination rights (Section 20)

---

## 4. MSA ↔ END USER LICENSE AGREEMENT (EULA)

### Relationship

The EULA governs end-user software licenses, while the MSA governs enterprise SaaS subscriptions. These are separate agreements for different contexts.

### Shared Clauses (for consistency)

- **Definitions:** Services, Intellectual Property Rights, Documentation
- **Usage Restrictions:** EULA Section 3 should align with MSA Section 4.2
- **Confidentiality:** EULA confidentiality should align with MSA Section 11
- **Limitation of Liability:** EULA liability cap should align with MSA Section 18
- **Export Controls:** EULA must align with MSA Section 25
- **Anti-Corruption:** EULA must align with MSA Section 26
- **Governing Law:** EULA should use same jurisdiction as MSA

---

## 5. MSA ↔ B2C TERMS OF SERVICE

### Relationship

B2C ToS governs consumer-facing services, while the MSA governs enterprise B2B relationships. These are separate agreements for different contexts.

### Shared Clauses (for consistency)

- **Definitions:** Services, API, Beta Features, Data
- **Data Protection:** B2C ToS must reference Privacy Policy and align with MSA Section 12.1 (data protection laws)
- **Security:** B2C ToS security standards should align with MSA Section 13
- **Limitation of Liability:** B2C ToS must include consumer protection carve-outs (MSA Section 18.4)
- **Export Controls:** B2C ToS must align with MSA Section 25

---

## 6. MSA ↔ PRIVACY POLICIES

### Direct References in MSA

| MSA Section | Reference | Privacy Policy Section |
|-------------|-----------|------------------------|
| 12.1 | Data protection laws | Privacy Policy Section 2 |
| 12.2 | DPA governs Processing | Privacy Policy Section 4 |
| 14.1 | Security Incident notification | Privacy Policy Section 6 |

### Shared Clauses

- **Definitions:** Data, Processing, Security Incident
- **Data Protection Laws:** Privacy Policies must list same laws as MSA Section 12.1
- **Security Incident Notification:** Privacy Policies must align with MSA Section 14
- **Data Residency:** Privacy Policies must reference MSA Schedule 1 (for enterprise customers)

---

## 7. MSA ↔ COOKIE POLICIES

### Relationship

Cookie Policies govern website cookie usage and are referenced in Privacy Policies. Minimal direct connection to MSA.

### Shared Elements

- **Data Protection Laws:** Cookie Policies must comply with same laws as MSA Section 12.1
- **Consent Mechanisms:** Cookie Policies must align with GDPR/UK GDPR standards referenced in MSA

---

## 8. MSA ↔ WEBSITE TERMS OF USE

### Relationship

Website Terms govern website usage, while MSA governs SaaS subscriptions. Separate agreements for different contexts.

### Shared Clauses (for consistency)

- **Definitions:** Services, Intellectual Property Rights
- **Limitation of Liability:** Website Terms liability should align with MSA Section 18
- **Governing Law:** Website Terms should use same jurisdiction as MSA
- **Export Controls:** Website Terms should align with MSA Section 25

---

## CRITICAL HARMONIZATION REQUIREMENTS

### Definitions (Must Be Identical)

1. **Affiliate** — MSA, DPA, SLA, EULA
2. **Applicable Law** — All agreements
3. **Client Data** — MSA, SLA, DPA (use "Customer Data" for B2C)
4. **Confidential Information** — MSA, SLA, DPA, EULA
5. **Force Majeure Event** — MSA, SLA
6. **Intellectual Property Rights** — All agreements
7. **Processing** — MSA, DPA, Privacy Policies
8. **Security Incident** — MSA, SLA, DPA, Privacy Policies
9. **Services** — All agreements

### Clause Templates (Must Align)

1. **Data Protection Compliance** (Section 12.1) — MSA, SLA, DPA, B2C ToS, Privacy Policies
2. **Security Obligations** (Section 13) — MSA, SLA, DPA
3. **Security Incident Notification** (Section 14) — MSA, SLA, DPA, Privacy Policies
4. **Limitation of Liability** (Section 18) — MSA, SLA, EULA, B2C ToS (with consumer carve-outs)
5. **Export Controls** (Section 25) — MSA, SLA, EULA, B2C ToS
6. **Anti-Corruption** (Section 26) — MSA, SLA, EULA
7. **Governing Law** (Section 22) — MSA, SLA, DPA, EULA (same jurisdiction)

### Schedule 1 Variables (Must Be Consistent)

1. **Governing Law / Jurisdiction** — Must be same across MSA, SLA, DPA, EULA
2. **Data Residency** — Must be same across MSA, DPA
3. **Liability Cap** — Must be same across MSA, SLA
4. **Subprocessor Notice Period** — Must be same across MSA (30 days), DPA (30 days)
5. **Transition Period** — Must be same across MSA (90 days), SLA (90 days)

---

**END OF MSA ALIGNMENT MAP**

