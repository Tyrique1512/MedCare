# MedCare Campaign Performance Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Dataset Structure](#dataset-structure)
- [Insights Summary](#insights-summary)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Presentation Sample](#presentation-sample)

# Project Overview

## The goal of this project is to investigate the performance of marketing campaigns at MedCare to surface recommendations on marketing budget allocation across future campaign categories

Founded in 2016, MedCare is a U.S.-based medical insurance company serving thousands of customers. In 2019, they introduced marketing campaigns focused on wellness tips, affordability, and preventative care. Customers can choose from four plans—bronze, silver, gold, and platinum—offering varying premiums and coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of MedCare's brand across the country.

# Dataset Structure

The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img src="https://github.com/user-attachments/assets/0b9119c9-8e15-499a-97a0-193203728228" width="700">



# Insights Summary

## North Star Metrics

To evaluate campaign performance, the insights focused on the following key metrics:

•	**Impressions:** The number of people who saw a marketing campaign.

•	**Cost per Click (CPC):** the amount an advertiser pays each time a user clicks on their advertisement

•	**Signup Rate:** The percentage of people who see a campaign and subsequently sign up for a MedCare plan.

•	**Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.

•	**Click through Rate (CTR):** The percentage of people who see a campaign and click on the associated link.

## Marketing Insights

•	Despite achieving the highest number of impressions (1.3 million+), the Tailored Health Plans campaign category has the third lowest click-through rate (7%), which indicates a potential mismatch between the audience reached and the call-to-action.

•	Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

•	The Healthy Living and Tailored Health Plans campaigns have nearly identical total impressions (1,372 million vs. 1,398 million) but show notable performance differences. Healthy Living achieves a higher CTR (10% vs. 7%) and a slightly lower CPC ($0.05 vs. $0.06). 

•	Across categories, Health for All and Benefit Updates performed around 3x better than the average CTR (9%) at 25% and 22%, respectively.

•	The Golden Years Security campaign has the lowest CTR at 1%, resulting in a disproportionately low number of clicks relative to its cost and an abnormally high CPC of $0.68. In contrast, the remaining campaigns are more efficiently budgeted, with CPCs ranging between $0.03 and $0.11.

## Signup Insights

•	In 2020, all campaign categories experienced a significant rise in signups due to increased demand for healthcare products during the pandemic. While the pandemic initially boosted signups, most categories experienced a decline from mid-2022 onwards, with recent signups falling below pre-pandemic levels. However, the #Coverage Matters and #HealthyLiving categories have shown resilience, collectively accounting for approximately 47% of recent signups. Some COVID-based campaigns also had abnormally high CACs at $1.2-$2.2K

•	Health For All campaign category had the strongest performance, achieving 3,5k signups and a signup rate of 2%, approximately 12x higher than the overall average. This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%)

• Golden Years Security has the lowest signup count (23) and the lowest signup rate (0,18%) despite having the highest cost per signup ($177).

•	Despite its strong click-through rate, the Benefit Updates campaign category had the second lowest signups (45) and signup rate (0.02%), along with the second highest cost per signup at $48.

•	Notably, the #HealthyLiving category had the highest number of signups but a relatively low signup rate of 0.3%.

•	Within the two campaign categories with the highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.


## Claims Insights

•	Claim counts and amounts rose at the pandemic's onset alongside increased signups and have remained steady across most campaign categories, except for the Compare Health Coverage campaign. This campaign steadily increased throughout 2021 - 2022, peaking at a record-high of $173K in July 2022 before significantly decreasing in the following months due to a decrease in claim counts.

•	Customers for the Compare Health Coverage campaign had the most expensive claims on average ($410) and the highest total claim amount ($3.9M).  

•	The average claim amount for this campaign category was ~50% higher than the $267 average, which raises concerns about its cost-effectiveness and sustainability. 


# Recommendations

**•	Golden Years Security:** Consider discontinuing or overhauling this campaign due to its low click-through rate (1%) and high cost per signup ($177). Reallocate its budget to the Health For All Campaign, which has a stronger click-through rate (25%) and signup rate (2%). 

**•	Family Coverage Plan:** Investigate the lack of clicks despite high impressions, as there are likely issues with the campaign or missing data.

**• Compare Health Coverage:** Collaborate with the actuarial team to analyze this campaign category's demographics and health needs to ensure the campaign isn’t attracting higher-risk profiles than planned.

**Health Awareness:** Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.

**COVID Campaigns:** Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $3,70. Consider removing these campaigns altogether.

# Dashboard

The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/tyrique.klassen/viz/MedCareDashboard/CampaignCategoryDashboard?publish=yes). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![image](https://github.com/user-attachments/assets/d13b432a-ad25-4d7e-9821-6b76f2b60d96)



# Presentation Sample
