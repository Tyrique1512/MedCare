# MedCare Campaign Performance Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Dataset Structure](#dataset-structure)
- [Insights Summary](#insights-summary)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Presentation Sample](#presentation-sample)

# Project Overview

## The goal of this project is to investigate the performance of marketing campaigns at MedCare in order to surface recommendations on marketing budget allocation across future campaign categories

Founded in 2016, MedCare is a U.S.-based medical insurance company serving thousands of customers. In 2019, they introduced marketing campaigns focused on wellness tips, affordability, and preventative care. Customers can choose from four plans—bronze, silver, gold, and platinum—offering varying premiums and coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of MedCare's brand across the country.

# Dataset Structure

The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img src="https://github.com/user-attachments/assets/0b9119c9-8e15-499a-97a0-193203728228" width="700">



# Insights Summary

## North Star Metrics

To evaluate campaign performance, the insights focused on the following key metrics:

•	**Signup Rate:** The percentage of people who see a campaign and subsequently sign up for a MedCare plan.

•	**Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.


•	**Click through Rate:** The percentage of people who see a campaign and click on the associated link.

## Marketing Insights

•	Despite achieving the highest number of impressions (1.3 million+), the Tailored Health Plans campaign category has the third lowest click-through rate (7%), which indicates a potential mismatch between the audience reached and the call-to-action. This could suggest that the campaign is attracting users outside the intended demographic or that the marketing content isn't effectively highlighting the unique value of the tailored plans

•	Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

•	The Healthy Living and Tailored Health Plans campaigns have nearly identical total impressions (1,372 million vs. 1,398 million) but show notable performance differences. Healthy Living achieves a higher CTR (10% vs. 7%) and a slightly lower CPC ($0.05 vs. $0.06). 

•	Across categories, Health for All and Benefit Updates performed around 3x better than the average CTR (9%) at 25% and 22%, respectively.

•	The Golden Years Security campaign has the lowest CTR at 1%, resulting in a disproportionately low number of clicks relative to its cost and an abnormally high CPC of $0.68. In contrast, the remaining campaigns are more efficiently budgeted, with CPCs ranging between $0.03 and $0.11.



# Recommendations


# Dashboard

The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/tyrique.klassen/viz/MedCareDashboard/CampaignCategoryDashboard?publish=yes). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![image](https://github.com/user-attachments/assets/1152d686-a7d2-4fa0-9ea7-171ea89d74a0)


# Presentation Sample
