
# Soft Drink Market Insight Challenge
# Executive Report on Soft Drink Market Insights
This analysis, based on a real-world survey of  about 1,500 outlet visits across Alimosho LGA, Lagos, reveals the intense, street-level competition in Nigeria’s soft drink category and explains why global giants still dominate despite aggressive local challengers.
Objective Deliver a concise, board-ready summary of brand performance and distribution realities in Alimosho (Nigeria’s largest soft drink market) based on survey data from 1,500+ outlets.
# Approach & Methodology (How the Report Was Built)
1.	Started with the raw 1,500 × 38 wide-format CSV containing binary (0/1) flags for every brand, package, and display type per outlet.
2.	Transformed the data in Power Query:
o	Promoted headers, removed blank rows and S/N column
o	Unpivoted all brand columns → created long format (one row per brand found per outlet)
o	Repeated unpivot for Package Type and Display Type columns, keeping only present items
o	Created a unique Outlet Key (Latitude + Longitude concatenation)
o	Classified individual brands into four Brand Groups: Coca-Cola Family, Pepsi Family, La Casera, Local/Other
o	Standardized outlet types (e.g., all “Shop” variants → “Provision Store/Kiosk”)
3.	Built key DAX measures in Power BI:
o	Total Outlets (distinct outlet count)
o	Numeric Distribution % per Brand Group
o	Share of Chilled (cooler presence) per brand and overall
o	Stock Condition distribution
4.	Created supporting visuals: matrix tables, geographic maps, stacked bars, and availability charts.
5.	Validated insights against raw counts and cross-charts to ensure no transformation errors.
# Key Findings
1.	Coca-Cola leads with 84% Numeric Distribution, followed by Pepsi (73%) and resilient Local/Other brands (66%). La Casera lags badly (<30%).
2.	Channel Dynamics: Formal vs Informal Battleground Shops (provision stores) and kiosks represent >80% of all outlets and are the true powerhouse channels with over 1,200 active points. Supermarkets, while fewer in number, remain prestige locations. International brands (Coca-Cola and Pepsi) command formal retail (shops & supermarkets), whereas Local/Other brands (Bigi, Fearless, American Cola, etc.) dominate hawking and show remarkable strength in kiosks – highlighting their superior penetration of informal, high-footfall micro-locations
3.	Supply Chain Reliability = Winning Edge Coca-Cola and Pepsi maintain the highest “well-stocked” ratios and the lowest out-of-stock incidents, demonstrating superior demand forecasting and distributor push. Remarkably, Local/Other brands now match global players on stock depth in outlets where they are present, showing that the historical supply-chain gap is closing fast. La Casera is the clear laggard, suffering chronic stock inconsistency.
4.	Share of chilled is virtually identical (20–35%) across all brands once present in an outlet – leadership in chilled volume is purely a function of broader distribution.
5.	Competition is hyper-local: all brands heavily overlap in the same high-traffic corridors (Egbeda, Ikotun, Idimu, Gowon Estate).
# Conclusion & Recommendation 
In Alimosho, category share is won through two non-negotiables: Firstly, being present in more outlets than competition, and secondly, perfect availability when present. Coca-Cola currently executes both better than anyone else.
