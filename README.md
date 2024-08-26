# duration_matching

Duration matching is a risk management technique used in fixed income portfolio management. The primary goal is to match the duration of assets and liabilities so that the portfolio is immunized against interest rate movements. When the durations are matched, the impact of changes in interest rates on the value of assets will be offset by the impact on the value of liabilities, thereby reducing interest rate risk.

Key Concepts
Duration:
Duration is a measure of the sensitivity of a bond's price to changes in interest rates. It represents the weighted average time until the bond's cash flows are received.
Macaulay Duration is the weighted average time until cash flows are received, weighted by the present value of the cash flows.
Modified Duration adjusts Macaulay Duration by dividing it by (1 + yield), making it a direct measure of price sensitivity to interest rate changes.

Interest Rate Risk:
The risk that changes in interest rates will affect the value of a bond or bond portfolio. Duration matching aims to minimize this risk.
Immunization:

The strategy of structuring a portfolio so that its duration matches the duration of its liabilities, thereby "immunizing" the portfolio against interest rate changes.


1. Present Value (PV) of a Cash Flow
The present value of a cash flow received at time t: 
PV = \frac{CF_t}{(1 + r)^t}
Where:
CF_t is the cash flow at time t.
r is the discount rate (or yield to maturity).
t is the time in years.

2. Macaulay Duration
Macaulay Duration D is calculated as the weighted average time until cash flows are received:
D = \frac{\sum_{t=1}^{T} \left( t \times \frac{CF_t}{(1 + r)^t} \right)}{\sum_{t=1}^{T} \frac{CF_t}{(1 + r)^t}}
Where:
t is the time in years when each cash flow CF_t is received.
r is the yield to maturity (discount rate).
T is the total number of periods.

4. Modified Duration
Modified Duration D_{mod} is derived from Macaulay Duration:
D_{\text{mod}} = \frac{D}{(1 + r)}
Where:
D is the Macaulay Duration.
r is the yield to maturity.

4. Duration Matching Condition
For duration matching, the average duration of assets should equal the average duration of liabilities 
D_A \approx D_L
This condition ensures that the portfolio is immunized against changes in interest rates.

Example
If you have a portfolio of assets and liabilities, you calculate the duration of each and ensure that:
\frac{\sum_{i=1}^{n} \left( w_i \times D_{A_i} \right)}{\sum_{i=1}^{n} w_i} \approx \frac{\sum_{j=1}^{m} \left( v_j \times D_{L_j} \right)}{\sum_{j=1}^{m} v_j}

