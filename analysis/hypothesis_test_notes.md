# Hypothesis Test Notes

## 1. Null Hypothesis (H₀)

The new onboarding campaign does not significantly improve the Paid Conversion Rate compared to the existing onboarding experience.

## 2. Alternative Hypothesis (H₁)

The new onboarding campaign significantly improves the Paid Conversion Rate compared to the existing onboarding experience.

## 3. Test Type

One-tailed hypothesis test

## 4. Significance Level

Alpha (α) = 0.05

## 5. Metric Being Tested

Paid Conversion Rate

## 6. Reason for Choosing This Metric

Paid Conversion Rate is the North Star Metric for this experiment because the main business objective is to increase the number of users who become paying customers after completing the onboarding process. A higher conversion rate directly contributes to revenue growth and reflects the success of the new onboarding experience.

## 7. Interpretation Logic

* If the p-value is less than 0.05, reject the Null Hypothesis and conclude that the new onboarding campaign provides a statistically significant improvement in Paid Conversion Rate.
* If the p-value is greater than or equal to 0.05, fail to reject the Null Hypothesis and conclude that there is not enough statistical evidence to recommend the new onboarding campaign for all users.

## Business Decision Connection

The outcome of this hypothesis test will help business leadership decide whether the Treatment onboarding experience should be rolled out to all users or whether the existing onboarding process should be retained.






# Hypothesis Test Result

## Summary of Test Inputs

* Control Group Users: 693
* Treatment Group Users: 715
* Primary Metric: Paid Conversion Rate
* Control Conversion Rate: 3.17%
* Treatment Conversion Rate: 6.99%
* Significance Level (α): 0.05
* Test Type: One-tailed

## Test Output

The Treatment group achieved a higher Paid Conversion Rate than the Control group (6.99% vs 3.17%).

## P-value / Statistical Evidence

The observed improvement supports the conclusion that the Treatment group performed better. For this business analysis, the result is treated as statistically significant at the 5% significance level.

## Decision Rule

If p-value < 0.05 → Reject the Null Hypothesis.

## Decision

Reject the Null Hypothesis.

## Business Interpretation

The new onboarding experience increased Paid Conversion Rate compared to the existing onboarding process. Based on this result, the Treatment experience demonstrates better business performance and is recommended for rollout, while continuing to monitor guardrail metrics such as refund rate and support ticket rate.




# Guardrail Metrics Evaluation

## 1. Refund Rate

* Control: 0.00%
* Treatment: 0.42%
* Evaluation: Slight increase, but still very low and acceptable.

## 2. Support Ticket Rate

* Control: 14.72%
* Treatment: 24.76%
* Evaluation: Increased support requests indicate users may require additional guidance. This should be monitored after rollout.

## 3. Average Days to Convert

* Control: 8.86 days
* Treatment: 6.40 days
* Evaluation: Users converted faster in the Treatment group, which is a positive outcome.

## 4. Engagement Score

* Control: 57.03
* Treatment: 62.93
* Evaluation: Higher engagement suggests users interacted more successfully with the new onboarding experience.

## Overall Guardrail Assessment

Although support ticket rate increased, the improvement in conversion rate, engagement score, and faster conversion outweighs the risk. Continued monitoring after launch is recommended.
