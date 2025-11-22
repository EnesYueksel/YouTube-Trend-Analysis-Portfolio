# Case Study: YouTube Trend Analysis & Actionable Insights for Media Strategy
This project analyzes the German YouTube trending landscape to provide data-driven answers to key strategic questions for a media agency. The final result is an interactive dashboard designed to support decisions on budget allocation, content strategy, and influencer partnerships.

[View the Interactive Looker Studio Dashboard Here] https://lookerstudio.google.com/s/kxPc6AOwwP0

![Youtube_Analysis](https://github.com/user-attachments/assets/4d5ad307-3c83-44f1-b983-2eb4473da623)

---

A media agency needs to invest its clients' marketing budgets efficiently. This analysis was designed to move beyond simple vanity metrics and answer three core business questions:

1.  **Where to Play?** Which content categories offer the highest reach and engagement?
2.  **Who to Partner With?** Which channels are the most valuable and consistent performers?
3.  **How to Win?** What are the measurable characteristics of a successful, viral video?

---

## 2. Key Findings & Actionable Recommendations

The analysis of the dataset yielded the following clear, data-driven recommendations.

### Finding 1: Content placement is key. "Entertainment" and "Music" dominate the market.
The data shows that these two categories are responsible for the vast majority of total views. While niche categories like "Gaming" have a dedicated audience, their overall reach is significantly smaller.

 **Recommendation:** For large-scale brand awareness campaigns, focus the budget on "Entertainment" and "Music". Use niche categories for highly targeted, lower-budget initiatives.
 ![image.png](attachment:9d2bf844-d2d5-433b-a371-c059c14e1e28:image.png)

---

### Finding 2: The "Friday Effect" is real. The publishing day directly impacts performance.
Videos published on a **Friday** achieve the highest average viewership, likely due to increased audience availability leading into the weekend.

**Recommendation:** Schedule the launch of high-priority content for Fridays to maximize organic reach and initial impact. This is a zero-cost strategy to boost performance.
![image.png](attachment:22c708d7-2ca2-4bce-bf43-3f9a78843988:image.png)

---

### Finding 3: Influence is multi-dimensional. We must look beyond total views.
My "Channel Portfolio Analysis" shows that there are different types of successful channels:
*   **High-Quality "Superstars":** Channels with extremely high average views per video.
*   **High-Quantity "Workhorses":** Channels that consistently produce a large volume of trending videos.

> **Recommendation:** Diversify the influencer strategy. Partner with "Superstars" for high-impact brand campaigns. Collaborate with "Workhorses" for consistent, long-term affiliate marketing and community engagement. The dashboard allows for filtering and identifying the top players in each category.
![image.png](attachment:830bebad-c612-4352-9fdd-2f820023ba52:image.png)


---


## 3. Project Workflow & Technical Skills

To achieve these insights, a complete end-to-end data pipeline was developed:

1.  **Data Cleaning & ETL (Python):** The raw data was heavily processed to handle inconsistencies. A denormalized Master View was then created in PostgreSQL to serve as an optimized, single source of truth.
2.  **Dashboarding & Visualization (Looker Studio):** An interactive, multi-page dashboard was built to present the findings in a clear and actionable format, featuring drill-down capabilities for deep-dive analysis.
3.  **Predictive Modeling PoC (Python & Scikit-learn):** As an extension, a proof-of-concept machine learning model was developed to forecast a video's viral potential, demonstrating an understanding of advanced analytical techniques.

*   **Tech Stack:** `Python (Pandas)`, `SQL (PostgreSQL)`, `Looker Studio`, `Jupyter Notebook`

The full project files, including the data preparation scripts, are available in this repository.
