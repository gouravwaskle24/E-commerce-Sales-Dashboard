# E-commerce Sales Dashboard using MS Power BI

## Project Overview
This project showcases an interactive **E-commerce Sales Dashboard** built using Microsoft Power BI. The dashboard provides comprehensive insights into sales trends, customer behavior, and product performance by analyzing data from two primary tables: **Details** and **Orders**.

## Key Features
- **Sales Insights:** Visual representation of sales revenue, profit, and product performance.
- **Customer Insights:** Analysis based on customer geography, preferences, and order trends.
- **Time-Based Trends:** Monthly and yearly sales analysis.
- **Payment Mode Distribution:** Evaluation of payment preferences across customer segments.
- **Drill-down Capabilities:** Deeper analysis of sales performance by category and location.

---

## Data Model
### 1. **Details Table**
| Order ID | Amount | Profit | Quantity | Category   | Sub-Category     | PaymentMode  |
|----------|--------|--------|----------|------------|------------------|--------------|
| B-25681  | 1096   | 658    | 7        | Electronics| Electronic Games | COD          |
| B-26055  | 5729   | 64     | 14       | Furniture  | Chairs           | EMI          |
| B-25955  | 2927   | 146    | 8        | Furniture  | Bookcases        | EMI          |
| B-26093  | 2847   | 712    | 8        | Electronics| Printers         | Credit Card  |
| B-25602  | 2617   | 1151   | 4        | Electronics| Phones           | Credit Card  |

### 2. **Orders Table**
| Order ID | Order Date | CustomerName | State         | City    |
|----------|------------|--------------|---------------|---------|
| B-26055  | 10-03-2018 | Harivansh    | Uttar Pradesh | Mathura |
| B-25993  | 03-02-2018 | Madhav       | Delhi         | Delhi   |
| B-25973  | 24-01-2018 | Madan Mohan  | Uttar Pradesh | Mathura |
| B-25923  | 27-12-2018 | Gopal        | Maharashtra   | Mumbai  |
| B-25757  | 21-08-2018 | Vishakha     | Madhya Pradesh| Indore  |

---

## Dashboard Insights
1. **Sales Performance:**
   - Total sales revenue and profit metrics.
   - Top-performing categories like Electronics and Furniture.
   - Sub-category analysis reveals high profits in Phones and Printers.

2. **Customer Analysis:**
   - Majority of customers from states like Uttar Pradesh and Maharashtra.
   - Cities like Mumbai and Mathura show a significant number of orders.
   - Payment preferences indicate a strong inclination towards Credit Card and EMI options.

3. **Time-based Analysis:**
   - Identification of sales peaks during specific months.
   - Seasonal sales trends observed with high orders in Q1 and Q3.

4. **Payment Mode Analysis:**
   - Clear breakdown of payment modes used by customers.
   - COD still has a notable share despite digital payment adoption.

---

## How to Use
1. Open the `.pbix` file in Microsoft Power BI Desktop.
2. Explore interactive visuals and slicers for detailed insights.
3. Use filters to drill down by categories, states, and time periods.

---

## Dashboard Screenshot
![E-commerce Sales Dashboard](dashboard_screenshot.png)

---

## Technologies Used
- **Microsoft Power BI:** Data visualization and dashboard creation.
- **Power Query:** Data transformation and integration.

---

## How to Contribute
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

---

## License
This project is licensed under the MIT License.
