# Pizza-Analysis

## Table of Contents

- [Data Description](#dataset-description)
- [Content](#content)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Inference Analysis](#inference-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

### Dataset Description(Overview)
A Piza Company  is on a quest to extract pivotal insights from their customer database in other to fast-speed her revenue and to enhance their operations and sales strategies.

### Content
 The dataset comprises 48,620 rows, observations across 12 variables, each illuminating different facets of the company's operations and customer interactions:

- **Pizza_id**: Customer identification number.
- **Order_id**: This column display the Order identification number.
- **Pizza_name_id**: The Costumers Names id
- **Order_date:** Periodical Time Track Record
- **Quantity**: Piza Quantity.
- **Order_time**: Time record.
- **Unit_price**:  Sales price.
- **Pizza_size**:  Sizes of Piza.(“Small Medium, Large”)
- **Pizza_category**: Pizza type
- **Pizza_ingredients**: The ingredients for making pizza"
- **Pizza_name**: Customers name.

### Data Sources 

•	The data source for the analysis is an Excel file from kaggle named "Pizza Dataset 1.xlsx"

### Tools:
 * Excel
 * Pivot Tabl for proper analysis.
 * Excel Dashboard for interactive visualizations

### Data Cleaning
* 1. Null/empty value check to ensure no missing data.
* 2.  Pizza type column was created for proper analysis on “vegetarian and non vegetarian” set of Pizza.
* 3. Duplicate value check: no duplicates found.
* 4. The "Date of purchase" column is been split into Days, Month, and Year of purchase for proper analysis.

### Inference Analysis
  The analysis uses several techniques:
* 1. Line with marker: Analyzes the “Highest peak period”.
* 2. 3-D pie: Analyzes the “Days with the highest numbers of pizza sold.
* 3. 3-D Clustered Column Chart: Review the “Revenue against pizza categories”.
* 4. 3-D line: Analyzed the “order of time count”.
* 5. Clustered bar Chart: Analyzes “The most ordered pizza”.
* 6. 3-D Column: Analyzed “The most popular pizza size”.
* 7. Dough not: Shows “The most popular pizza category”.
* 8. 3-D Clustered column: Shows the “Price range for each pizza”.
* 9. Clustered bar: Analyzes the “Pizza with highest revenue”.
* 10. Clustered column: Show the “Average order value insight”.
* 11.Area: Analyzes the “Pizza category revenue”.
* 12.3-D Clustered column: Shows “The price varies across sales of pizza”.
* 13. Pie of pie: Preference for “Vegetarian and non Vegetarian”.
*14. Bar of pie: “Time and period of sales”.

 
### Findings
* The total revenue is N817,860
* Total count of Vegetarian is 37,805 and Non Vegetarian is 10,815 Analysis stating that Vegetarian is more demanding.
* Large(L) Pizza is more demanded with a value count of 18,526 customers and a total revenue of 375,318 next to Medium(M) which is having a count of 15,385 with a revenue of 249,382 followed by Small(S) having a value count of 14,137 with a total revenue of 178,076 and Extra Large(XL) having a value count of 544 with a total revenue of 14,076 while the least is (XXL) having a value count of 28 and the total revenue is 1,006.
* December is a feast (celebration) period yet the least period of sales.
* “XL,XXL” have an all time low sales.
* The “Five cheese pizza and the Hawaiian pizza” has the highest revenue.
* Between 12pm to 1pm is the highest peak period.
* 12pm to 7pm are the mode hours for sales

### Recommendations
1. **Focus on "XL and XXL" improvements**: There should be a proper investigation on the reason for low sales in “XL” and “XXL” pizza, perhaps a rebrand should be consider, an ad should also be consider, a price discount as well in order to draw customers attention for more patronage.

2. ** Time Discount **: Pizza sales between 9am to 10am and also 10pm to 11pm should consider having a lower price tag in other to attract more sales.
3. **Discount Optimization and Customers Rating**: Understand the relationship between discounts and customer ratings. Test the impact of different discount strategies, potentially optimizing for higher ratings rather than just sales.

### Limitations
1. **Lack of customers feedback data**: Customer feedback would significantly enhance understanding of the rating distributions and offer targeted ways to improve customer satisfaction.

### Conclusion
- The entire sales distribution shows that “XL, XXL” is all time low, a discount price should be consider.
- “XL, XXL” should considers a rebrand.
- Survey on customers satisfaction: information is a critical attribute for decision making and should not be underestimated majorly on “XL and XXL”, a survey should be carry out to understand customers rating and satisfaction.
