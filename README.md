# CBA-DDM-VALUATION
Two-stage Dividend Discount Model valuing Commonwealth Bank (CBA.AX) in Excel. Includes CAPM cost of equity, regression and peer-based beta estimation, sensitivity analysis and an investment recommendation.
Commonwealth Bank (CBA.AX) – Dividend Discount Model Valuation

An Excel-based equity valuation of Commonwealth Bank of Australia using a two-stage Dividend Discount Model. Dividends are the cleanest way to value a bank, because its cash flows are hard to separate from its debt funding. That makes DDM the standard method for banks, where DCF doesn’t fit well.

Methodology

Risk-free rate
Built the Australian Government Bond yield curve (1 to 15 years) and chose the 10-year yield (5.04%) to match a long-term equity investment horizon.
Beta estimation, two approaches
Approach 1 (firm beta): Regressed 60 months of CBA returns against the ASX 200 using the SLOPE and Covariance/Variance methods. Levered beta: 1.24
Approach 2 (industry beta): Unlevered the betas of five ASX-listed peers (WBC, ANZ, NAB, MQG, BEN) with the Hamada equation, averaged them, then relevered at CBA’s target D/E of 2.88 from the FY2025 Annual Report
Cost of equity (CAPM)
Approach 1: 12.47%
Approach 2: 12.27%
Market risk premium: 6%
Growth assumptions
High growth (g1): 7.19%, based on CBA’s historical dividend growth
Stable growth (g2): 2.225%, the long-run average of Australian real GDP growth (2021 excluded because of COVID distortion)
Two-stage DDM
Projected dividends over 5 high-growth years from the FY2025 dividend of $4.95, then added a Gordon Growth terminal value at Year 5.

Results

Approach 1: Intrinsic value $60.33
Approach 2: Intrinsic value $61.57
Market price: $174.49
Implied overvaluation: about 65%
Recommendation: HOLD / AVOID

Sensitivity analysis
Two data tables test the intrinsic value against:

Stable growth (g2) vs high growth (g1)
High growth (g1) vs cost of equity (Ke)

Key takeaway
CBA trades at a large premium to its dividend-based value. The market is pricing in more than dividends: its status as Australia’s highest-quality bank, a strong ROE and a lower perceived risk than CAPM implies.

Data sources
Yahoo Finance (monthly prices for CBA, the ASX 200 and peers), CBA FY2025 Annual Report, RBA bond yields, ABS real GDP data.

Tools
Microsoft Excel
