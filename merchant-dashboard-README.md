# Merchant Performance Dashboard

## Overview

A comprehensive merchant analytics dashboard tracking the health and growth of a large-scale fintech payments platform. Designed to give business and sales leadership a single source of truth across acquisition, engagement, retention, device adoption, and revenue.

> All metrics shown are fictional and created for portfolio purposes. Dashboard structure and KPI framework are inspired by real-world fintech merchant analytics.

---

## Dashboard Sections & KPIs

### 1. Core Metrics
| KPI | Description |
|---|---|
| Total Transactions | Count of successful payment transactions in the period |
| Gross Merchandise Value (GMV) | Total value of transactions processed (₹) |
| Active Merchants | Merchants with at least 1 transaction in the month |

### 2. Acquisition
| KPI | Description |
|---|---|
| New Onboardings (New OB) | Total new merchants registered in the period |
| New OB Active | New merchants who completed at least 1 transaction |
| DIY Channel | Self-onboarded merchants via app/web |
| SO Channel | Merchants onboarded via Sales Officers in the field |

> Activation rate = New OB Active / New OB. Benchmark: 45–55%

### 3. Retention & Engagement
| KPI | Description |
|---|---|
| Churn (M-1 Txn) | Merchants active last month with 0 transactions this month |
| Winback | Previously churned merchants who transacted again |
| Repeat | Merchants transacting for 2+ consecutive months |
| Revisits | Merchants returning after 1+ months of inactivity |
| Super Engaged | Merchants transacting 20+ days in the month |
| Engaged | Merchants transacting 6–19 days in the month |
| Super Engaged 6+ users | Super engaged merchants with 6+ unique payment users |

> Engagement funnel: Churn → Winback → Repeat → Engaged → Super Engaged

### 4. Device — Soundbox
| KPI | Description |
|---|---|
| SB Merchants | Merchants with an active Soundbox device |
| Non-SB Merchants | Merchants transacting without Soundbox |
| New SB Deployments | New Soundbox devices deployed in the period |

> SB merchants show 2.4x higher retention vs Non-SB in sample data

### 5. Revenue
| KPI | Description |
|---|---|
| UPI CC Revenue | Revenue from UPI Credit Card transactions (MDR share) |
| Settle Now Active | Merchants using the instant settlement feature |
| Settle Now Revenue | Revenue earned from Settle Now fees |
| Subscription Revenue | Revenue from device/platform subscription plans |

---

## Key Insights (Sample Data)

- **Acquisition**: SO channel drives 62% of new onboardings but DIY shows faster growth — signals product-led growth opportunity
- **Engagement**: Super Engaged 6+ users growing fastest (+22% MoM) — high LTV cohort to prioritise in retention
- **Retention**: Winback growing at +12% MoM — targeted re-engagement campaigns showing strong ROI
- **Revenue**: Subscription is largest stream; Settle Now growing fastest at +11% MoM
- **Device**: SB penetration at 39% — significant headroom for expansion

---

## Tools Used
- Superset / Looker — dashboard visualisation
- SQL (Hive / Trino) — data extraction and transformation
- Easy Reports — automated data pipelines and scheduled reporting
- JIRA / Confluence — requirements and documentation

---

## Skills Demonstrated
- KPI framework design for a 48M+ merchant ecosystem
- Business storytelling through metrics
- Executive dashboarding for national sales leadership
- Cross-functional collaboration: product, data engineering, field sales

---

## Author
**Ananya Jain** — Business Analyst | Fintech & Analytics  
📎 [LinkedIn](your-linkedin-url) | 📧 ananyajain2606@gmail.com
