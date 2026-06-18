# Capstone Part 2: RFM Customer Segmentation & Retention Strategy

This repository contains **Part 2** of the D2C Customer Churn Intelligence & Retention API project. In this phase, we calculate Recency, Frequency, and Monetary (RFM) metrics from raw orders, combine them with support and return behaviors, define 8 customer segments, and present retention strategy rules.

## Repository Contents

*   `rfm_segmentation.ipynb`: Jupyter notebook showing data loading, order cleaning (outlier treatment), manual RFM computation, and segment visualizations.
*   `segments.csv`: Generated output file containing `customer_id`, `segment_name`, and aggregated features.
*   `retention_strategy.md`: Strategy report detailing segment behaviors, recommended interventions, expected value, and budget prioritization hierarchy.
*   `manual_review_cases.md`: Case studies of 10 complex customers where decisions are not straightforward, with customized action plans.
*   `requirements.txt`: Python package requirements.
*   `images/`: Pre-generated segment size and churn rate plots.

## Segment Definitions & Churn Statistics

1.  **Champions** (Active, high spend, recent): **4.9% Churn** (102 customers)
2.  **Loyal Customers** (Active, moderate spend): **16.5% Churn** (358 customers)
3.  **New Customers** (Signed up recently, 1 order): **15.2% Churn** (112 customers)
4.  **High-Value Unhappy** (High spend, low satisfaction/tickets): **19.7% Churn** (213 customers)
5.  **Discount-Sensitive** (High discount percentage): **37.5% Churn** (352 customers)
6.  **At-Risk** (High past spend, moderate recency): **45.4% Churn** (315 customers)
7.  **Dormant** (High recency, inactive): **89.3% Churn** (656 customers)
8.  **About to Churn / Low Value** (Default low-value, mod recency): **49.0% Churn** (292 customers)

## Installation & Setup

1.  Make sure you have Python 3.11+ installed.
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Code

To run the RFM segmentation notebook:
```bash
jupyter notebook rfm_segmentation.ipynb
```
The notebook will run the preprocessing, write the output table to `segments.csv`, and display visual summaries of the segments.
