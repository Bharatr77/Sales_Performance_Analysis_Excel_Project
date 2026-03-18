# FMCG Warehouse: Optimizing Amazon's Distribution Efficiency
Project Overview

This project is a deep-dive data analysis aimed at improving the operational efficiency of Amazon's FMCG warehouse network. In the fast-paced FMCG sector, delays and stockouts lead to significant revenue loss. This project identifies root causes of supply chain bottlenecks and provides data-driven recommendations to minimize operational costs and ensure timely delivery.

 Business Problem

Amazon is experiencing inefficiencies in its warehouse operations, leading to:

Frequent stockouts and delivery delays.

Increased operational costs.

Supply chain disruptions affecting customer satisfaction.

Goal: Analyze warehouse data to uncover inefficiencies and propose actionable solutions to optimize performance.

 Tech Stack & Methodology

Tool: Microsoft Excel (Advanced Analytics)

Data Cleaning: Handled missing values (Mean/Median imputation for wh_est_year) and type conversion for categorical variables.

Analysis: Pivot Tables for regional performance, correlation analysis between warehouse age and breakdown frequency, and capacity utilization checks.

Visualization: Interactive Excel Dashboard with slicers for Zone, Location Type, and Warehouse Capacity.

 Key Objectives & KPIs
Warehouse Utilization: Analyzing product_wg_ton against WH_capacity_size.

Operational Health: Monitoring wh_breakdown_l3m and storage_issue_reported_l3m to identify aging infrastructure.

Logistics Efficiency: Evaluating transport_issue_l1y based on dist_from_hub.

Competitor Mapping: Understanding the impact of Competitor_in_mkt on refill requests.

 Actionable Insights

Infrastructure: Warehouses with "No" temp_reg_mach (Temperature Regulation) showed a higher rate of storage issues in the food category.

Location: Rural warehouses face 15% more transport issues compared to Urban centers due to dist_from_hub constraints.

Refill Pattern: High correlation found between num_refill_req_l3m and retail_shop_num.


