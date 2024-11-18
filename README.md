# Term Deposit Subscription Campaign: Client Segmentation and Strategy

This project focuses on leveraging data-driven insights to enhance term deposit subscription rates for a bank. By analyzing customer patterns and segmenting clients into high, moderate, and low potential groups, we develop tailored strategies to optimize marketing efforts and achieve significant growth in subscription rates.

## **Objective**

The project aims to increase the term deposit subscription rate from **11.68% to 20–25%** within **12–18 months** by:
- Identifying and segmenting clients based on demographic, economic, and behavioral factors.
- Developing tailored campaign strategies for each client segment.
- Implementing data-driven decisions for effective resource allocation.

---

## **Dataset Overview**

The dataset includes information about clients' demographic, economic, and engagement patterns during past campaigns.  
Key features include:
- **Demographics:** `age`, `job`, `marital`, `education`.
- **Economic factors:** `default`, `balance`, `housing`, `loan`.
- **Past campaign data:** `contact`, `duration`, `poutcome`, `campaign`.
- **Temporal factors:** `day`, `month`.

[(https://archive.ics.uci.edu/dataset/222/bank+marketing)](#)

---

## **Exploratory Data Analysis (EDA)**

Key findings from EDA:
- **Contact Method:** Cellular and telephone communications yield higher conversion rates.
- **Timing:** Campaigns performed better at the beginning of the month and during March, September, October, and December.
- **Engagement:** Longer interaction durations significantly increase success rates.
- **Past Successes:** Outcomes from previous successful campaigns provide valuable insights for strategy refinement.

---

## **Segmentation Model**

Clients were segmented into three categories:
1. **High-Potential Clients:** Likely to convert with minimal effort.
2. **Moderate-Potential Clients:** Require nurturing and trust-building.
3. **Low-Potential Clients:** Need awareness-focused campaigns.

The segmentation was based on:
- Demographic patterns (e.g., education, job).
- Economic stability (e.g., balance, loan status).
- Past engagement and temporal factors.

---

## **Campaign Strategy**

### **Objective:**
To achieve a 20–25% subscription rate by targeting each segment with specific strategies:

- **High-Potential Clients (1,407 clients):**
  - Focus: Maximize quick conversions.
  - Strategies: Personalized consultations, exclusive benefits (e.g., higher interest rates).
  - Goal: 70–75% conversion (~1,000 clients).

- **Moderate-Potential Clients (318 clients):**
  - Focus: Nurture and engage.
  - Strategies: Flexible deposit terms, financial education webinars.
  - Goal: 50–60% conversion (~150 clients).

- **Low-Potential Clients:**
  - Focus: Build awareness and trust.
  - Strategies: Financial literacy campaigns using low-cost channels.
  - Goal: Incremental growth (~2–3%).

---

## **Implementation Timeline**

1. **Phase 1 (Months 1–6):**
   - Focus on high-potential clients with early-bird offers.
   - Engage moderate-potential clients through digital campaigns.

2. **Phase 2 (Months 7–12):**
   - Re-engage high-potential holdouts with additional perks.
   - Expand moderate-client webinars and flexible offers.

3. **Phase 3 (Months 13–18):**
   - Retain existing depositors via loyalty programs.
   - Continue education campaigns for low-potential clients.

---

## **Results & Expected Outcomes**

- **6 Months:** Subscription rate increases to 15%.
- **12 Months:** Reaches 20%.
- **18 Months:** Achieves the 25% target.
  
---
