# Superstore Sales Data Analysis

## 📊 Project Overview

This project presents a comprehensive exploratory and descriptive analysis of Superstore sales data to uncover key revenue drivers, customer behavior patterns, geographic performance metrics, product profitability, and temporal sales trends. Through systematic data analysis and visualization, this project transforms raw transactional data into actionable business intelligence that directly informs strategic decision-making.

The analysis integrates multiple analytical dimensions, including customer segmentation, product category performance, geographic analysis, shipping preference evaluation, and time series trend analysis to provide a holistic view of business operations.

---

## 🎯 Business Problem

Despite having extensive transactional data, Superstore lacked a clear, data-driven understanding of what drives sales performance and customer value across different business dimensions. The organization faced critical challenges in:

- **Customer Intelligence**: Identifying which customer segments generate the most revenue and demonstrate the highest lifetime value
- **Product Strategy**: Understanding which products and categories contribute most significantly to overall sales performance
- **Geographic Optimization**: Determining regions and cities with the highest commercial potential for resource allocation
- **Temporal Patterns**: Recognizing sales seasonality and trends to support demand forecasting and operational planning

Without these insights, the business risked inefficient resource allocation, suboptimal inventory planning, missed revenue opportunities, and poor anticipation of seasonal demand fluctuations.

---

## 📁 Dataset Description

The analysis utilizes a comprehensive Superstore sales dataset containing **9,994 transactional records** across **21 variables**, covering orders from 2014 to 2017.

### Key Dataset Features:

**Customer Dimensions**
- Customer ID, Name, Segment (Consumer, Corporate, Home Office)
- Geographic information (Country, State, City, Postal Code, Region)

**Product Dimensions**
- Product ID, Name, Category, Sub-Category
- 3 main categories: Furniture, Office Supplies, Technology
- 17 distinct sub-categories

**Transaction Metrics**
- Sales revenue, Quantity, Discount, Profit
- Order and Ship dates
- Shipping modes (Standard Class, Second Class, First Class, Same Day)

**Data Quality**
- No missing values detected
- No duplicate records identified
- Clean dataset ready for analysis

---

## 🔬 Methodology and Analytical Approach

The project follows a structured analytical framework:

### 1. Data Preprocessing
- Data quality assessment (missing values, duplicates)
- Data type conversion and validation
- Feature engineering (shipping lead time, temporal features)

### 2. Exploratory Data Analysis (EDA)
Systematic investigation across six key dimensions:

**Customer Analysis**
- Segmentation by customer type
- Revenue contribution analysis
- Repeat purchase behavior and CLTV inference
- High-value customer identification

**Product Performance**
- Category and sub-category sales assessment
- Top and bottom performer identification
- Product mix analysis

**Geographic Analysis**
- State and city-level performance metrics
- Regional sales concentration
- Market penetration assessment

**Shipping Operations**
- Shipping mode preference analysis
- Lead time evaluation
- Profitability impact by shipping method

**Time Series Analysis**
- Yearly, quarterly, and monthly trend decomposition
- Seasonality detection
- Growth pattern identification

**Executive Visualization**
- Multi-dimensional treemaps and sunburst charts
- Hierarchical data representation

### 3. Statistical Techniques
- Aggregation and grouping operations
- Descriptive statistics
- Trend analysis and pattern recognition

---

## 💡 Key Insights and Findings

### Customer Insights

**Segment Distribution**
- **Consumer segment**: 51.9% of customer base, contributing **50.6% of total revenue** ($1.16M)
- **Corporate segment**: 30.2% of customers, generating **30.8% of revenue** ($706K)
- **Home Office segment**: 17.8% of customers, accounting for **18.7% of revenue** ($430K)

**Customer Loyalty**
- Top repeat customer: William Brown (Consumer) with 37 orders
- High-frequency customers predominantly from the Consumer segment
- Concentration of customer lifetime value in a small group of repeat buyers

**High-Value Customers**
- Sean Miller (Home Office): Top spender with $25,043 in total purchases
- Top 12 customers contribute disproportionately to overall revenue
- Mix of all three segments in the top spender list, indicating diverse high-value opportunities

### Product Performance

**Category Analysis**
- **Technology**: Leading category with **36.5% of sales** ($836K), driven by Phones ($330K) and Copiers ($150K)
- **Furniture**: Second largest with **32.4% of sales** ($742K), led by Chairs ($328K) and Tables ($207K)
- **Office Supplies**: **31.4% of sales** ($719K), with Storage ($224K) and Binders ($203K) as top sub-categories

**Sub-Category Winners**
1. Phones: $330,007 (highest revenue generator)
2. Chairs: $328,449
3. Storage: $223,844
4. Tables: $206,966
5. Binders: $203,413

**Underperformers**
- Fasteners: Only $3,024 in sales
- Labels: $12,486
- Envelopes: $16,476

### Geographic Performance

**Top States by Sales**
1. **California**: $457,688 (19.9% of total sales)
2. **New York**: $310,876 (13.5%)
3. **Texas**: $170,188 (7.4%)
4. **Washington**: $138,641 (6.0%)
5. **Pennsylvania**: $116,512 (5.1%)

**Top Cities**
1. **New York City**: $256,368 with 915 customers
2. **Los Angeles**: $175,851 with 747 customers
3. **Seattle**: $119,541 with 428 customers

**Regional Distribution**
- **West region**: Highest sales volume, driven by California
- **East region**: Strong performance from New York and Pennsylvania
- **Central and South regions**: Significant growth opportunities

### Shipping Operations

**Mode Preference**
- **Standard Class**: 59.7% of all shipments (most cost-effective)
- **Second Class**: 19.5%
- **First Class**: 15.4%
- **Same Day**: 5.4% (premium option)

**Operational Trade-offs**
- Standard Class offers the best balance of speed and profitability
- Same-day shipping has tighter profit distributions but lower margins
- Regional disparities in lead times suggest fulfillment inefficiencies in the South and Central regions

### Temporal Trends

**Yearly Growth**
- **2014**: $484,247 (baseline)
- **2015**: $470,533 (slight dip)
- **2016**: $609,206 (29% growth)
- **2017**: $733,215 (20% growth, highest year)
- **Overall trend**: Strong upward trajectory with 51% growth from 2014 to 2017

**Seasonality Patterns**
- **Q4 dominance**: Accounts for 38% of 2017 annual sales
- **November peak**: $118,448 (highest monthly sales in 2017)
- **December**: $83,829 (holiday season strength)
- Clear seasonal pattern with year-end demand surge

---

## 📈 Visualizations

### Customer Segmentation

![Customer Distribution](images/percentage_distr_of_customer_type.png)
*Distribution of customers across Consumer, Corporate, and Home Office segments. The consumer segment represents the majority of the customer base.*

![Sales by Segment](images/sales_by_customer_type.png)
*Total sales contribution by customer segment. The consumer segment generates over 50% of the total revenue.*

### Product Performance

![Sales by Sub-Category](images/sales_by_subcategory.png)
*Horizontal bar chart showing sales performance across all product sub-categories. Phones and Chairs emerge as clear revenue leaders.*

![Sales by Main Category](images/sales_by_main_product_category.png)
*Proportional representation of sales across three main product categories: Technology, Furniture, and Office Supplies.*

![Multi-Dimensional Sales Analysis](images/sales_by_multiple_dimensions.png)
*Comprehensive view of sales across Segment, Region, Category, and Sub-Category dimensions.*

### Geographic Analysis

![Sales by State](images/total_sales_by_state.png)
*Total sales by U.S. state. California and New York dominate the market with significant margins.*

![Top 10 Cities](images/top_10_cities_by_sales.png)
*Top 10 cities ranked by total sales revenue. Urban centers drive the majority of sales.*

![Regional Sales](images/total_sales_by_region.png)
*Sales performance across four U.S. regions: West, East, Central, and South.*

![Choropleth Map](images/us_sales_choropleth.png)
*Geographic heatmap showing sales intensity across U.S. states. Darker shades indicate higher sales concentrations.*

### Shipping Analysis

![Shipping Mode Distribution](images/shipping_mode_distribution.png)
*Customer preference for shipping modes. Standard Class dominates, accounting for nearly 60% of all shipments.*

![Shipping Lead Time](images/avg_shipping_lead_time.png)
*Average delivery lead time by shipping mode. Clear trade-off between speed and cost.*

![Profit by Shipping Mode](images/Profit_by_shipping_mode.png)
*Profit distribution across shipping modes. Shows variability and outliers in profitability.*

![Shipping by Segment](images/shipping_mode_usage_by_cust_segment.png)
*Shipping mode preferences vary by customer segment, informing operational strategies.*

![Regional Shipping Performance](images/reg_shipping_lead_time_by_mode.png)
*Regional differences in shipping lead times reveal fulfillment inefficiencies in certain areas.*

### Time Series Analysis

![Yearly Sales Trend](images/yearly_sales_trend.png)
*Year-over-year sales performance from 2014-2017. Strong upward growth trajectory.*

![Quarterly Sales 2017](images/quarterly_sales_trend.png)
*2017 quarterly sales showing steady growth with Q4 peak.*

![Monthly Sales 2017](images/monthly_sales_trend.png)
*Month-by-month sales breakdown for 2017. November shows exceptional performance driven by holiday demand.*

### Executive Visualizations

![Treemap](images/sales_treemap.png)
*Interactive treemap showing hierarchical sales distribution across Category, Shipping Mode, and Sub-Category.*

![Sunburst Chart](images/sales_sunburst.png)
*Nested sunburst visualization providing an intuitive view of sales hierarchy by category and sub-category.*

---

## 🛠️ Tools and Technologies

### Programming & Analysis
- **Python 3.x**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing

### Visualization Libraries
- **Matplotlib**: Static plotting and charts
- **Seaborn**: Statistical data visualization
- **Plotly**: Interactive visualizations (choropleth maps, treemaps, sunburst charts)

### Development Environment
- **Jupyter Notebook**: Interactive analysis and documentation
- **Git**: Version control

### Key Python Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
```

---

## 🎯 Actionable Business Recommendations

### 1. Prioritize Consumer Segment Marketing
**Action**: Allocate 60% of the marketing budget to the Consumer segment initiatives
- Develop targeted retention programs for high-frequency buyers
- Create personalized email campaigns for the top 100 consumers
- Implement loyalty rewards program with tiered benefits

**Expected Impact**: 15-20% increase in Consumer segment repeat purchase rate

### 2. Double Down on High-Performing Products
**Action**: Optimize inventory and promotion for the Technology category
- Increase Phones inventory by 25% ahead of Q4
- Create bundled offers combining Phones with Accessories
- Expand the Chairs product line with premium options
- Negotiate better vendor terms for the top 5 sub-categories

**Expected Impact**: $150K+ additional revenue in high-margin products

### 3. Geographic Sales Optimization
**Action**: Implement tiered geographic strategy
- **Tier 1 Markets** (CA, NY, TX): Increase sales team presence and marketing spend
- **Tier 2 Markets** (WA, PA, FL): Pilot new customer acquisition campaigns
- **Growth Markets** (Central/South regions): Explore partnership opportunities and local marketing

**Expected Impact**: 10% market share increase in Tier 2 markets

### 4. Seasonal Planning and Forecasting
**Action**: Develop comprehensive Q4 readiness program
- Pre-position inventory by September based on November/December historical demand
- Hire seasonal staff 6 weeks before peak period
- Launch promotional campaigns in early October
- Increase warehouse capacity in top-performing states

**Expected Impact**: Capture an additional 5-8% of seasonal demand without stockouts

### 5. Customer Retention Strategies for High-Value Accounts
**Action**: Launch VIP customer program
- Identify and segment the top 200 customers (by revenue and frequency)
- Assign dedicated account managers to the top 50 customers
- Offer exclusive early access to new products
- Provide priority shipping at standard rates
- Implement quarterly business reviews with Corporate segment clients

**Expected Impact**: 25% increase in customer lifetime value for VIP segment

### 6. Shipping Cost Optimization
**Action**: Implement an intelligent shipping strategy
- Maintain Standard Class as the default for orders under $100
- Auto-upgrade to faster shipping for orders over $500
- Negotiate regional carrier contracts to reduce Central/South region lead times
- Test free shipping threshold promotions

**Expected Impact**: 3-5% reduction in shipping costs while maintaining customer satisfaction

### 7. Product Portfolio Optimization
**Action**: Address underperforming sub-categories
- Phase out or reposition Fasteners, Labels, and Envelopes
- Redirect marketing resources to high-performers
- Conduct market research on potential new product additions in the Technology category

**Expected Impact**: Improved inventory turnover and capital efficiency

---

## ⚠️ Limitations and Future Work

### Current Limitations

**Data Scope**
- Analysis limited to 2014-2017 data; current market conditions may differ
- Single geographic market (United States) limits global applicability
- No customer demographic data (age, income, company size) for deeper segmentation

**Analytical Constraints**
- Customer lifetime value inferred from purchase frequency, not predictive modeling
- Profit analysis doesn't account for overhead costs or a full P&L structure
- No competitive market analysis or external market factors

**Methodological**
- Descriptive analysis only; no predictive modeling implemented
- Correlation vs. causation not established
- Limited A/B testing or experimental validation

### Future Work Recommendations

**Advanced Analytics**
1. **Predictive Modeling**
   - Develop a customer churn prediction model
   - Build sales forecasting model using time series methods (ARIMA, Prophet)
   - Implement product recommendation engine

2. **Customer Lifetime Value (CLTV) Modeling**
   - Calculate actual CLTV using probabilistic models
   - Segment customers by predicted lifetime value
   - Develop retention strategies by CLTV tier

3. **Price Optimization**
   - Analyze discount elasticity and optimal pricing
   - Implement dynamic pricing strategies
   - Evaluate promotional effectiveness

**Enhanced Segmentation**
- RFM (Recency, Frequency, Monetary) analysis
- Behavioral clustering using machine learning
- Cohort analysis for customer retention trends

**Operational Efficiency**
- Supply chain optimization modeling
- Inventory forecasting by product and region
- Warehouse location optimization analysis

**Real-Time Capabilities**
- Develop an interactive dashboard for live monitoring
- Implement automated reporting pipeline
- Create an alert system for anomaly detection

**External Data Integration**
- Incorporate competitor pricing data
- Add economic indicators for demand forecasting
- Include social media sentiment analysis

---

## 📝 Project Structure

```
superstore-sales-analysis/
│
├── data/
│   └── Superstore_Sales.csv
│
├── notebooks/
│   └── superstore_sales_analysis_notebook.ipynb
│
├── images/
│   ├── customer_distribution_pie.png
│   ├── sales_by_segment_bar.png
│   ├── sales_subcategory_horizontal.png
│   └── [additional visualization files]
│
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.7+
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### Running the Analysis
```bash
# Clone the repository
git clone https://github.com/GogoHarry/superstore-sales-analysis.git

# Navigate to project directory
cd superstore-sales-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/superstore_sales_analysis_notebook.ipynb
```

---

## 👤 Author

**Gogo Harrison**
- GitHub: [GogoHarry](https://github.com/GogoHarry)
- LinkedIn: [Gogo Harrison](https://linkedin.com/in/gogo-harrison)
- Email: gogoharrison66@gmail.com

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Dataset source: Superstore Sales Dataset
- Inspiration from retail analytics best practices
- Python data science community for excellent libraries and documentation

---

**Last Updated**: January 2026

*For questions, feedback, or collaboration opportunities, please open an issue or reach out directly.*
