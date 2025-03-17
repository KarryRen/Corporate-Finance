# Mid-Term Review Note

针对 Corporate Finance 期中考试进行复习。以 PPT 内容为核心，捋一遍框架，将课程思路弄清楚，然后将重点放在 Cheat Sheet 上。

## 0. Introduction

Introduction 章节介绍了 Corporate Finance 所关注的问题：

- Which investment project should Tailored Brands pursue/discontinue ？（投资决策）
- What is the fair value of Tailored Brands in a M&A market ？（资产定价）
- How much debt should Tailored Brands maintain ？Should it reduce its dividends/share repurchase ？（资产架构）

### Corporation

> 这门课所针对的核心目标就是 Corporation，在此探讨一下常见的三种组织形式。

**Sole Proprietorship** 独资企业/个体户（A business owned by **a single person**）

- **No formal charter required**, very few government regulations
- **Unlimited liability** for business debt since no distinction between personal and business assets
- Profit taxed as individual income (**single taxation**)
- **Equity is limited** to the proprietor’s personal wealth
- **Duration is limited** to the life of the sole proprietor

**Partnership** 普通/有限合伙人（A business with two or more owners）

- General partnership:
  - All partners provide work and cash
  - All partners share the profit and losses
  - Each partner is liable for all the business debt
- Limited partnership:
  - At least one general partner. Others are limited partners
  - Limited partners are liable for business debt up to the contributed equity
  - General partner(s) manage the business and have unlimited liabilities for business debt
  - Limited partners do not participate in daily management
- Features:
  - Partnerships are inexpensive to form, subject to very few regulations
  - General partners have unlimited liabilities for all debts
  - Limited partners enjoy limited liabilities
  - Difficulty in raising large amount of equity. Limited to partners’ capacity and desire to contribute
  - Duration of business is limited to life of partners
  - Difficult to transfer ownership

**Corporation**

- A corporation is a distinct legal entity, separated from its owners
- Ownership in a corporation is represented by shares of stock
- Ownership is readily transferrable, no impact on existence of business
- Unlimited life, not subject to owners’ life or exit/change
- Limited liabilities: Owners are liable up to the equity contribution
- Double taxation: Corporate income tax + individual income tax

### Decision Makers

> Shareholder => Board of directors (directors can be non-shareholders) => Management team

- Board chair: voted by the directors
- Inside directors, who work day-to-day at the company
- CEO, CFO, manager, or any other person who works for the company daily
- Outside/independent directors 独立董事, who can make impartial judgments. NYSE & NASDAQ request more than half board to be independent directors but China >= 1/3.

**Shareholder votes for**

- The makeup of the board of directors 
- Issuing new securities
- Initiating corporate actions like mergers or acquisitions
- Approving dividends
- Substantial changes in the corporation's operations or policies

### Goal of Company

**Maximize Shareholders’ Value**

- Why not market share, profit, growth, survival, risk management… ?: “Value” encompasses all above
- Why not creditors’, employees’, customers’, community’s…?: Chief decision makers (executives) are hired by shareholders!

**True or False** (All are False)

- The goal of financial management for a public firm is to maximize the current value per share of the existing stocks.
- The goal of financial management is to maximize the value of existing owners’ equity.
- We evaluate financial managers’ decisions on the basis of whether they add value to the business owners.
- Maximizing shareholders’ value is equivalent with maximizing firm value.
- Maximizing shareholders’ value is equivalent with maximizing the value of all the stakeholders (i.e., creditors, suppliers, customers, government, community, etc.)

**ESG affect firm value**

- ESG affects long term cash flow: Government intervention and Emission allowances and carbon allowances auctions
- Customer preferences;
- Brand value;
- Employee disruption of business (such as OpenAI’s mass exodus);
- ESG affects discount rate: Non-ESG imposes risk factors. Climate change and Resource scarcity;
- Investor preferences: Green equity (firm based), Green bond (project-based);

### Related Decisions

**Capital Budgeting**

- What long-term investments and projects should be taken?
- M&A

**Capital Structure**

- How should we raise finance for our investments?
- Should we use debt or equity? What percent?

**Working Capital/Liquidity Management**

- How do we manage the day-to-day finances of the company?

不同的参与者有不同的需求。

**Corporate managers:**

- Capital budgeting (long-term asset investment decisions)
- Financing decisions (debt vs. equity)
- Acquisition, Going Public, Going Private, etc.
- The basic rules of making good decisions

**Investors/ fund managers/ investment bankers:**

- Offer cash in exchange for future cash flows
- As investor at buy side, how to judge a good deal
- As underwriter at sell side, how to sell a deal



## 1. NPV and Basic Concepts of Corporate Finance

### The definition of value

An asset creates value for its owner if it generates a positive value of cash flows.

**Cash Flows**

- Cash Flows occur in the future
- Unless contractually fixed, cash flows need to be forecasted
- For non-financial assets (e.g., cash flows from investment projects), cash flows can be conceptually challenging.

**Value-related Decision**

- Acquire an asset in exchange for future cash flows

- Corporate Manager: Invest in real assets which generates future cash flows
- Investors: Invest in financial assets which entitle the owner to future payments. Bond/Loan: Principal & Interest Stock: Dividend and Capital Gain;
- Value of a single unit of asset is its fair market price.

**The value of Money**

- opportunity cost: the forgone benefit that would have been derived from an option other than the one that was chosen.
- Annuity 定期年金: Cash flows are constant for T periods: C1=C2=…=CT (debt coupon payment)
- Perpetuity 永续年金: Infinite series of equal payments: C1=C2=..=CT=CT+1=.. (perpetuity debt 永续债, preferred stock 优先股)
- Growing Annuity 增长年金: Ct+1=(1+g)Ct. Cash flows that are growing at a constant rate (wage, bonds with “Step-Up” Coupon)
- Growing Perpetuity 永续增长年金: Infinite series of cash flows that are growing at a constant rate (firm valuation, government sustainability analysis)

**Risky Cash Flows**

Investment A generates cash flow of \$105 with **certainty** next year (Risk-free). Investment B’s cash flows are risky (50%=>110, 50%=100). How much are you willing to pay for Investment A? Suppose the risk-free rate is 10%, PV_A =105/(1+10%)=95.45 , the price will be \$95.45. How much are you willing to pay for B? If you are risk averse , it would be less. If you are willing to pay $90, what is your discount rate? 𝑃𝑉 =90 =105/(1+ 𝑟 ), 𝑟 =16.67%.  The risk-premium for Investment B is 16.67%-10% = 6.67%. Investors require a higher return for riskier financial assets.

