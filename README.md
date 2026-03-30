# coupon-campaign-analysis
Analysis of a coupon campaign to evaluate incremental spend and ROI

1. Objective
  The goal of this project is to evaluate the impact of a coupon campaign on customer spending and determine whether the campaign generated positive return on investment (ROI)

2. Data
   The dataset includes:
   - User-level transaction data
   - Customer segmentation into Control and Test groups
   - Identification of coupon redeemers within the T est group

3. Methodology
   The analysis was conducted in the following steps:
   1. Customer Segmentation:
      -Users were divided into Control and Test groups
      -Test group was further split into Redeemers and Non-Redeemers
   2. Spend Analysis:
      -Weekly spending trends were analyzed
      -Average spend per user was calculated for both groups
   3. Incremental Analysis:
      -Incremental spend per user was calculated as: Test average spend - Control average spend
      -Uplift percentage was computed
      -Total incremental revenue was estimated, based on the Test group size
   4. ROI Calculation:
      -Revenue = Incremental spend x Take Rate (10%)
      -Cost Coupon value x Number of redeemers
      -ROI = (Revenue - Cost) / Cost

4. Results
   -Spend per User (Control): 34.24 USD
   -Spend per User (Test): 45.13 USD
   -Incremental Spend per User: 10.89 USD
   -Uplift: 31.8%
   -Total Incremental Revenue: 450,409 USD
   -ROI: -59%

5. Key Insights
   -The coupon campaign significantly increased customer spending (+32%)
   -However, the cost of the campaign exceeded the generated revenue
   -Despite higher engagement, the campaign was not profitable

6. Conclusion
   While the campaign successfully increased customer spend, it resulted in a negative ROI. This suggest that the campaign strategy needs optimization, such as adjusting coupon value or improving targeting.
