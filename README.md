# Lead-Scoring-Assignment-MLOps

## Problem statement
- CodePro is an EdTech startup that had a phenomenal seed A funding round. It used the money to increase its brand awareness. As the marketing spend increased, it got several leads from different sources. Although it had spent significant money on acquiring customers, it had to be profitable in the long run to sustain the business. The major cost that the company is incurring is the customer acquisition cost (CAC).
- At the initial stage, customer acquisition cost is required to be high in companies. But as their businesses grow, these companies start focussing on profitability. Many companies first offer their services for free or provide offers at the initial stages but later start charging customers for these services.
- Businesses want to reduce their customer acquisition costs in the long run. The high customer acquisition cost is due to following reasons:
    * Improper targeting
    * High competition
    * Inefficient conversion
- Job of ML team is to create Lead categorisation system to help sales team.


## Objectives
- Having junk leads in the pipeline creates significant inefficiency in the sales process. Thus, the goal of the data science team is to build a system that categorises leads based on the likelihood of their purchasing CodePro’s course. This system will help remove the inefficiency caused by junk leads in the sales process.
- We are creating three different pipelines for our use case:
   * Data pipeline - Continuous collection of data
   * Training pipeline - Retrain the model wherever there is change in input data, for example, launch of new program
   * Inference pipeline - Categorises the lead based on the likelihood of their purchasing CodePro’s course


## Technologies Used
- library - pandas
- library - sklearn
- library - pycaret
- library - sqlite3
- library - mlflow
- library - logging
- tools - airflow
