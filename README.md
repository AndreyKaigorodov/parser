# Financial Statement Parser
# Purpose
The purpose of this project is to collect data from financial statements of companies: balance sheet, income statement, and cash flows, as well as multipliers to automate the decision based on this data wether to purchase/not purchase an asset in an investment portfolio

# Decision logic
The decision is made as follows. The main metrics are calculated for a period of N years: the average annual growth rate of net profit, the average annual growth rate of equity capital, average ROE, the amount of long-term debt of the company to net income; also calculation of additional metrics: revenue, assessment of the effectiveness of top management, ROS, P/E. 

Next, based on the metrics, a decision is made which of the 4 categories the analyzed company belongs to.

A) Successful company (growing) -> worth adding to your portfolio

B) Just a profitable company (good) -> worth adding to your portfolio

C) Unsustainable (pre-crisis) -> not worth adding to your portfolio

E) Unprofitable (crisis) -> not worth adding to the portfolio

Additionally, data on annual and quarterly reports is saved for further analysis, building reports to track trends.

$E = mc^2$.


