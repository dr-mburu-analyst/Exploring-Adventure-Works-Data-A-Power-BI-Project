# Power-BI-Reports

## Project Title: Adventure Works 

### Project Description

- In this project I had the opportunity to work with Adventure Works dataset. Adventure Works is a bike manufacturer and seller.
- The project involves creating a Power BI dashboard to analyze various aspects of the business, including sales, revenue, profit, customer behavior, product performance, and returns.
- The dashboard aims to provide actionable insights to support decision-making processes.

#### Loading Data

I imported raw data in form of .cvs format and loaded it directly in the PowerBI. A total of 8 files were imported, each occupying their own table.

#### Data Cleaning

After loading the data into Power BI, I performed the follwoing data cleaning steps:
- Removed duplicates
- Handled missing values
- Standardized data formats


#### Data Modelling

After loading and cleaning up the data, I created data models by establishing relationships among the tables. One-to-many relationships
  were very prevalent among the tables, such as:
  - **Customers to Sales**: One customer can have many sale transactions.
  - **Products to Sales**: One product can appear in many sales transactions.
  - **Sales to Returns**: One sales transaction can have multiple returns.
    
 Below is a screenshot of the model view.
  
  ![Adventure Works Data Model](images/Adventure_Works_Data_Model.png)
  
### Key Visualizations

#### Executive Dashboard: 
- This is the major dashboard that houses the company's KPI's and metric that are crucial for decision-making. Executives can quickly assess the overall
  health of the company and identify areas that need attention or improvement.
- The dashboard dispalys visuals including charts and graphs for Trending Revenue, Orders among other top selling products.
  
  Below is a screenshot of the Executive Dashboard.

![Adventure Works Executive Dashboard](images/Adventure%20Works%20Executive%20Dashboard.png)

#### Map Dashboard
- The map provides a visual representation of where customers are located globally. It has interactive features where you can zoom in/out, filtering
  by specific criteria eg sales volume by region.
  
 Below is a screenshot of the Map Dashboard.
 
 ![Adventure_Works_Map](images/Adventure_Works_Map.png)


#### Product Detail Dashboard
- The product detail provides a visual representation of how different products interact with each other in terms of revenue generation,
   orders, profitability, and returns.

 Below is a screenshot of the Product Detail Dashboard.

![Adventure_Works Product Detail](images/Adventure_Works%20Product%20Detail.png)


#### Customer Detail Dashboard
- The Customer detail dashboard breaks down customers by demographics, seasonal influences, and top 100 customer insights.
- Through different charts and graphs, it provides key finding and insights into revenue generation, customer behaviour, making it informative for stakeholders.

  Below is a screenshot of the Customer Detail Dashboard.

![Adventure_Works Customer Detail](images/Adventure_Works%20Customer%20Detail.png)

#### Decomposition Tree Dashboard
- The Decomposition Tree Dashboard presented here breaks down the total orders into disticnt categories inclusing accessories, bikes, and clothing. Each
  category further branches out to provide a detailed breakdown of sub-categories and their respective contributions to total orders.
- The viual offers insights into product category performance, revealing which catgories drive the highest number of orders and how they compare  within their
  respective sub-categories.

Below is a screenshot of the Decomposition Tree Dashboard.

![Adventure_Works Decomposition Tree ](images/Adventure_Works%20Decomposition%20Tree.png)


#### Q&A Dashboard
- The graph displays the trend of total orders across multiple years. It provides a clear visualization of how orders have evolved over time,
  highlighting any trends or patterns that may be significant for analysis or decision-making.
- A slicer is integrated into the dashboard, allowing users to dynamically filter data by category name.
- A user can use the slicer to select a specific category name (e.g., accessories, bikes, clothing) to view its corresponding total orders on the graph.

 Below is a screenshot of the Q&A Dashboard.

![Adventure_Works Q&A](images/Adventure_Works%20Q%26A.png)


#### Conclusion
This Power BI project has been instrumental in enhancing my data analysis and visualization skills. Through this project, I gained proficiency in:

- Data Cleaning and Preparation: Efficiently loading, cleaning, and preparing data for analysis.
- Data Modeling: Establishing relationships between tables and understanding the prevalence of one-to-many relationships.
- Interactive Visualizations: Creating dynamic dashboards with visualizations such as decomposition trees, line charts, bar charts, slicers among others to filter and analyze data effectively
- Customer Insights: Leveraging demographic breakdowns and customer segmentation to uncover valuable insights and trends.
- Q&A Functionality: Utilizing the Q&A feature to enable interactive and user-friendly data exploration.
- Advanced Analytics: Applying advanced calculations and visual calcs to derive meaningful insights from the data.
- DAX (Data Analysis Expressions): Using DAX for creating calculated columns, measures, and custom calculations to perform complex data analysis within Power BI.

These skills have equipped me with the capability to build comprehensive and insightful Power BI dashboards, enhancing my ability to support data-driven decision-making processes.



















  

