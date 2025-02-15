# AF3005_ProgrammingForFinance

Part 1: Loan Eligibility & Interest Rate Calculation
Objective: The system assesses loan eligibility based on three factors: employment status, income, and credit score. It returns an approval decision along with the interest rate.

Loan Eligibility Function:
The function loan_eligibility takes three inputs: income, credit_score, and employment_status.
It checks:
If the customer is unemployed, the loan is immediately rejected.
If the income is less than PKR 50,000, the loan is rejected.
If the credit score is above 750, a 5% interest rate is assigned; between 650 and 749, the rate is 8%.
If the credit score is below 650, the loan is rejected.
-----------------------------------------------------------------------------------------------------------------------------------------

Part 2: Investment Risk Assessment
Objective: The system classifies an investment portfolio based on stock returns. If any stock has a negative return, the portfolio is classified as High Risk. If all returns are positive but at least one is below 5%, it’s classified as Medium Risk. Otherwise, it is classified as Low Risk.

Risk Assessment Function:
The function assess_investment_risk iterates over the stock returns list.
It uses conditions to classify the portfolio based on the returns.
If any stock has a negative return, the risk is classified as High. If any return is below 5%, it’s classified as Medium. If all returns are 5% or above, it’s classified as Low.

-----------------------------------------------------------------------------------------------------------------------------------------

Part 3: Loan Repayment Tracker
Objective: The system helps customers track their loan repayments. It starts with an initial loan balance and deducts a fixed monthly payment until the loan is paid off. It then shows the remaining balance after each payment.

Loan Repayment Tracker Function:
The function loan_repayment_tracker runs a loop where the loan balance is deducted by the monthly payment at each step.
It continues until the loan balance reaches zero, then outputs the total number of months taken to fully repay the loan.

-------------------------------------------------------------------------------------------------------------------------------------

Part 4: Stock Price Monitoring and Trading Strategy
Objective: This feature allows stock traders to monitor stock prices daily. The system tracks stock prices and triggers an alert once the price hits PKR 200, at which point the stock is sold.

Stock Price Monitoring Function:
The function stock_price_monitor iterates through a list of stock prices.
It skips any missing data (represented by None) and stops tracking once the price reaches or exceeds PKR 200, triggering an alert to sell the stock.



------------------------------------------------------------------------------------------------------------------------------------

Part 5: Currency Exchange Rate Tracker
Objective: The system tracks currency exchange rates starting at PKR 290/USD and increases by 1 PKR daily until it reaches PKR 300/USD. It displays the exchange rate daily and stops when the target rate is reached.

Currency Exchange Tracker Function:
The function currency_exchange_tracker simulates a daily increase in the exchange rate.
It prints the exchange rate for each day and stops once the target exchange rate is reached.

















