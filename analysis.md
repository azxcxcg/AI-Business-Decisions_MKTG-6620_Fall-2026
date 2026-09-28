# AI-Business-Decisions_MKTG-6620_Fall-2026

Q2:
(1): Data cleaning: After the python script was ran, there were 11 values left in "TotalCharges" that were empty. These need to be converted to numbers (entered as "0") so these rows can be compared against the rest of the data. These empty values are not anomalous and it makes sense to keep them as zeros.
(2): AUC: Contract = 74.27% | Logistic Regression = 83.84% | Boosted Trees = 84.56%
(3): Crosses zero? Yes the Top 2 (Boosted Trees vs. Logistic Regression) cross zero, meaning neither one is definitively better. -0.0049 and +0.0103

The Boosted Trees has an AUC of 0.84556, the highest among the three options. Logistic Regression is similar, at 0.8384. But the Contract Rule is the lowest at 0.7427.
Additionally, churn was highest in Boosted Trees, and lowest in Contract Rule. Thus Boosted Trees is best.

Q3:
Use the python script to clean data. Then with remanining actions (11 rows) change to zeros. Then ask AI to perform ranking via Boosted Trees as it has the highest AUC, and is slightly better than logisitc regression. FOcus on the top 20% of that list to contact as those customers have the highest churn so we will be more effective targeting those customers, vs. those who will not churn (those who will stay regardless).



