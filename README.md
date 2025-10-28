# Global Superstore Project Analysis & Insights

## Project Overview
The **Global Superstore** is an international online retailer that sells Office Supplies, Furniture, and Technology products across 147 countries. The goal of this project is to clean and model the dataset, generate **KPIs and DAX measures, visualize sales, profit, and shipping performance**, and provide data-driven recommendations to improve profitability.

---

## Objectives
- Clean and model the Global Superstore dataset.
- Create DAX measures for key business metrics.
- Visualize sales and profitability across countries, categories, and subcategories.
- Identify key performance drivers and underperforming regions.
- Provide data-driven recommendations for business growth.

---

## Tools & Technologies
|   Step                  |      Tool/Feature Used                                                        |
|------------------------ | ----------------------------------------------------------------------------  |
|   Data Cleaning	        |      Power Query (Remove nulls, fix data types, create derived columns)       |
|   Data Modeling	        |      Star schema — Orders (Fact) + Customers, Products, Region (Dimensions)   |
|   DAX Calculations	     |      SUM, AVERAGE, DIVIDE, CALCULATE, FILTER, RANKX                           |
|   Visualization	        |      Power BI (KPI Cards, Maps, Bar Charts, Line Charts, Tables)              |

---

## Data Cleaning Highlights
- Removed null and duplicate rows in Orders and Customer tables.
- Standardized Country names and set correct data categories for mapping.
- Created calculated columns: Year, Profit Margin, Delivery Days.
- Validated numerical fields (Sales, Profit, Shipping Cost) for outliers.

---

## Key KPIs
| KPI	                   |   DAX Measure  	           |      Description                 |
| ---------------------- | -------------------------- | -------------------------------- |
| Total                  |   Sales	SUM(Sales)	        |   Total revenue generated        |
| Total Profit	          |   SUM(Profit)	             |   Total profit after discounts   |
| Profit Margin	         |   Profit / Sales	          |   Efficiency of sales            |
| Total Orders	          |   DISTINCTCOUNT(Order ID)	 |   Number of unique orders        |
| Average Discount	      |   AVERAGE(Discount)	       |   Average discount per order     |
| Average Shipping Cost	 |   AVERAGE(Shipping Cost)	  |   Logistics efficiency           |

---

## Analysis and Findings
**Top 3 Countries by Profit (2014):**  
 The United States, India, and China generated the highest profit in 2014. Within these countries, top products included Phones (Technology) and Chairs (Furniture). High-profit regions tend to have a strong technology market with low shipping costs.

**U.S. Subcategories with Highest Shipping Cost:**  
 Top 3 subcategories: Tables, Bookcases, and Copiers. These bulky items have higher delivery costs; optimizing logistics or using local suppliers could reduce expenses.

**Nigeria’s Profitability (2014):**  
 Nigeria recorded low profit in 2014 due to high average discounts (~20%) and high shipping costs. This indicates pricing and delivery inefficiencies rather than poor sales volume.

**Least Profitable Subcategory in Southeast Asia:**  
 The Tables subcategory recorded the lowest profitability in Southeast Asia, particularly in Vietnam and Indonesia. Recommendation: review pricing or discontinue bulky furniture lines in those markets.

**Least Profitable U.S. City:**  
 Philadelphia had the lowest average profit (excluding cities with fewer than 10 orders) due to heavy discounting and low sales on large furniture items.

**Most Profitable Subcategory in Australia:**  
 Copiers and Phones generated the highest average profit in Australia, suggesting a strong market for Technology products.

**Most Valuable Customers:**  
 Top 10 customers contributed over 25% of total profit, mainly purchasing Technology and Office Supplies. Implement loyalty and personalized promotions to retain them.

## Overall Insights
|   Area                  |          Insight                             |       Recommendation                         |
| ----------------------- | -------------------------------------------- | -------------------------------------------- |
| Profit Distribution	    |       Concentrated in North America & Asia	  |     Expand strategically to emerging markets |
| Shipping Costs	         |       High for bulky furniture	              |     Optimize routes or local suppliers       |
| Discount Policy	        |       Excessive discounts reduce margin	     |     Implement stricter discount controls     |
| Customer Value	         |      20% of customers drive 80% of profit	   |    Introduce loyalty/referral programs       |
|  Regional Focus	        |       SEA and Africa underperforming	        |     Localize pricing and logistics           |

---

## Key Insights
- **High-profit regions:** North America & Asia (U.S., India, China dominate).  
- **Nigeria:** Low profitability due to high discounts and shipping costs.  
- **Technology category:** Delivers the highest margins globally.  
- **Tables subcategory:** Least profitable, especially in Southeast Asia.  
- **Top 10 customers:** Contribute ~25% of total profit — mostly tech buyers.  

---

## Recommendations
- Reduce discounts in low-performing regions to improve margins.  
- Optimize shipping logistics for bulky products (Furniture).  
- Focus on high-performing categories like **Technology** in profitable regions.  
- Re-evaluate or reprice low-margin subcategories.  
- Localize pricing and shipping strategies by region.  
- Introduce **loyalty programs** for high-value customers.  

---

## Conclusion
The Global Superstore analysis reveals that profitability is **regionally concentrated**, with major opportunities in logistics optimization and customer retention.  
By aligning discount strategy, logistics planning, and customer-focused marketing, the business can achieve **sustainable profit growth** across all markets.

---

## Dashboard Preview
<img width="1453" height="815" alt="Image" src="https://github.com/user-attachments/assets/e0f27d0e-2753-4044-b65c-45d88b42fa7f" />

<img width="1275" height="717" alt="Image" src="https://github.com/user-attachments/assets/d34e51ee-43cc-4d0d-8ee3-354f9c7250a6" />

---

## Author
**Ikeoluwa Ifejowo**  
📍 Nigeria | 💼 IT Support Analyst & Data Analyst  
 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)  

---

## 📢 Acknowledgment
This project was completed as part of the **Data Analyst Bootcamp – Capstone Project** by **DigitaleyDive**.

---

