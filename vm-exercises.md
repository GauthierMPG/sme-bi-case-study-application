# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Identify the most profitable promotion for the brand "Orchid Oasis" in 2022.

#### Context

Orchid Oasis significantly increased their sales in 2022 at Retailer X by offering promotions to the consumers. "Promotions Management" is one of the 5 NRM pillars. To improve the Gross Profit of the brand it would be interesting to compare the promotions uplifts to the redemptions costs we received from Retailer X. Can you help us to identify which promotion mechanism is the most profitable one?

#### Steps to be executed by the student (max 6)

- Create a PivotChart, visualizing the absolute value sales of Orchid Oasis in 2022.
- Create a table to make a clear overview of the different elements of this comparison
- Add the promo and baseline sales to the table. For the latter one, you can take the average sales of the non-promo months.
- Calculate the uplift for the three promotions. Uplift = promo sales - baseline sales.
- Look up the redemption costs for each promotion in the tab "Promo Info".
- Define the most profitable promotion mechanism by calculating the Return Of Investment for each promotion. ROI = (uplift - cost) / cost

#### Exercise question:
Which promotion mechanism was the most profitable for Orchid Oasis in 2022 at Retailer X?:
- 1+1 free
- 2nd at 50% off
- 2+1 free

#### End goal:

![Conclusion](https://user-images.githubusercontent.com/132507679/236923059-6752d0bd-844a-45d0-aa88-aeef26525c3a.PNG)


## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`.

#### Explanation & Description
The learner will learn to use Excel to measure the performance of a brand using different KPI's. He/she will be able to use dynamic tools and visuals in Excel to better deep-dive into the data. Finally, it will be clear how the different NRM will help to grow the business and to generate more sales / profit.

#### End goal:

<img width="1115" alt="Slicers" src="https://user-images.githubusercontent.com/132507679/236928314-d4ff1d0e-36a7-4ac0-b663-85832c103078.png">


