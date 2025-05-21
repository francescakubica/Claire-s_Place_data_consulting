# Work Proudly Program & Claire's Place Foundation Impact Analysis

> **Team Members:** Francesca Kubica, Lee Stilwell, Leyna Nguyen, Theodora Heredia, Guadalupe Martinez, Jennifer Zhang  
> **Course:** BUAD 312 | Final Project  
> **Presentation Recording:** [Watch Here](https://youtu.be/3vSi_zE2wP)

## 📌 Project Overview

This project analyzes the **impact of recent policy changes** at *Claire’s Place Foundation*, focusing on three key areas:
- Patient grant distributions (EHSG)
- The Work Proudly Program (WPP)
- Donations and donor trends

The primary aim is to assess policy effectiveness, identify areas for improvement, and provide strategic recommendations using real organizational data.

---

## 📂 Datasets Analyzed

1. **Patients Dataset**  
   Analyzes grant frequency and amount before and after policy changes.
2. **Work Proudly Program Dataset**  
   Evaluates employment outcomes and demographic impacts.
3. **Donations Dataset**  
   Assesses donation behavior and retention trends across states and time.

---

## 📊 Key Findings

### 🧑‍⚕️ Patients Dataset (Extended Hospital Stay Grant)
- Grant rates **decreased** from 6.7 to 5.3 per month after the policy change.
- **No significant difference** in grant amounts awarded before vs. after the change (p = 0.684).
- California, Colorado, Hawaii, NJ, and MA had a significant influence on grants before the policy, but not after.
- **Recommendation:** Track `RequestedGrant` vs. `Amt_Granted` and prevent duplicate patient IDs.

### 💼 Work Proudly Program (WPP)
- Employment rates increased **30.1% overall** after the policy change:
  - **+51% for women**
  - **+8.3% for men**
  - **+41.7% for recipients of food stamps**
  - **+77.8% for those with SSI**
- Chi-square testing showed changes were **not statistically significant** but promising.
- **Recommendation:** Collect more granular employment data (e.g., education, income, desired job match).

### 💰 Donations Dataset
- Claire’s donation patterns mirror national nonprofit trends but with more volatility.
- **60% of donations** come from California, with **donor participation dropping** in recent years.
- **Recommendation:** Expand outreach beyond California and improve donor retention through personalized engagement and thank-you events.

---

## 📉 Limitations

- Only **6 months of post-policy data** available.
- Applicant IDs not unique across applications, creating duplication.
- Recurring donations counted multiple times due to failed statuses.
- Incomplete sector data for 2023 limits macro-trend comparisons.

---

## ✅ Recommendations Summary

| Area | Recommendation |
|------|----------------|
| **Patients** | Prevent double-counting by standardizing Applicant IDs |
| | Collect `RequestedGrant` and run follow-up surveys |
| **WPP** | Target outreach at food banks and large hospitals |
| | Collect job match and satisfaction survey data |
| **Donations** | Promote in all 50 states; focus on TX, FL, GA if needed |
| | Host thank-you events and send follow-up emails to donors |

---

## 📎 Files Included

- `Executive Summary.pdf` — 1-page high-level overview of the project  
- `Team 7.pdf` — Full final report presentation slides  
- `Appendix.pdf` — Technical models, visualizations, and statistical details

---

## 🙌 Acknowledgments

Special thanks to Claire’s Place Foundation and BUAD 312 faculty for the opportunity to work on a meaningful and data-driven impact evaluation project.

---

## 📫 Contact

If you have any questions or feedback about this project, feel free to reach out:

**Francesca Kubica**  
[GitHub Profile](https://github.com/francescakubica) | [LinkedIn](https://www.linkedin.com/in/francesca-kubica/)
