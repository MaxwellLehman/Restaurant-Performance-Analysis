## Project Background
My client is an upscale seafood restaurant and steakhouse owned by a private equity firm that has requested the restaurant name and locations remain confidential. I am partnering with the General Manager to analyze first-quarter 2026 category-level sales and item-level cost data across three restaurant locations.

The primary objective of this analysis was to identify opportunities to improve profitability and uncover performance differences between locations. By examining sales trends and item-level cost patterns, this analysis identifies cost anomalies and key profit drivers, providing recommendations to maximize the impact of high-performing categories while improving purchasing efficiency across all three locations.

Insights and recommendations are provided on the following areas:
- **Category Level Performance:** Evaluation of overall spend distribution and cost contribution across major product categories.
- **Item Level Cost:** Identification of individual items driving cost variance within categories.
- **Location Level Variance:** Comparison of sales and purchasing patterns across locations to identify operational inconsistencies.

## Data Used
- This analysis uses first-quarter 2026 sales and cost data across five restaurant locations, with the scope narrowed to three locations as defined by management. The dataset includes category-level sales, item-level cost data, and location-level breakdowns of purchasing activity and sales performance. Sales data is reported at the category level, while cost data is reported at the item level, enabling both aggregate sales analysis and detailed cost analysis.

*The source data was transformed in Excel and modeled in Power BI using a star schema to support flexible category-, item-, and location-level reporting and analysis.*

<img width="800" height="484" alt="image" src="https://githubusercontent.com/user-attachments/assets/3505100e-9d05-408a-8ec9-aab9181f8641" />

## Overview of Findings
Analysis of first-quarter 2026 sales and cost data identified liquor as the restaurant's strongest profit driver, generating an average gross margin of 85.6% despite accounting for only 5.1% of total sales, presenting a significant opportunity to increase overall profitability. The analysis also uncovered notable cost anomalies across locations, including unusually high spending on Uncle Nearest 1856 at Location 2, which was confirmed to result from improper use of the product in a cocktail recipe. Additionally, Location 1 reported no costs for Raw Tail On 16-20 Shrimp, compared to approximately $9,000 and $12,000 at the other two locations, indicating a possible procurement discrepancy requiring further investigation. Based on these findings, recommendations focus on increasing sales of liquor products while strengthening inventory controls and purchasing oversight to address the Uncle Nearest 1856 and Raw Shrimp cost inconsistencies across locations.

## Category Performance
- Category-level analysis identified liquor as the restaurant's strongest profit driver, generating an average gross margin of 85.6% across all three locations. This was substantially higher than beer (71.6%) and the overall average margin of 65.9%. Although liquor accounted for only 5.1% of total sales, its high margin structure makes it the most efficient category for generating profit.

*The visualization below compares gross margin and total sales across categories, highlighting liquor as the highest-leverage driver of profitability despite representing a small share of total revenue.*

<img width="1412" height="791" alt="image" src="https://githubusercontent.com/user-attachments/assets/5a20fc9e-b5c8-4eef-93ac-1c0a133d161e" />

- This finding suggests that increasing liquor sales presents a highly effective opportunity to improve overall profitability. Unlike the restaurant's highest-selling category, food, which requires significant increases in sales volume to generate meaningful profit growth, liquor produces a substantial profit return on each additional dollar sold. Based on current performance, a 10% increase in liquor sales would be expected to generate approximately $18,000 in additional quarterly gross profit across the three locations while requiring relatively little incremental cost.

## Item-Level Anomalies
### Uncle Nearest 1856

- Analysis of liquor purchasing patterns identified Uncle Nearest 1856 as a significant cost anomaly. While most liquor products showed relatively balanced purchasing across all three locations, spending on Uncle Nearest 1856 was overwhelmingly concentrated at Location 2, which accounted for 91.8% of total purchases despite representing only one-third of restaurant operations.

*The visualization below compares top liquor purchases by value and highlights the individual cost and percentage share of Uncle Nearest 1856 across locations.*

<img width="1413" height="794" alt="image" src="https://githubusercontent.com/user-attachments/assets/d34a5338-043f-4b02-ac24-575b830c31a4" />

- To determine the cause of the variance, purchasing records were reviewed alongside bar recipes and operational procedures. Discussions with management confirmed that Uncle Nearest 1856 had been substituted into a cocktail recipe where Uncle Nearest 1884 was intended. This explanation aligned with the purchasing data, which showed unusually low spending on Uncle Nearest 1884 at Location 2. The substitution resulted in substantially higher consumption and purchasing volume of a more expensive liquor, driving elevated costs.

- This finding highlighted the value of item-level purchasing visibility in identifying operational issues that would have remained hidden within category-level reporting. While overall liquor spending appeared consistent across locations, drilling down to individual products revealed a purchasing pattern that was inconsistent with expected consumption behavior. By tracing the anomaly to a recipe discrepancy showed how a seemingly minor operational issue could create measurable cost differences across locations.

### Raw P&D Tail-On Shrimp 16-20

- Analysis of seafood purchasing patterns identified Raw P&D Tail-On Shrimp 16-20 as a notable reporting anomaly. While most seafood products showed relatively balanced purchasing across all three locations, reported spending on Raw P&D Tail-On Shrimp was entirely absent at Location 1. Instead, Locations 2 and 3 accounted for 42.5% and 57.5% of total recorded purchases, respectively, despite the product being used in the same menu offerings across all locations.

*The visualization below compares top seafood purchases by value and highlights the individual cost and percentage share of Raw P&D Tail-On Shrimp 16-20 across locations.*

<img width="1413" height="795" alt="image" src="https://githubusercontent.com/user-attachments/assets/097091d3-8e04-4d55-8704-0792796c0f83" />

- To determine the cause of the variance, item-level purchasing records and seafood sourcing practices were reviewed. While most fish and shellfish products exhibited purchasing patterns consistent with expected operational activity, Raw P&D Tail-On Shrimp 16-20 showed no recorded purchases at Location 1 despite having similar usage to the other locations. Further investigation revealed that Location 1 received shrimp through the commissary department, which purchased and distributed inventory separately from the restaurant-level purchasing system. As a result, shrimp costs associated with Location 1 were not reflected in the restaurant's direct purchasing records, creating the appearance that all purchases were concentrated at Locations 2 and 3.

- This finding demonstrated the value of item-level cost analysis in identifying data quality and procurement reporting issues that would have remained hidden within broader category-level reporting. While overall seafood spending appeared reasonable across locations, examining individual products revealed a purchasing pattern inconsistent with expected operational activity. By identifying the source of the discrepancy, the analysis provided a more accurate interpretation of seafood purchasing performance and highlighted a reporting limitation that should be considered when comparing costs across locations.

## Recommendations

- To capitalize on the high liquor margin, a recommendation was implemented to introduce seasonal cocktail pairings aligned with rotating menu specials (e.g., halibut-focused offerings in summer and crab-focused dishes in winter). This approach focuses on guests ordering seasonal specials, a  higher average ticket value segment with stronger beverage attachment potential.  The concept is currently being developed and integrated into the menu.

- Implement quarterly reviews of high-variance products during procurement meetings, with particular attention given to items displaying significant location-level purchasing imbalances. Regular monitoring of purchasing trends will help management identify emerging cost anomalies, investigate underlying causes, and take corrective action before variances become significant.

- Reinforce standardized liquor usage practices across locations to reduce variability in recipe execution. Establishing clearer guidelines for premium ingredients and liquor usage will help ensure consistency with recipe standards and improve alignment between purchasing patterns and operational expectations.
