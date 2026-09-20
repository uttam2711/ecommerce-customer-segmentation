**E-Commerce Customer Segmentation**

Groups ~93,000 real e-commerce customers into 4 segments based on how recently, how often, and how much they buy (RFM analysis), using K-Means clustering.

**Dataset:** https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
<img width="1105" height="640" alt="image" src="https://github.com/user-attachments/assets/3bfc0455-1037-4734-b51d-ead2c01456f0" />

**Segment	Meaning**
Loyal Repeat Customers --	Buy often, spend well
Recent Big Spenders    -- Just bought, spent a lot
Lapsed / At-Risk       -- Haven't bought in a long time
New / Low-Value	       -- Recent but small purchase

Key finding

Silhouette Score technically favored just 2 clusters, but that only split "**repeat buyers**" vs "**everyone else**" — too simple to act on. Choose **4 clusters instead since they're genuinely useful for targeted marketing**, even with a lower score.

**Tools**

Python (Pandas, Scikit-Learn, Seaborn), Power BI, Excel (Pivot Tables, VLOOKUP, Macros)

**Files**

**Segmentation.ipynb** — full analysis
**customer_segments.csv** — customers with RFM scores + segment
**customer_segmentation_dashboard.pbix** — Power BI dashboard
**customer_segmentation_analysis.xlsm** — Excel analysis
