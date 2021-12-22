# Holiday_Business_Segments-
## Problem Statement
We have been tasked with estimating daily cases for two separate business segments aggregated at the country level for the next three months, taking into account the following significant Indian holidays (not a complete list): Diwali, Dussehra, Ganesh Chaturthi, Navratri, Holi, and other Hindu festivals (You are free to use any publicly available open source external datasets). Other instances may include:

Weather Macroeconomic variables Note that the external dataset must belong to a reliable source.

Weather and macroeconomic factors It's worth noting that the external dataset must come from a reputable source.

Dictionary of Data The train information was delivered in the following format:

Historical data for business sector 1 has been made accessible at the branch ID level. Historical data for business sector 2 has been made accessible at the state level.
File Variable Training application date is a term that is defined as follows: Segment of application date 1/2 of the business segment branch id An anonymous identifier for the branch where the application was received The state where the application was submitted (Karnataka, MP etc.) state where the application was received (Central, East etc.) case count is a function that counts the number of cases (Target) The number of cases/applications that have been received

Forecasting for the dates supplied in the test set for each section must be done at the nation level.

id of a variable definition Application date for each sample in the test set with a unique id Segment of application date 1/2 of the business segment

## Evaluation
Metrics for Evaluation *MAPE (Mean Absolute Percentage Error) M is the assessment metric for rating the forecasts, following the formula:

Where At denotes the current value and Ft denotes the predicted value.

For both portions, the final score is derived using MAPE and the formula:

## Important Notes
When deciding on the winners, the practicality of implementing the best ideas will be taken into account. Both business groups must be satisfied with the outcome of the solution.

The data from the public and private split tests is separated into two categories: public (1st month) and private (2nd month) (Next 2 months)
