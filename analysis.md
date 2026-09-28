# AI-Business-Decisions_MKTG-6620_Fall-2026

Q2:

(1): Data cleaning: After the provided python script was ran, there were 11 values left in "TotalCharges" that were empty. These need to be converted to numbers (entered as "0") so these rows can be compared against the rest of the data. These empty values are not anomalous and it makes sense to keep them (but as zeros).
(2): AUC: Contract = 74.27% | Logistic Regression = 83.84% | Boosted Trees = 84.56% | Boosted Trees is the better option, but only slightly better than Logistic Regression. Additionally, churn was highest in Boosted Trees, making it the best choice.
(3): Crosses zero?: Yes, the Top 2 (Boosted Trees vs. Logistic Regression) cross zero, meaning neither one is definitively better, so both are a fair choice, but Boosted Trees is slightly better.
- 95% paired bootstrap interval, trees vs. logistic, of -0.0049 and +0.0103, with an AUC difference of 0.0025

Q3:

Hi Devon,

We identified the top 20% of customers to target for retention. Below are the details of the experiment:

We ran run the data through a script to understand it and clean it, to prepare it for analysis. We identified 11 rows with missing values, which were converted to zeros (as consistent with surrounding data) so those rows could be included in the experiment. Next, a Boosted Trees experiment was conducted due to it being the best equipped to handle this scenario. The results include a ranked list where the top 20% represent customers with the highest churn rate, meaning our efforts will be best spent on those customers in an attempt to retain them, and not focus on customers who will stay regardless.
