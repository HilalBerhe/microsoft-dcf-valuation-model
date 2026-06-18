# Microsoft DCF Valuation Model

## Project Overview

This project presents a Discounted Cash Flow (DCF) valuation model for Microsoft. The model estimates Microsoft’s implied intrinsic value per share using forecasted unlevered free cash flow, terminal value analysis, enterprise value, equity value, and market value comparison.

The purpose of this project is to demonstrate practical financial modeling, valuation, forecasting, Excel analysis, and investment analysis skills relevant to financial analyst, FP&A analyst, corporate finance, and valuation-focused roles.

All figures are shown in **millions of U.S. dollars**, except per-share values, percentages, dates, and valuation multiples.

## Model Preview

### DCF Summary Dashboard

![DCF Model Dashboard](./DCF%20Model%20Part%201.png)

### Valuation Output

![DCF Valuation Output](./DCF%20Model%20Part%202.png)

## Key Valuation Output

Based on the base-case assumptions used in the model, the DCF analysis estimates an implied intrinsic value of approximately **$414.03 per share**, compared to a current market price of **$384.41**.

This implies approximately **7.7% upside**, suggesting that Microsoft may be slightly undervalued under the assumptions used in this analysis.

| Metric                          |  Result |
| ------------------------------- | ------: |
| Current Share Price             | $384.41 |
| Implied Intrinsic Value / Share | $414.03 |
| Implied Upside                  |   7.71% |
| Internal Rate of Return (IRR)   |   10.0% |
| Discount Rate                   |    9.0% |

## Key Assumptions

| Assumption              |           Value |
| ----------------------- | --------------: |
| Tax Rate                |           17.0% |
| Discount Rate           |            9.0% |
| Perpetual Growth Rate   |            3.0% |
| EV/EBITDA Exit Multiple |           20.0x |
| Current Share Price     |         $384.41 |
| Shares Outstanding      |   7,465 million |
| Debt                    | $60,588 million |
| Cash                    | $30,242 million |
| Capital Expenditures    | $40,255 million |

## DCF Methodology

The model calculates unlevered free cash flow by starting with EBIT, subtracting estimated cash taxes, adding back depreciation and amortization, subtracting capital expenditures, and subtracting changes in net working capital.

The model then discounts projected free cash flows and terminal value to estimate enterprise value. After adjusting for cash and debt, the model calculates implied equity value and implied intrinsic value per share.

## Free Cash Flow Forecast

| Year | Unlevered Free Cash Flow |
| ---- | -----------------------: |
| 2026 |         $105,142 million |
| 2027 |         $119,355 million |
| 2028 |         $135,820 million |
| 2029 |         $154,115 million |
| 2030 |         $174,503 million |

## Terminal Value Analysis

The model estimates terminal value using two methods:

1. **Perpetual Growth Method**
2. **EV/EBITDA Exit Multiple Method**

The base-case valuation uses the average of both methods.

| Terminal Value Method          |              Value |
| ------------------------------ | -----------------: |
| Perpetual Growth Method        | $2,751,771 million |
| EV/EBITDA Exit Multiple Method | $5,238,928 million |
| Average Terminal Value         | $3,995,350 million |

## Valuation Summary

| Valuation Item               |              Value |
| ---------------------------- | -----------------: |
| Enterprise Value             | $3,121,094 million |
| Plus: Cash                   |    $30,242 million |
| Less: Debt                   |    $60,588 million |
| Equity Value                 | $3,090,748 million |
| Shares Outstanding           |      7,465 million |
| Implied Equity Value / Share |            $414.03 |

## Market Value Comparison

| Metric                          |              Value |
| ------------------------------- | -----------------: |
| Market Capitalization           | $2,869,621 million |
| Plus: Debt                      |    $60,588 million |
| Less: Cash                      |    $30,242 million |
| Market Enterprise Value         | $2,899,967 million |
| Current Share Price             |            $384.41 |
| Implied Intrinsic Value / Share |            $414.03 |
| Implied Upside                  |              7.71% |

## Model Highlights

* Built a DCF valuation model for Microsoft
* Created a forecast period from 2026 through 2030
* Projected EBIT, taxes, depreciation and amortization, capital expenditures, and working capital
* Calculated unlevered free cash flow
* Estimated terminal value using both perpetual growth and EV/EBITDA methods
* Calculated enterprise value, equity value, and implied share price
* Compared implied intrinsic value to current market value
* Included IRR analysis to estimate expected return
* Added charts to summarize free cash flow growth and valuation output

## Skills Demonstrated

* Financial statement analysis
* Discounted Cash Flow valuation
* Free cash flow forecasting
* Revenue and margin analysis
* Working capital analysis
* Capital expenditure forecasting
* Terminal value calculation
* Enterprise value to equity value bridge
* IRR analysis
* Excel modeling and formatting
* Investment analysis and valuation interpretation

## Files Included

| File                       | Description                                                                                                |
| -------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `Microsoft-DCF-Model.xlsx` | Main Excel valuation model                                                                                 |
| `DCF Model Part 1.png`     | Screenshot of the DCF dashboard, assumptions, cash flow chart, and valuation chart                         |
| `DCF Model Part 2.png`     | Screenshot of the detailed DCF output, terminal value, enterprise value, equity value, and return analysis |
| `README.md`                | Project documentation                                                                                      |

## Conclusion

The DCF analysis suggests that Microsoft may be slightly undervalued under the base-case assumptions used in this model. The estimated intrinsic value of **$414.03 per share** is above the current share price of **$384.41**, implying approximately **7.7% upside**.

The model also estimates an internal rate of return of approximately **10.0%**, which is slightly above the discount rate of **9.0%**. This suggests a modestly attractive return profile under the assumptions used.

However, the valuation is sensitive to key assumptions, including the discount rate, perpetual growth rate, revenue growth, margins, capital expenditures, working capital changes, and terminal value methodology.

## Disclaimer

This project is for educational and portfolio purposes only. It is not investment advice and should not be considered a recommendation to buy, sell, or hold any security. The assumptions and outputs are based on a financial model created for practice and demonstration purposes.
