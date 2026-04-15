# LuckyMobile | Telco Customer Churn Analysis

![Excel](https://img.shields.io/badge/Excel-Advanced-green?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview

LuckyMobile is a telecom customer churn analysis project covering **7,043 customers** across multiple service categories, contract types, and demographic segments. The project identifies the key drivers of churn through a structured breakdown of 20+ variables, segments customers by churn risk profile, and delivers actionable retention recommendations for each high-risk group.

**Overall churn rate: 26.54%** (1,869 out of 7,043 customers)

---

## Dataset

- **Total customers:** 7,043
- **Churn:** 1,869 (26.54%) | Retained: 5,174 (73.46%)
- **Features:** Gender, Senior Citizen, Partner, Dependents, Tenure, Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies, Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges

---

## Methodology

Churn rates were calculated and compared across every available dimension — demographics, services, contract terms, and payment methods — to identify which variables correlate most strongly with customer loss.

Customers were further segmented into **tenure groups** (6 months, 12 months, 18 months, 18+ months) and **service usage profiles** (Tech Use vs. No Tech Use) to enable targeted retention strategy design.

---

## Key Findings

### Demographics
| Variable | Churn Rate | Note |
|----------|-----------|------|
| Female | 26.92% | Slightly higher than male |
| Male | 26.16% | |
| Senior Citizen | **41.68%** | Significantly higher risk |
| Non-Senior | 23.61% | |
| No Partner | **32.96%** | Higher churn |
| Has Partner | 19.66% | |
| No Dependents | **31.28%** | |
| Has Dependents | 15.45% | |

### Tenure
| Tenure Group | Churn Rate |
|-------------|-----------|
| 6 Months | **52.94%** |
| 12 Months | 35.89% |
| 18 Months | 32.30% |
| 18+ Months | 15.20% |

Early-tenure customers churn at more than 3x the rate of long-term customers — onboarding and early engagement are critical.

### Internet Service
| Service Type | Churn Rate |
|-------------|-----------|
| Fiber optic | **41.89%** |
| DSL | 18.96% |
| No internet | 7.40% |

Fiber optic customers churn at more than double the DSL rate — likely due to pricing or competition.

### Contract Type
| Contract | Churn Rate |
|---------|-----------|
| Month-to-month | **42.71%** |
| One year | 11.27% |
| Two year | 2.83% |

Contract length is one of the strongest predictors of churn.

### Payment Method
| Payment Method | Churn Rate |
|--------------|-----------|
| Electronic check | **45.29%** |
| Mailed check | 19.11% |
| Bank transfer (automatic) | 16.71% |
| Credit card (automatic) | 15.24% |

Electronic check users churn at 3x the rate of automatic payment users.

### Value-Added Services
| Service | No → Churn | Yes → Churn |
|---------|-----------|------------|
| Online Security | 41.77% | **14.61%** |
| Tech Support | 41.64% | **15.17%** |
| Device Protection | 39.13% | **22.50%** |
| Online Backup | 39.93% | **21.53%** |

Customers without tech/security services churn at nearly 3x the rate of those with them.

### Paperless Billing
| Paperless Billing | Churn Rate |
|-----------------|-----------|
| Yes | 33.57% |
| No | 16.33% |

---

## Customer Segments

Customers were segmented into 4 profile groups based on service usage and tech adoption patterns, enabling differentiated retention campaigns per segment.

---

## Business Recommendations

| Risk Factor | Action |
|-------------|--------|
| Month-to-month contracts | Offer loyalty discounts for annual/biannual upgrades |
| Electronic check payment | Incentivise switch to automatic payment (discount or bonus data) |
| Fiber optic high churn | Review pricing competitiveness; improve service quality perception |
| No online security / tech support | Bundle these as free trial add-ons for new customers |
| 0–6 month tenure | Strengthen onboarding programme; assign dedicated support contact |
| Senior citizens | Simplified plans, dedicated support line, family bundling options |

---

## Files

| File | Description |
|------|-------------|
| `LuckyMobile` | Full churn analysis: raw data, segmentation, churn breakdown by all variables |



---

## Tools

- **Excel:** Pivot tables, churn rate calculations, segmentation matrices, conditional formatting
