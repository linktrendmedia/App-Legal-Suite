# SERVICE LEVEL AGREEMENT — SCHEDULE 1 (SPECIFIC PROVISIONS)

This Schedule forms an integral part of the Service Level Agreement (SLA). Capitalized terms have the meanings assigned in the SLA or MSA.

---

## 1. EFFECTIVE DATE

### 1.1 Effective Date

This SLA is effective as of:  
[INSERT DATE]  
(Must match MSA Effective Date)

---

## 2. UPTIME COMMITMENTS

### 2.1 Platform Uptime Commitment

The Company commits to the following monthly Uptime:  
[INSERT PERCENTAGE]

**Recommended:** 99.9% monthly uptime

### 2.2 API Uptime Commitment

The Company commits to the following monthly API Uptime:  
**99.9%** (fixed standard)

---

## 3. API LATENCY TARGETS

### 3.1 API Response Time

95th percentile API response time (measured at Company edge servers):  
[INSERT TARGET]

**Recommended:** ≤ 500ms for standard API calls

### 3.2 Exclusions

Latency targets exclude network transit time between Client and Company infrastructure.

---

## 4. DATA BACKUP AND RECOVERY

### 4.1 Backup Frequency

**Daily automated backups** (every 24 hours)

### 4.2 Recovery Point Objective (RPO)

**24 hours** (maximum acceptable data loss period)

### 4.3 Recovery Time Objective (RTO)

**4 hours** (target restoration time for catastrophic failures)

### 4.4 Backup Retention Period

[INSERT PERIOD]

**Recommended:** 30 days minimum

### 4.5 Client-Initiated Restore Fees

[INSERT FEE STRUCTURE]

**Options:**
- Free for first restore per year; USD $[X] per subsequent restore
- USD $[X] per restore request
- Included in Premium Support tier

---

## 5. SCHEDULED MAINTENANCE WINDOWS

### 5.1 Maintenance Window

**Day/Time:** [INSERT SCHEDULE]

**Recommended:** Sundays 2:00 AM - 6:00 AM UTC

### 5.2 Maximum Scheduled Maintenance per Month

[INSERT HOURS]

**Recommended:** 4 hours per month

---

## 6. SUPPORT TIERS AND HOURS

### 6.1 Standard Support

**Hours:** [INSERT HOURS]

**Recommended:** Monday–Friday, 9:00 AM – 5:00 PM [INSERT TIMEZONE], excluding public holidays in [INSERT JURISDICTION]

### 6.2 Premium Support (24/7)

**Availability:** Available as paid add-on

**Hours:** 24/7/365 (every day, all year)

**Additional Features:**
- Priority response times
- Dedicated Technical Account Manager (TAM) for enterprise clients
- Quarterly business reviews
- Proactive monitoring

**Fee:** [INSERT ANNUAL FEE]

---

## 7. SUPPORT RESPONSE TIMES

### 7.1 Standard Support Response Times

| Severity Level | Response Time Target |
|----------------|---------------------|
| Severity 1 (Critical) | [INSERT TIME] (e.g., 1 hour) |
| Severity 2 (High) | [INSERT TIME] (e.g., 4 hours) |
| Severity 3 (Medium) | [INSERT TIME] (e.g., 1 Business Day) |
| Severity 4 (Low) | [INSERT TIME] (e.g., 3 Business Days) |

### 7.2 Premium Support Response Times

| Severity Level | Response Time Target |
|----------------|---------------------|
| Severity 1 (Critical) | [INSERT TIME] (e.g., 30 minutes) |
| Severity 2 (High) | [INSERT TIME] (e.g., 2 hours) |
| Severity 3 (Medium) | [INSERT TIME] (e.g., 4 hours) |
| Severity 4 (Low) | [INSERT TIME] (e.g., 1 Business Day) |

---

## 8. SUPPORT RESOLUTION TARGETS

### 8.1 Resolution Time Targets (Best Effort)

| Severity Level | Resolution Target |
|----------------|------------------|
| Severity 1 (Critical) | [INSERT TIME] (e.g., 4 hours) |
| Severity 2 (High) | [INSERT TIME] (e.g., 8 hours) |
| Severity 3 (Medium) | [INSERT TIME] (e.g., 3 Business Days) |
| Severity 4 (Low) | [INSERT TIME] (e.g., 10 Business Days) |

**Note:** Resolution targets are best-effort commitments and are not guaranteed.

---

## 9. SERVICE CREDIT TIERS

### 9.1 Platform Uptime Service Credits

| Monthly Availability | Service Credit |
|---------------------|---------------|
| ≥ 99.9% | 0% (No credit) |
| 99.0% – 99.89% | 10% of Monthly Subscription Fee |
| 98.0% – 98.99% | 25% of Monthly Subscription Fee |
| < 98.0% | 50% of Monthly Subscription Fee |

### 9.2 API Uptime Service Credits

| Monthly API Availability | Service Credit |
|-------------------------|---------------|
| ≥ 99.9% | 0% (No credit) |
| 99.0% – 99.89% | 5% of Monthly Subscription Fee |
| 98.0% – 98.99% | 15% of Monthly Subscription Fee |
| < 98.0% | 25% of Monthly Subscription Fee |

### 9.3 RTO/RPO Failure Credits

**10% of Monthly Subscription Fee** if RTO or RPO commitments are not met due to a non-Excluded Event.

### 9.4 Maximum Monthly Credit

**100% of Monthly Subscription Fee**

---

## 10. STATUS PAGE

### 10.1 Status Page URL

[INSERT URL]

**Example:** https://status.company.com

### 10.2 Update Frequency

The Status Page shall be updated within **15 minutes** of detecting a Severity 1 or Severity 2 Incident.

---

## 11. INCIDENT NOTIFICATION CONTACTS

### 11.1 Client Notification Contacts

**Primary Contact Email:** [INSERT EMAIL]  
**Secondary Contact Email:** [INSERT EMAIL]  
**SMS/Phone (Optional):** [INSERT NUMBER]

### 11.2 Executive Escalation Contact (Company)

**Name:** [INSERT NAME]  
**Title:** [INSERT TITLE]  
**Email:** [INSERT EMAIL]  
**Phone:** [INSERT NUMBER]

---

## 12. SUPPORT CHANNELS

### 12.1 Available Support Channels

**(a)** Email: [INSERT SUPPORT EMAIL]  
**(b)** Helpdesk/Ticketing System: [INSERT URL]  
**(c)** Live Chat: [Available / Not Available]  
**(d)** Telephone Support: [INSERT NUMBER] (if applicable)

---

## 13. ROOT CAUSE ANALYSIS (RCA) DELIVERY

### 13.1 RCA Timeline

**Severity 1 Incidents:** RCA delivered within **10 Business Days** of Incident resolution.

**Severity 2 Incidents:** RCA available upon request.

---

## 14. CHRONIC FAILURE THRESHOLD

### 14.1 Single-Month Threshold

Availability below **99.0%** in any single month constitutes Chronic Failure.

### 14.2 Consecutive-Month Threshold

Availability below the Uptime Commitment for **three (3) consecutive months** constitutes Chronic Failure.

---

## 15. BUSINESS DAY DEFINITION

### 15.1 Business Days

For purposes of this SLA, "Business Day" means any day other than Saturday, Sunday, or a public holiday in:

[INSERT JURISDICTION]

**Recommended:** State of Nevada, United States

---

## 16. GOVERNING LAW AND JURISDICTION

### 16.1 Reference to MSA

This SLA is governed by the same laws and jurisdiction as specified in MSA Schedule 1, Section 2.

---

## 17. THIRD-PARTY MONITORING (OPTIONAL)

### 17.1 Independent Monitoring

The Company may use third-party monitoring services such as:

[INSERT SERVICE NAME]

**Examples:** Pingdom, StatusCake, Datadog, New Relic

---

## 18. ACCESSIBILITY COMPLIANCE

### 18.1 Standard

The Company commits to conformance with:

**WCAG 2.1 Level AA**

### 18.2 VPAT Availability

VPAT available upon request: [INSERT EMAIL OR URL]

---

**END OF SCHEDULE 1**

