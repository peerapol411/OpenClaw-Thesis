# Investment Rules - ThesisVenture (Buffett & Munger Edition)

## Buy Rules
To execute a new BUY order, Nick must verify the alignment of the research team. Unlike conventional funds, we prioritize quality and value over market momentum:
- **Ben's Fundamental Verdict:** Must be **PASS** (Mandatory baseline: Verified Economic Moat, ROE > 15%, and trading below Intrinsic Value).
- **Sarah's Technical Verdict:** Must be **PASS** or **NEUTRAL** (Ensuring we are not buying a vertical parabolic peak; looking for accumulation or stabilization).
- **Alex's Sentiment Verdict:** Must be **PASS** or **NEUTRAL** (No structural integrity or corporate governance failures).

*Decision Matrix:*
- If Ben PASS + Sarah (PASS/NEUTRAL) + Alex (PASS/NEUTRAL) → **BUY**
- If Ben NEUTRAL or FAIL → **Do NOT Buy** (Never compromise on fundamental quality)
- If any agent reports **FAIL** → **Do NOT Buy**

## Hold Rules
- **The Infinite Horizon:** Hold as long as the company's competitive advantage (Economic Moat) and fundamental thesis remain intact.
- **Volatility is an Opportunity:** Short-term market price drops are fluctuations, not a reason to sell. If price drops while fundamentals improve, it is an opportunity to acquire more.
- **Deep Review:** Conduct a comprehensive review every Quarter following official earnings releases and 10-Q/10-K filings.

## Sell Rules
We do not sell based on short-term price movements or chart breakdowns. We only exit a position under the Munger & Buffett principles:
- **Structural Thesis Invalidation (Ben FAIL):** Permanent erosion of the Economic Moat, structural collapse in earnings, or permanent decline in industry relevance.
- **Integrity/Governance Failure (Alex FAIL):** Discovered accounting irregularities, corporate fraud, or severe management dishonesty (We do not sit in a room with cockroaches).
- **Extreme Overvaluation:** The market price rises to a level that completely outstrips any realistic future cash flows, destroying the Margin of Safety.
- *Note: Sarah's Technical FAIL will NEVER trigger a sell on its own if fundamentals are thriving.*

## Position Sizing
Concentration builds wealth; diversification preserves it. Nick manages allocation strictly within these guardrails:
- **Initial Conviction Size:** 10% of total portfolio value ($1,000 USD baseline) for a new position.
- **Maximum Position Limit:** No single stock can exceed 25% of total portfolio value.
- **High-Conviction Discretion:** Nick has full discretion to allocate maximum capital only when Ben signals an exceptionally wide Margin of Safety.

## Risk Management
- **No Leverage:** Absolute ban on margin, debt, short-selling, or complex derivatives. We only invest cash.
- **Cash Reserve:** Maintain a minimum 10% cash reserve ($1,000 USD) at all times to capitalize on market panics.
- **Anti-FOMO Guardrail:** Freeze all new BUY decisions if cash falls below the 10% threshold.

## Fund Rules
- **Total Capital:** $10,000 USD starting baseline
- **Min Cash Reserve:** 10% ($1,000) at all times
- **Max Positions:** 10 stocks maximum (Focus on high-conviction ideas, avoid "diworsification")

## Position Management

### Adding to Existing Position (Scale In / Value Accumulation)
- May add to a position if the business thesis is confirmed by 2+ consecutive earnings beats.
- **The Buffett Dip:** May average down on a losing position *ONLY* if Ben re-verifies that the thesis is intact, management is honest, and the Margin of Safety has actually widened due to the price drop.
- **Tranche Limit:** Maximum of 3 total buying tranches per stock, spaced at least 10% apart in price.

### Trimming Position (Scale Out)  
- **Automatic Allocation Trim:** Automatically trim back to 20% if organic stock growth drives a single position to exceed 25% of total portfolio value.
- Trim when a stock is up >100% *AND* Ben reports fundamental growth deceleration or margin contraction.

## Rebalancing Rules
- Review portfolio metrics and allocation every quarter.
- No single stock > 25% of portfolio value.
- No single sector > 40% of portfolio value (Prevent structural sector over-exposure).

## Weekly Checklist
Before making or logging any portfolio action, Nick must check off this list:
- [ ] Read all 3 updated research reports (Ben, Sarah, Alex)
- [ ] Audit the current pipeline against `portfolio/mistakes.md`
- [ ] Calculate the available Cash Reserve (Confirm it is > 10% before any BUY)
- [ ] Verify that no sector allocation will exceed 40% post-transaction
- [ ] Confirm the date and quarter of all financial data used by Ben

## Portfolio Calculation Rules
These rules are SYSTEM STRICT and must be executed mathematically without deviation:

### Cash Calculation
- Cash balance is treated as static and independent of asset price movements.
- Cash *ONLY* alters when an explicit transaction occurs:
  - **BUY Action:** Cash = Cash - Actual Amount Spent (Shares x Purchase Price)
  - **SELL/TRIM Action:** Cash = Cash + Actual Amount Received (Shares x Sale Price)

### Portfolio Value Calculation
- **Total Portfolio Value** = Cash + Sum of all (Shares x Current Market Price)
- **Invested Amount** = Sum of all (Shares x Current Market Price) — evaluated Mark-to-Market
- **Total Return %** = (Total Portfolio Value - Starting Capital) / Starting Capital x 100%

### Calculation Example (Sanity Check)
- Starting Capital: $10,000
- Action: Buy NVDA 9.30 shares @ $215.05 = $2,000 spent
- Cash after buy: $10,000 - $2,000 = $8,000
- NVDA price rises to $235.74 (Mark-to-Market)
- NVDA Current Value: 9.30 x $235.74 = $2,192.38
- Invested Amount: $2,192.38
- Total Portfolio Value: $8,000 (Static Cash) + $2,192.38 = $10,192.38
- Total Return: ($10,192.38 - $10,000) / $10,000 = +1.92%