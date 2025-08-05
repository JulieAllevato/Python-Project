# **FoodHub Delivery Service Analysis**

-----

### **Project Overview**

This project presents a comprehensive data analysis of orders from a fictional food delivery service, "FoodHub." The primary goal is to leverage Python for data exploration and analysis to answer key business questions related to customer behavior, restaurant performance, and delivery logistics. This project demonstrates skills in data cleaning, exploratory data analysis (EDA), and data visualization to provide actionable insights for improving service and customer satisfaction.

-----

### **Key Questions Addressed**

The analysis was designed to answer a series of business questions, including:

  - What is the overall demand for FoodHub's services, and how does it vary by time of day, day of the week, or month?
  - What are the most popular cuisines and restaurants?
  - How does delivery time impact customer ratings?
  - What are the key metrics that can be used to measure the company's operational efficiency?

-----

### **Data Source**

The dataset used for this analysis is `foodhub_order.csv`, which contains detailed information on individual orders, including order ID, customer details, restaurant information, order timings, and delivery ratings.

-----

### **Methodology & Tools**

The project follows a rigorous data analysis workflow centered around Python:

1.  **Data Cleaning & Preprocessing:** The raw data was cleaned and prepared using **Python** with the **pandas** library. This involved handling missing values, correcting data types, and creating new features for analysis (e.g., `delivery_time`).
2.  **Exploratory Data Analysis (EDA):** The prepared data was analyzed to identify trends, patterns, and relationships between variables.
3.  **Data Visualization:** Visualizations were created using **Matplotlib** and **Seaborn** to communicate key findings effectively.
4.  **Reporting:** The entire analysis process is documented in a Jupyter Notebook (`Allevato_ProjectNotebook.ipynb`), which includes code, outputs, and narrative explanations.

**Tools Used:**

  - **Python:** For all data cleaning, analysis, and visualization.
  - **Pandas:** For data manipulation and analysis.
  - **Matplotlib & Seaborn:** For creating professional-grade visualizations.
  - **Jupyter Notebook:** For documenting the end-to-end analysis process.

-----

### **Key Findings & Visualizations**
The analysis resulted in several key findings, presented in the project notebook. Some of the core insights include:

**Order Trends:** A clear pattern of order volume was identified, with peak days of the week showing the highest demand.

<img width="577" height="548" alt="image" src="https://github.com/user-attachments/assets/41a03549-877c-4738-bbec-232235ed2558" />

**Rating Correlation:** A strong relationship was found between delivery time and customer satisfaction. The analysis shows that weekday deliveries take longer than weekend deliveries.

<img width="356" height="388" alt="image" src="https://github.com/user-attachments/assets/c67b1377-a803-4b73-a8a8-5077701152b0" />

**Restaurant Performance:** The analysis identified the top five most popular cuisines (American, Japanese, Italian, Chinese, and Mexican) and the top-performing restaurants.

<img width="459" height="556" alt="image" src="https://github.com/user-attachments/assets/4f4e579d-2381-4842-bcc4-0fbca86b754f" />
<img width="704" height="341" alt="image" src="https://github.com/user-attachments/assets/0434de4b-2aef-49a2-b032-cab67b49aeb3" />

-----

### **Conclusions & Recommendations**

**Conclusions:**

  * Weekdays account for only **29%** of all orders, and delivery times are approximately **6 minutes longer** compared to weekends. This suggests that the longer delivery times on weekdays may be a deterrent for customers.
  * Customer satisfaction is highly correlated with delivery time.

**Recommendations:**

  * Create a dynamic pricing model to offer a 15% discount on top-5 cuisines during weekday peak hours (11am-1pm) to shift demand, potentially increasing weekday revenue by 8%.
    * FoodHub could bring in more revenue if there were more orders placed on the weekdays.
    * Offer promotions and discounts on the top five popular cuisine types (American, Japanese, Italian, Chinese, and Mexican) specifically during weekdays to incentivize more customer purchases and increase overall order volume.
  * Investigate and optimize the logistics process to reduce the longer delivery times on weekdays, as this could directly improve customer satisfaction and retention.
