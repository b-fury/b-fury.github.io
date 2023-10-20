The primary use of the cost of capital is to evaluate investment opportunities to determine if they are profitable. Typically, an investment opportunity is profitable if its rate of return is higher than the company's cost of capital. For example, if a business opportunity promises a rate of return of 15% and the company's cost of capital is only 10%, it is a good opportunity for the company to invest in because it generates more return that the company must offer its investors. It is important to note, however, that the WACC is the appropriate discount rate only if the proposed investment is similar to the company's overall existing business. When a firm has different operating divisions with different risks, its WACC is an average of the divisional required returns. In such cases, it is not appropriate to use the WACC as the cost of capital for each division. To ensure correct decisions, the cost of capital for different risks within the same firm needs to be established. We can accomplish this in two ways:

1. Pure-play approachThis involves using the cost of capital for a company that specializes in the division's line of business. For example, to estimate the cost of capital for its finance arm (GE Capital), GE can use the cost of capital estimated for a traditional finance company or bank.
2. Subjective risk categoriesThe firm creates subjective risk categories by assigning investment opportunities to different risk baskets, for example, very high risk, high risk, average risk, low risk, and very low risk. The cost of capital for each risk category is determined by adding or subtracting a premium from the WACC. For example, suppose the overall WACC is 12%, then projects in the very high-risk category can be assigned a cost of capital of 18%, that is, the base WACC of 12% plus a risk premium of 6%, while projects in the very low-risk category can be assigned a cost of capital of 8%.

## Agency Relationships + Financial Ratios

### Liquidity ratios

Quick Ratio = (Current Assets-Inventories)/Current Liabilities

Current Ratio = Current Assets/Current Liabilities

### Asset management ratios

Inventory Turnover Ratio = Sales Revenue/ Inventories

Dales Sales Outstanding = Accounts Receivable / (Sales/365)

Fixed Asset Turnover = Sales/Net PPE [Property, plant, equipment]

Total Asset Turnover Ratio = sales/total assets

### Debt management ratios

Total Debt Ratio = (Short-term+Long Term Debt)/Total Assets

Debt to Capital Ratio = (short term + long term debt)/(Short term + long term debt + Shareholders Equity)

Debt-Equity Ratio = (Short Term + long term debt)/ Shareholders equity

Total interest Earned (TIE) = Operating Income (EBIT)/Interest Expense

### Profitability ratios

Basic Earning Powers = Operating Income (EBIT)/Total Assets

Return on Assets = Net Income / Total Assets

Profit Margin = Net Income/ Sales Revenue

Return on Equity = Net Income / Shareholders Equity

### Market value ratios

Price-Earnings Ratio = Price per Share / Earnings per share

Market/book Ratio = (Price Per Share* Shares Outstanding)/Shareholders Equity

## Time Value Of Money

**PV:** present value or cash flow in today's dollars

**PMT:** regular cash flow received or paid over a period, for example, $100 per month for five years

**FV:** future value or cash flow at some point in the future

**I:** interest rate paid or earned per period

**N:** number of periods

$\text{FV}=\text{PV}\left(1+i\right)^N$﻿

EXAMPLE: Suppose you deposit $100 today in an account paying 5% interest per year. How much would you have in the account in 3 years, assuming you make no further deposits or withdrawals?

$\text{FV}=\text{PV}\left(1+i\right)^N=\$100\times\left(1.05\right)^3=\$115.76$﻿

💡

In Excel, use the FV function. Select the **Function Ribbon**, **Financial Functions**, and **FV**. This will bring up the following dialog box. Complete it as indicated, and select **OK** to get the same answer, $115.76.

$\text{PV}=\text{FV/}\left(1+i\right)^N=\text{FV}\left(1+i\right)^{-N}$﻿

**Uneven Cash Flow Example**

Suppose you are planning to buy a house five years from now, and you want to start saving for the down payment today. You have just opened a savings account at your local credit union. The account pays an interest rate of 5% per year, and your opening deposit (made today) is $2,500. You anticipate that you will save additional amounts over the next years as follows: $3,000 a year from today, $4,000 two years from now, $5,000 in three years, and $5,500 in four years. How much would you have in the account five years from today? How much would you have if you delay the start of savings by a year, that is, you will open the savings account a year from today with $2,500 and deposit $3,000, $4,000, $5,000, and $5,500 in years 2 – 5?

**Solution**

If you start the savings today, the cash flows look like this: Year 0 (now), $2,500; Year 1, $3,000; Year 2, $4,000; Year 3, $5,000; Year 4, $5,500. To find the future values in 5 years, note that the first deposit has 5 years to grow, the second has 4 years, the third has 3 years, the fourth has 2 years, and the fifth has only 1 year to grow. Therefore, the respective future values using an interest rate of 5% are as follows:

|   |   |   |   |   |
|---|---|---|---|---|
|Deposit #|Amount|# Years|Rate|FV|
|1|2500|5|5%|$3,190.70|
|2|3000|4|5%|$3,646.52|
|3|4000|3|5%|$4,630.50|
|4|5000|2|5%|$5,512.50|
|5|5500|1|5%|$5,775.00|
|Total||||$22,755.22|

If you start saving a year late, note that everything will be delayed by one year, which means that the first deposit will now grow for 4 years, the second for 3 years, the third for 2 years, the fourth for 1 year, and the fifth for 0 years (that is, the fifth deposit gets no chance to earn interest). The solution is presented in the table below:

|   |   |   |   |   |
|---|---|---|---|---|
|Deposit #|Amount|# Years|Rate|FV|
|1|2500|4|5%|$3,038.77|
|2|3000|3|5%|$3,472.88|
|3|4000|2|5%|$4,410.00|
|4|5000|1|5%|$5,250.00|
|5|5500|0|5%|$5,500.00|
|Total||||$21,671.64|

  

## Annuities

### future value of an ordinary annuity

$\text{FV}=\text{PMT}\left(\frac{\left(1+i\right)^N\text{-1}}i\right)$﻿

### Future Value of Annuity Due

$\text{FV}=\text{PMT}\left(1+I\right)\left(\frac{\left(1+i\right)^N\text{-1}}i\right)$﻿

### Preset Value of Ordinary Annuity

$\text{PV}=\text{PMT}\left(\frac{1-\left(1+i\right)^{-N}}i\right)$﻿

### Present value of annuity Due

$\text{PV}=\text{PMT}\left(1+i\right)\left(\frac{1-\left(1+i\right)^{-N}}i\right)$﻿

  

## Comparing Interest Rates

In calculating PVs or FVs, we generally deal with three different interest rates:

1. Quoted interest rate, also known as stated or nominal rate or annual percentage rate (APR) — This is stated in lending or deposit contracts. The compounding frequency per year is also given. For example, 8% APR with quarterly compounding means you earn 8%/4 = 2% per quarter; 8% APR with daily compounding means you earn 8%/365 = 0.022% per day.
2. Periodic rate. You earn this rate per period — In the example above, the periodic rate for 8% APR with quarterly compounding is 2%. The periodic rate is what we use in our calculations. We must take care to ensure that everything else is stated in the same time units; for example, monthly interest rate with monthly deposits or payments, quarterly interest rate with quarterly cash flows, and annual interest rates with annual cash flows.
3. Effective annual rate (EAR) — This rate produces the same ending future value as if annual compounding had been used, taking into account that when interest is earned more than once per year, you get to earn interest on interest. For example, if your nominal rate is 8% with quarterly compounding, that means you earn 2% each quarter. But you get to earn interest in the second quarter on the interest you earned in the first quarter. So, if you have $10,000 at the beginning of the first quarter, you will have $10,200 at the end of the quarter. During the second quarter, you will earn interest on the original $10,000 and the $200 of interest earned in the first quarter. The EAR is the actual annual rate of interest earned or paid, as opposed to the quoted rate. In this example, although the quoted rate is 8%, you will earn more than 8% because of the quarterly compounding. When interest rates are quoted with different compounding frequencies, the EAR is the only rate that can be compared.

$⁍$

APR is the quoted rate, and M is the frequency of compounding per year.

|APR|Frequency|Calculation|EAR|
|---|---|---|---|
|8%|Annual|(1 + 0.08/1)1 − 1|8%|
|8%|Semi-annual|(1 + 0.08/2)2 − 1|8.16%|
|8%|Daily|(1 + 0.08/365)365 &minus 1|8.33%|
|9%|Monthly|(1 + 0.09/12)12 − 1|9.38%|

## Cost of Capital and WACC

### Sources of Capital

- Debt (bonds)
    - Issue date: date when bond was issued, i.e., the date on which company borrows money.
    - Maturity date: date on which the debt is to be repaid.
    - Maturity: years until the debt must be repaid. Also called term to maturity or term.
    - Par value: amount to be repaid per unit of bond, also called face value. Usually $1,000.
    - Coupon rate: stated interest rate. Multiply by par value to get $ of interest.
- Preferred Equity: Preferred equity is an ownership stake with limited control rights and preferential cashflow rights, both relative to common equity. In general, preferred stock holders don’t have the right to vote in the election of directors, but they must be paid their dividends before common stock holders are paid.
- Common Equity: Common equity is the basic ownership stake in a company. Common stock holders elect directors who select the top managers responsible for running the business. Common stock holders are entitled to receive dividends when declared by the board of directors but cannot force the company to pay dividends if the board decides otherwise.

### Risk Adjusted Cost of Capital

The primary use of the cost of capital is to evaluate investment opportunities to determine if they are profitable. Typically, an investment opportunity is profitable if its rate of return is higher than the company's cost of capital. For example, if a business opportunity promises a rate of return of 15% and the company's cost of capital is only 10%, it is a good opportunity for the company to invest in because it generates more return that the company must offer its investors. It is important to note, however, that the WACC is the appropriate discount rate only if the proposed investment is similar to the company's overall existing business. When a firm has different operating divisions with different risks, its WACC is an average of the divisional required returns. In such cases, it is not appropriate to use the WACC as the cost of capital for each division. To ensure correct decisions, the cost of capital for different risks within the same firm needs to be established. We can accomplish this in two ways:

1. Pure-play approach: This involves using the cost of capital for a company that specializes in the division's line of business. For example, to estimate the cost of capital for its finance arm (GE Capital), GE can use the cost of capital estimated for a traditional finance company or bank.
2. Subjective risk categories: The firm creates subjective risk categories by assigning investment opportunities to different risk baskets, for example, very high risk, high risk, average risk, low risk, and very low risk. The cost of capital for each risk category is determined by adding or subtracting a premium from the WACC. For example, suppose the overall WACC is 12%, then projects in the very high-risk category can be assigned a cost of capital of 18%, that is, the base WACC of 12% plus a risk premium of 6%, while projects in the very low-risk category can be assigned a cost of capital of 8%.

  

### Weighted Average Cost of Capital