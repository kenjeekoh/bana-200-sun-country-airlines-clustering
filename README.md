K-Means Clustering for Sun Country Airlines Customers

___________________
OVERVIEW

This project leverages the K-Means clustering algorithm to analyze customer reservation data for Sun Country Airlines. By identifying distinct customer segments, we provide actionable insights to enhance marketing strategies and improve customer experience.

___________________
OBJECTIVE

To identify customer segments based on booking behavior, demographics, and travel preferences, and to recommend tailored marketing strategies to better serve these segments and maximize revenue potential.

___________________
KEY FINDINGS

Using K-Means clustering, we identified five distinct customer segments:

1. Spontaneous Direct Flyers in Summer: Last-minute bookers who prefer direct flights in Q3.
2. Non-Member Seasonal Group Travelers: Group travelers with seasonal preferences.
3. Non-Member Middle-Aged Leisure Travelers: Over-35 travelers relying on non-digital booking channels.
4. Ufly Early-Bird Direct Flyers: Loyal Ufly members booking flights well in advance.
5. Non-Member Business Travelers: Solo business travelers with stopovers and last-minute bookings.

___________________
RECOMMENDATIONS

Tailored Packages for Business and Solo Travelers:
Provide single-person hotel deals, ride-hailing credits, and tier upgrades for business travelers.
Partner with MSP hotels and Fortune 500 companies for exclusive perks.

Invest in Non-Digital Marketing Channels:
Engage older and group travelers via mailbox fliers, vouchers, and airport booths.

Seasonal Marketing Campaigns:
Promote summer destinations (e.g., Las Vegas, Fort Myers) for Clusters 0 and 4.
Target winter/spring travelers (Clusters 1, 2, 3) with campaigns for Miami and Seattle.

Expand Ufly Loyalty Programs:
Introduce referral and appreciation programs.
Offer tier-based perks for early bookings and premium add-ons.

___________________
DATASET

The dataset contains detailed customer booking data, including:

Passenger demographics
Booking channels
Travel behavior (e.g., trip length, layovers)
Loyalty program membership (Ufly)

___________________
METHODOLOGY

Data Preparation:
Scaled continuous variables and transformed categorical/Boolean variables into numerical formats.

Clustering Approach:
Determined the optimal number of clusters (5) using the elbow method.
Ran the K-Means algorithm multiple times for stable results.

Customer Segmentation:
Identified distinct segment characteristics using demographic, behavioral, and booking data.

___________________
TOOLS AND TECHNOLOGIES

1. Programming: Python (Pandas, NumPy, Scikit-learn)
2. Data Visualization: Matplotlib, Seaborn, Tableau
3. Clustering: K-Means Algorithm

___________________
LIMITATIONS

The analysis is based on 2013-2014 data, which may not reflect current customer behavior.
Feedback and satisfaction data were not included in the clustering process.

___________________
FUTURE CONSIDERATIONS
Re-cluster customers regularly with updated data to reflect evolving preferences.
Incorporate post-flight surveys and satisfaction data to enhance segmentation insights.

___________________
TEAM

Kenjee Koh
Becky Wang
Vy Nguyen
Dennis Wu
Hsiang-Han (Cyan) Huang
