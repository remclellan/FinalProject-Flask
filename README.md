# Improving Healthcare Outcomes

Across america there are challenges in access to care when people need it. We have faced many attempt to address the issue as we carry one of the highest spends on healthcare ($3.6T in 2018)), including landmark legislation in 2010 with the Affordable Care Act. Recent events have brough a significant spotlight to this issue as people try to find care during the current crisis and face navigation challenges even in large cities that we thought were better equipped.

As we delved into our analysis we found key metrics that told a broader story when we looked at county level data over multiple years. While many elements are related to income disparity and disproportionately impact lower income and more rural areas, we also found education, minority status and certain lifestyle behaviors affected this as well.

Armed with this knowledge we set about to find a way to connect a potential solution to access to care. As Community Health Centers have been a highlighted resource through the country during this crisis, they are not yet available in all areas though they have been expanding over the past several years. Taking our knowledge of those Community Health Centers and where they are today, we aimed to predict the type of Center delivery model that may work best in additional a county near you. 

---
### Healthcare Viz Architects Team:
Raquel McLellan, Steven J Bark, Eliana Suarez, Solicia Xu and Jessica Carns

---
### Analysis Objectives:
* Identify important factors that drive health outcomes
* Determine the best community health center type and setting based on county health factors
 
---
### Machine Learning Models:
* Use Random Forest Regression model to target critical health factors
* Use KNN model to cluster health center type and location to top health factors
---
### About this repo:
This repo houses our flask application and visual elements.  

We welcome you to check our data munging and working repository as well at [DataAnalytics-FinalProject](https://github.com/stevenjbark/DataAnalytics-FinalProject)

For those who are interested in more visualizations on this topic, we also recommend visiting our team member Tableau dashboards:
* [Outcomes 2015 - 2020: States with Lowest Premature Deaths](https://public.tableau.com/views/HealthCareOutcomesfrom2015to2020/PrematureDeaths?:display_count=y&:origin=viz_share_link)
* [Healthcare Factors and Demographics by State](https://public.tableau.com/views/HealthCareFactorsandDemographicsbyState/Maps?:display_count=y&:origin=viz_share_link)
* [PCP vs Other Primary Care by State](https://public.tableau.com/shared/8B3G73MCS?:display_count=y&:origin=viz_share_link)
* [Percent Fair/Poor Health compared to PCP and Other Primary Delivery](https://public.tableau.com/views/PercentFairPoorHealthPCPNumbersandOtherPrimaryCareMapbyStates/PercentFairPoorHealthPCPandOtherPrimaryCareMapbyStates?:display_count=y&:origin=viz_share_link)
* [Uninsured Population by Median Household Income](https://public.tableau.com/views/UninsuredPopulationbyMHIovertheYears/UninsuredPopulationbyMHIovertheYears?:display_count=y&:origin=viz_share_link)
*[Deaths Dashboard](https://public.tableau.com/views/DeathsReviewDashboard/DeathsReviewsDatshboard?:display_count=y&:origin=viz_share_link)

---
### Data Sources:
* [County Health Rankings](https://www.countyhealthrankings.org/app/Texas/2020/downloads)
* [Health Resources & Services Administration](https://data.hrsa.gov/tools/data-explorer)