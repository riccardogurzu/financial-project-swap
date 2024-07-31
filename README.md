# Financial Derivatives Project

## Project Overview
This project involves analyzing a floating rate loan agreement and hedging its interest rate risk using various derivative products. The project requires using market data, performing calculations for cash flows, swap pricing, and evaluating alternative hedging strategies.

## Loan Details
- **Notional**: EUR 1,748,653.15
- **Start Date**: 19-01-2007
- **Maturity Date**: 19-01-2022
- **Interest Rate**: Euribor 6M, half-yearly, act/360, modified following, adjusted

## Tasks
### 1. Estimated Cash Flows
- Calculate the estimated cash flows of the loan as of January 15, 2007.

### 2. Interest Rate Swap for Hedging
- **Details of Swap**: Determine the details of an interest rate swap with an annual fixed rate 30/360 for a perfect hedge.
- **PV01 Calculation**: Calculate the PV01 of the swap.
- **Swap Pricing**: Determine the price of the swap considering a counterparty charge of 5bps from the fair value.
- **Market Value**: Calculate the market value of the swap at the trade date.
- **Historical Market Value**: Calculate the historic daily market value of the swap from 31.01.2007 to 30.11.2020.
- **Plot and Analysis**: Plot the market value of the swap and the market rate of the 15-year swap, and comment on the divergence of the lines.
- **Future Cashflows**: Provide a table for each swap leg's future cashflows as of December 18, 2020.

### 3. Alternative Hedge Products
- **Alternative 1**: Company pays a fixed rate X% annual 30/360 vs. Euribor 6M, with the bank having the right to cancel the swap after 10 years.
- **Alternative 2**: Company pays a fixed rate X% annual 30/360 vs. Euribor 6M, and sells a cap at 6%.
- **Alternative 3**: Company receives Euribor 6M and pays Euribor 6M capped at 6% and floored at X%.
- **Details and Fair Value**: Describe each derivative and determine the fair value for X.
- **Selection and Justification**: Choose the best alternative and justify your choice.
- **Rate Plot**: Plot the rate the company would pay under each alternative against Euribor 6M fixing between 0% and 10%.
