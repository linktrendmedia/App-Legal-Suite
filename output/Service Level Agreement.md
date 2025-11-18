# SERVICE LEVEL AGREEMENT

**Effective Date:** [As specified in Schedule 1]

---

## SECTION 1 — DEFINITIONS AND INTERPRETATION

### 1.1 Definitions

**(a) "Affiliate"**  
Has the meaning given in the MSA.

**(b) "API"**  
Means the application programming interfaces provided by the Company to enable programmatic access to the Services.

**(c) "Available" or "Availability"**  
Means the Services are accessible and operational for production use.

**(d) "Business Day"**  
Has the meaning given in the MSA.

**(e) "Client"**  
Means the business customer receiving Services pursuant to the MSA.

**(f) "Client Data"**  
Has the meaning given in the MSA.

**(g) "Company"**  
Means the entity identified in Schedule 1 as the provider of the Services.

**(h) "Confidential Information"**  
Has the meaning given in the MSA.

**(i) "Downtime"**  
Means any period during which the Services are unavailable, excluding Permitted Downtime.

**(j) "DPA"**  
Means the Data Processing Addendum incorporated into the MSA.

**(k) "Emergency Maintenance"**  
Means urgent maintenance required to prevent or mitigate security or operational risks.

**(l) "Excluded Events"**  
Means events outside the Company's control, including:

- **(i)** Client network, systems, or infrastructure failures;
- **(ii)** third-party service or provider outages;
- **(iii)** internet backbone issues;
- **(iv)** Force Majeure Events;
- **(v)** breaches by the Client;
- **(vi)** denial-of-service attacks not caused by Company negligence;
- **(vii)** Beta Features;
- **(viii)** Client misuse, including use of Services for AI/ML training in violation of the MSA.

**(m) "Force Majeure Event"**  
Has the meaning given in the MSA.

**(n) "Incident"**  
Means any event that causes or may cause disruption to the Services.

**(o) "MSA"**  
Means the Master Service Agreement governing the relationship between the parties.

**(p) "Order Form"**  
Means the document specifying subscription details and incorporating this SLA.

**(q) "Permitted Downtime"**  
Includes:

- **(i)** Scheduled Maintenance;
- **(ii)** Emergency Maintenance;
- **(iii)** downtime caused by Excluded Events.

**(r) "Recovery Point Objective (RPO)"**  
Means the maximum acceptable period of data loss measured in time.

**(s) "Recovery Time Objective (RTO)"**  
Means the maximum acceptable duration to restore Services after an Incident.

**(t) "Resolution Time"**  
Means the time between acknowledgment of an Incident and issue resolution or workaround.

**(u) "Response Time"**  
Means the time between a Client-submitted support ticket and Company acknowledgment.

**(v) "Root Cause Analysis (RCA)"**  
Means a detailed postmortem report identifying the cause of an Incident and remediation steps.

**(w) "Scheduled Maintenance"**  
Means maintenance announced at least forty-eight (48) hours in advance.

**(x) "Security Incident"**  
Has the meaning given in the MSA.

**(y) "Service Credits"**  
Means credits issued for failure to meet the Uptime Commitment or other SLA guarantees.

**(z) "Services"**  
Means the software-as-a-service platform, APIs, and related functionalities provided by the Company.

**(aa) "Severity Levels"**  
Means the classification of support requests according to business impact.

**(ab) "SLA" or "Service Level Agreement"**  
Means this agreement governing uptime, performance, support levels, maintenance, and service credits.

**(ac) "Status Page"**  
Means the publicly accessible webpage displaying real-time Service availability and Incident status.

**(ad) "Support Services"**  
Means the support obligations described in this SLA, including response and resolution targets.

**(ae) "Uptime Commitment"**  
Means the percentage of time during a calendar month that the Services are required to be Available, as defined in Schedule 1.

### 1.2 Interpretation

**(a)** Headings are for convenience only and do not affect interpretation.

**(b)** Singular includes plural and vice versa.

**(c)** "Including" means "including without limitation."

**(d)** References to laws include amendments, replacements, and successor legislation.

**(e)** Schedule 1 controls for configurable variables.

**(f)** In case of translation discrepancies, the English version prevails.

**(g)** References to "writing" or "written" include email.

**(h)** In the event of any conflict between this SLA and the MSA, the MSA shall prevail except with respect to specific service level commitments set forth in this SLA.

---

## SECTION 2 — UPTIME COMMITMENT

### 2.1 Platform Uptime Guarantee

The Company shall provide an Uptime Commitment for the Services as defined in Schedule 1, expressed as a percentage of total minutes in each calendar month during which the Services must be Available.

### 2.2 API Uptime Guarantee

**(a)** The Company shall provide a separate API Uptime Commitment of 99.9% monthly availability for API endpoints.

**(b)** API Downtime is measured separately from platform Downtime and is subject to separate Service Credits as specified in Schedule 1.

**(c)** API rate limits and throttling do not constitute API Downtime.

### 2.3 Measurement Period

Uptime is calculated monthly, based on:

**(a)** total minutes in the month;

**(b)** minus Permitted Downtime;

**(c)** minus Downtime.

### 2.4 Monitoring

**(a)** The Company shall use industry-standard monitoring tools to measure Availability from multiple geographic locations.

**(b)** Monitoring shall include automated health checks, synthetic transactions, and real-time alerting.

### 2.5 Status Page

**(a)** The Company shall maintain a publicly accessible Status Page displaying real-time Service availability, Incident status, and Scheduled Maintenance windows.

**(b)** The Status Page shall be updated within fifteen (15) minutes of detecting a Severity 1 or Severity 2 Incident.

**(c)** The Status Page URL shall be provided in Schedule 1.

---

## SECTION 3 — SCHEDULED AND EMERGENCY MAINTENANCE

### 3.1 Scheduled Maintenance

**(a)** The Company may schedule maintenance with at least forty-eight (48) hours' advance written notice to the Client.

**(b)** Scheduled Maintenance is considered Permitted Downtime.

**(c)** Scheduled Maintenance windows shall not exceed the limits defined in Schedule 1.

**(d)** Scheduled Maintenance shall be conducted during the maintenance window specified in Schedule 1 (e.g., Sundays 2:00 AM - 6:00 AM UTC).

### 3.2 Emergency Maintenance

**(a)** Emergency Maintenance may occur without prior notice when necessary for security, stability, or safety.

**(b)** Emergency Maintenance counts as Permitted Downtime if it is required to mitigate substantial risk.

**(c)** The Company shall notify the Client of Emergency Maintenance as soon as reasonably practicable.

---

## SECTION 4 — SERVICE PERFORMANCE REQUIREMENTS

### 4.1 General Performance

The Services shall be provided using commercially reasonable efforts, consistent with industry standards for enterprise SaaS platforms.

### 4.2 API Latency Targets

**(a)** API response times (measured at the Company's edge servers) shall meet the targets specified in Schedule 1.

**(b)** Typical target: 95th percentile API response time ≤ 500ms for standard API calls.

**(c)** Latency targets exclude network transit time between the Client and the Company's infrastructure.

### 4.3 Performance Monitoring

The Company shall monitor Service performance metrics and provide performance reports upon request.

---

## SECTION 5 — DATA BACKUP AND RECOVERY

### 5.1 Backup Frequency

**(a)** The Company shall perform automated backups of Client Data at least once every twenty-four (24) hours.

**(b)** Backups shall be stored in geographically redundant locations.

### 5.2 Recovery Point Objective (RPO)

The maximum acceptable data loss period is twenty-four (24) hours.

### 5.3 Recovery Time Objective (RTO)

**(a)** In the event of a catastrophic failure, the Company shall use commercially reasonable efforts to restore Services within four (4) hours.

**(b)** RTO does not apply to Excluded Events.

### 5.4 Backup Retention

Backups shall be retained for a minimum of thirty (30) days unless otherwise specified in Schedule 1.

### 5.5 Client-Initiated Restore Requests

**(a)** The Client may request restoration of Client Data from backups by submitting a support ticket.

**(b)** The Company shall initiate the restore process within four (4) Business Hours of receiving the request.

**(c)** Additional fees may apply for restore requests as specified in Schedule 1.

---

## SECTION 6 — SUPPORT SERVICES

### 6.1 Support Channels

Support is provided through the following channels:

**(a)** email;

**(b)** helpdesk/ticketing system;

**(c)** optional live chat (if purchased);

**(d)** telephone support (if specified in Schedule 1).

### 6.2 Support Hours

**(a)** **Standard Support:** Monday–Friday, during business hours defined in Schedule 1, excluding public holidays.

**(b)** **Premium Support (24/7):** Available as a paid add-on tier, providing around-the-clock support every day of the year.

### 6.3 Premium Support Features

If the Client purchases Premium Support, the following additional features apply:

**(a)** 24/7/365 support coverage;

**(b)** priority response times (as specified in Schedule 1);

**(c)** dedicated Technical Account Manager (TAM) for enterprise clients;

**(d)** quarterly business reviews;

**(e)** proactive monitoring and alerting.

---

## SECTION 7 — INCIDENT CLASSIFICATION AND RESPONSE TIMES

### 7.1 Severity Levels

Incidents shall be classified by Severity Level:

**(a) Severity 1 — Critical**  
Complete outage or major functionality failure affecting all or substantially all Authorized Users, or Security Incident requiring immediate attention.

**(b) Severity 2 — High**  
Significant degradation or partial outage affecting a substantial portion of Authorized Users or critical functionality.

**(c) Severity 3 — Medium**  
Non-critical functionality impaired; workaround available; limited impact on business operations.

**(d) Severity 4 — Low**  
Minor issues, UI defects, cosmetic issues, or general inquiries with no material impact on operations.

### 7.2 Response Targets

**(a)** The Company shall adhere to Response Times defined in Schedule 1.

**(b)** **Standard Support Response Times (example):**

- Severity 1: 1 hour
- Severity 2: 4 hours
- Severity 3: 1 Business Day
- Severity 4: 3 Business Days

**(c)** **Premium Support Response Times (example):**

- Severity 1: 30 minutes
- Severity 2: 2 hours
- Severity 3: 4 hours
- Severity 4: 1 Business Day

### 7.3 Resolution Targets

**(a)** Resolution Times or workaround targets are defined in Schedule 1.

**(b)** The Company shall use commercially reasonable efforts to meet Resolution Targets but does not guarantee resolution within a specific timeframe.

### 7.4 Severity Classification Disputes

**(a)** The Company reserves the right to reclassify Incidents based on actual business impact.

**(b)** If the Client disputes the classification, the parties shall work in good faith to agree on the appropriate Severity Level.

---

## SECTION 8 — ESCALATION PROCEDURES

### 8.1 Escalation Path

If an Incident remains unresolved within the designated Resolution Time, the Company shall escalate to:

**(a)** Tier 2 Support;

**(b)** Engineering team;

**(c)** Management-level engineering leads (for Severity 1 Incidents).

### 8.2 Client Responsibilities

The Client must provide requested logs, screenshots, diagnostic information, and reasonable access to personnel promptly to facilitate resolution.

### 8.3 Executive Escalation

For Severity 1 Incidents that remain unresolved for more than four (4) hours, the Client may request executive escalation by contacting the escalation contact specified in Schedule 1.

---

## SECTION 9 — INCIDENT POSTMORTEM AND ROOT CAUSE ANALYSIS

### 9.1 RCA Requirement

For Severity 1 Incidents, the Company shall provide a written Root Cause Analysis (RCA) to the Client within ten (10) Business Days of Incident resolution.

### 9.2 RCA Contents

The RCA shall include:

**(a)** description of the Incident;

**(b)** root cause identification;

**(c)** timeline of events;

**(d)** impact assessment;

**(e)** remediation steps taken;

**(f)** preventive measures to avoid recurrence.

### 9.3 RCA for Severity 2 Incidents

RCAs for Severity 2 Incidents shall be provided upon request.

---

## SECTION 10 — SECURITY INCIDENT NOTIFICATION

### 10.1 Notification Timeline

**(a)** The Company shall notify the Client of any Security Incident within seventy-two (72) hours of becoming aware of the Security Incident, in accordance with MSA Section 14.1.

**(b)** Notification shall include the information specified in MSA Section 14.1(b).

### 10.2 Security Incident Response

The Company shall cooperate with the Client in accordance with MSA Section 14.2 and the DPA.

---

## SECTION 11 — SERVICE REQUESTS AND CHANGE REQUESTS

### 11.1 Service Requests

Non-incident requests such as configuration assistance, training, or information requests shall be handled within business hours and are not subject to Incident Response Times.

### 11.2 Change Requests

**(a)** Changes requiring engineering work, custom development, or significant configuration may be classified as Professional Services under the MSA.

**(b)** Change Requests shall be billed in accordance with the MSA.

---

## SECTION 12 — SERVICE AVAILABILITY EXCLUSIONS (EXCLUDED EVENTS)

The following events do not count as Downtime for purposes of calculating Availability:

**(a)** Client network, systems, or infrastructure failures;

**(b)** third-party service or provider outages (including cloud infrastructure providers, CDN providers, DNS providers);

**(c)** Force Majeure Events as defined in the MSA;

**(d)** Client misuse, unauthorized changes, or violations of the MSA or Acceptable Use Policy;

**(e)** issues arising from unsupported browsers, devices, or configurations;

**(f)** Beta Features or experimental functionality;

**(g)** Scheduled Maintenance and Emergency Maintenance within defined limits;

**(h)** denial-of-service attacks, distributed denial-of-service attacks, or other malicious attacks not caused by Company negligence;

**(i)** Client's failure to implement recommended updates, patches, or security measures;

**(j)** use of Services for AI/ML training in violation of MSA Section 4.2(g).

---

## SECTION 13 — COMMUNICATION OF INCIDENTS

### 13.1 Notifications

**(a)** The Company shall notify the Client of Severity 1 or Severity 2 Incidents without undue delay.

**(b)** Notifications shall be sent via email to the contacts specified in Schedule 1 and posted to the Status Page.

### 13.2 Status Updates

**(a)** The Company shall provide periodic updates for Severity 1 Incidents at least every two (2) hours until resolved.

**(b)** The Company shall provide periodic updates for Severity 2 Incidents at least every four (4) hours until resolved.

### 13.3 Incident Resolution Notice

Upon resolution of a Severity 1 or Severity 2 Incident, the Company shall notify the Client and update the Status Page.

---

## SECTION 14 — SERVICE CREDIT FRAMEWORK

### 14.1 Eligibility for Service Credits

Service Credits apply when:

**(a)** monthly Availability falls below the Uptime Commitment defined in Schedule 1; or

**(b)** API Availability falls below 99.9% monthly; or

**(c)** RTO or RPO commitments are not met.

### 14.2 Credit Calculation — Platform Uptime

Credits are calculated using the following formula:

**Service Credit = Monthly Subscription Fee × Credit Percentage**

Credit Percentage tiers (customizable in Schedule 1):

**(a)** Availability ≥ 99.9% — No credit

**(b)** 99.0% – 99.89% — 10% credit

**(c)** 98.0% – 98.99% — 25% credit

**(d)** < 98.0% — 50% credit

### 14.3 Credit Calculation — API Uptime

**(a)** API Availability ≥ 99.9% — No credit

**(b)** 99.0% – 99.89% — 5% credit

**(c)** 98.0% – 98.99% — 15% credit

**(d)** < 98.0% — 25% credit

### 14.4 Credit Calculation — RTO/RPO Failures

If the Company fails to meet RTO or RPO commitments due to a non-Excluded Event, the Client shall receive a 10% credit for that month.

### 14.5 Credit Limit

Service Credits for a single month shall not exceed 100% of that month's Subscription Fees.

### 14.6 Application of Credits

**(a)** Credits are applied to future invoices only and cannot be redeemed as cash.

**(b)** Credits have no cash value and may not be transferred or assigned.

---

## SECTION 15 — CREDIT CLAIM PROCESS

### 15.1 Automatic Credits

**(a)** For Availability below 98.0% in any calendar month, Service Credits shall be automatically calculated and applied to the next invoice without requiring a claim.

**(b)** The Company shall notify the Client of automatic credits via email.

### 15.2 Manual Claims

**(a)** For Availability between 98.0% and 99.89%, the Client may submit a claim for Service Credits.

**(b)** The Client must submit a claim:

- **(i)** within thirty (30) days after the month in which the failure occurred;
- **(ii)** including timestamps, logs, or evidence;
- **(iii)** via the support channel defined in Schedule 1.

### 15.3 Review

The Company shall review and validate claims within thirty (30) days.

### 15.4 Approval

If approved, Service Credits will be applied to the next billing cycle.

### 15.5 Denial

Credits may be denied if:

**(a)** data is insufficient to verify the claim;

**(b)** the event was an Excluded Event;

**(c)** the Client is delinquent on payments;

**(d)** misuse or violation of the MSA or SLA contributed to the issue.

---

## SECTION 16 — MEASUREMENT AND REPORTING

### 16.1 Measurement Tools

**(a)** Availability is measured using Company-operated monitoring systems.

**(b)** The Company may use third-party monitoring services to provide independent verification.

### 16.2 Transparency Reports

Upon request, the Company shall provide:

**(a)** monthly uptime reports;

**(b)** maintenance schedules and logs;

**(c)** Incident summaries.

### 16.3 Disputes

**(a)** If measurement results are disputed, the Company's system of record shall prevail unless demonstrably incorrect.

**(b)** The Client may request access to monitoring logs to verify Availability calculations.

---

## SECTION 17 — CHRONIC FAILURE

### 17.1 Definition

"Chronic Failure" occurs when:

**(a)** Availability falls below the Uptime Commitment for three (3) consecutive months; OR

**(b)** Availability falls below 99.0% in any single month.

### 17.2 Remedies

If Chronic Failure occurs, the Client may:

**(a)** request a Root Cause Analysis (RCA);

**(b)** request a written remediation plan with specific timelines;

**(c)** terminate the Agreement without penalty upon thirty (30) days' written notice.

### 17.3 Remediation Plan

The Company shall deliver the remediation plan within fifteen (15) Business Days of the Client's request.

---

## SECTION 18 — EXCLUSIONS FROM SERVICE CREDITS

Service Credits shall not be granted for failures caused by:

**(a)** Excluded Events as defined in Section 12;

**(b)** Client-side incidents, including Client network, systems, or infrastructure failures;

**(c)** denial-of-service attacks or other malicious attacks not caused by Company negligence;

**(d)** issues resulting from unsupported third-party integrations;

**(e)** Beta Features or experimental features;

**(f)** features not described in Documentation;

**(g)** Force Majeure Events;

**(h)** failures caused by the Client's breach of the MSA or SLA.

---

## SECTION 19 — ACCESSIBILITY COMPLIANCE

### 19.1 Commitment

The Company shall use commercially reasonable efforts to ensure the Services conform to Web Content Accessibility Guidelines (WCAG) 2.1 Level AA standards.

### 19.2 Accessibility Reports

Upon request, the Company shall provide the Client with the most recent accessibility audit report or Voluntary Product Accessibility Template (VPAT).

### 19.3 Remediation

If the Client identifies accessibility issues, the Company shall use commercially reasonable efforts to remediate such issues in accordance with its standard product roadmap.

---

## SECTION 20 — ENFORCEMENT

### 20.1 Sole Remedy

Service Credits constitute the Client's sole and exclusive remedy for failure to meet the Uptime Commitment, API Uptime Commitment, RTO, or RPO, except as provided in Section 17.2 (Chronic Failure termination rights).

### 20.2 No Other Damages

The Client shall not claim additional damages for uptime-related issues except as expressly permitted in the MSA.

---

## SECTION 21 — TERMINATION RIGHTS RELATED TO SLA

### 21.1 Termination for Chronic Failure

The Client may terminate the Agreement under Section 17.2 without penalty.

### 21.2 No Early Termination Fees

Termination for Chronic Failure shall incur no early termination fees.

### 21.3 Transition Assistance

**(a)** The Company shall provide data export assistance consistent with MSA Section 21.

**(b)** The transition period shall be ninety (90) days, in accordance with MSA Section 21.1.

---

## SECTION 22 — DATA PROTECTION AND CONFIDENTIALITY

### 22.1 Data Protection

The parties shall comply with all data protection obligations set forth in MSA Section 12 and the DPA.

### 22.2 Confidentiality

All information exchanged in connection with this SLA, including Incident details, RCAs, and performance reports, shall be treated as Confidential Information under MSA Section 11.

---

## SECTION 23 — LIMITATION OF LIABILITY

The limitations of liability set forth in MSA Section 18 apply to this SLA, except that Service Credits issued under this SLA shall not count toward the liability cap.

---

## SECTION 24 — GOVERNING LAW AND JURISDICTION

This SLA shall be governed by the same laws and jurisdiction as specified in the MSA Schedule 1.

---

## SECTION 25 — AMENDMENT AND MODIFICATION

**(a)** The Company may modify this SLA upon ninety (90) days' advance written notice to the Client, consistent with MSA Section 2.4.

**(b)** Material changes that adversely affect the Client's rights may trigger termination rights under MSA Section 2.4(d).

---

## SECTION 26 — SEVERABILITY

If any provision of this SLA is held to be invalid, illegal, or unenforceable, such provision shall be modified to the minimum extent necessary to make it valid and enforceable, or if such modification is not possible, such provision shall be severed. The remaining provisions shall continue in full force and effect.

---

## SECTION 27 — ENTIRE AGREEMENT

This SLA, together with the MSA, Order Forms, and all incorporated documents, constitutes the entire agreement between the parties with respect to service levels.

---

## SECTION 28 — EFFECTIVE DATE

This SLA is effective as of the Effective Date specified in Schedule 1 and remains in effect for the duration of the MSA.

---

**END OF SERVICE LEVEL AGREEMENT**

---

**SIGNATURE PAGE FOLLOWS**

