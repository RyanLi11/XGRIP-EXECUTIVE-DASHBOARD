# **XGRIP Sales and Profit Analytics Dashboard**

![](https://github.com/RyanLi11/XGRIP-EXECUTIVE-DASHBOARD/blob/main/Screenshot%202025-07-18%20165935.png)

---

## **Objective**  
I built an interactive and user-friendly Power BI dashboard for XGRIP, a simulated company that sells mobile phone accessories. The dashboard brings together data from multiple sources, standardizes currencies, and delivers insights on sales, profit, product performance, and returns. The goal was to simplify data analysis and help stakeholders make better business decisions based on real-time insights.

---

## **Action**  

### **Key Features**  
- **Multi-Source Data Integration:** Connected and cleaned data from PostgreSQL, MySQL, Excel, CSV, and PDF files to create a unified model.  
- **Currency Standardization:** Converted all regional currencies to USD for consistent, cross-country analysis.
- **Profitability Analysis:** Calculated key metrics by incorporating COGS, discounts, and quantities for accurate profit analysis.  
- **Interactive Visuals:** Designed dynamic dashboards with slicers, custom panes, drillthroughs, and bookmarks for better user navigation.
- **Scheduled Data Refresh:**  Scheduled daily data updates using Power BI Gateway to ensure up-to-date reporting.
- **Advanced DAX Calculations:** Created KPIs for revenue, profit margin, and YoY sales growth.  
- **Row-Level Security (RLS):** Implemented role-based access controls to protect sensitive data and limit visibility by user level.


### **Technology Used**  
- **Data Sources:** PostgreSQL, MySQL, Excel, CSV, PDF.  
- **Tools:** Power BI, Power Query, DAX.  
- **Gateway:** Power BI Gateway for scheduled refresh.



### **Execution Steps**  

1. **Data Integration:** Connected to multiple data sources including PostgreSQL, MySQL, Excel, CSV, and PDFs to build a complete and unified dataset.
2. **Data Standardization:** Applied currency conversion logic to standardize local currencies into USD for consistent global reporting. 
3. **Data Modeling:** Defined relationships between tables, merged product data, and built calculated columns to support profitability analysis.
4. **Dashboard Design:** Created interactive, multi-page dashboards using donut charts, bar charts, maps, slicers, and buttons for a better user experience.
5. **Advanced Calculations:** Used DAX to develop dynamic KPIs like revenue, profit margin, and YoY growth for deep performance tracking.
6. **Automation & Security:** Set up scheduled data refresh with Power BI Gateway and implemented Row-Level Security (RLS) to control data access by user role.

---

## **Impact**  

The dashboard delivers clear, actionable insights into sales, profits, and product performance, helping the XGRIP team make more informed, data-driven decisions. With a clean, interactive interface and automated data refresh, it significantly improves reporting efficiency and enhances the overall decision-making process.


---

## **Key Learnings**  
- **Multi-Source Integration:** Strengthened my ability to combine data from PostgreSQL, MySQL, Excel, CSV, and PDFs into a single, clean data model.  
- **Advanced Data Transformation:**  Improved Power Query skills for cleaning, merging, and shaping complex datasets.
- **DAX Proficiency:** Gained experience writing advanced DAX measures for KPIs like YoY growth, profit margin, and revenue. 
- **Interactive Design:**  Learned to create intuitive, user-friendly dashboards with slicers, drillthroughs, and bookmarks.  
- **Automation & Security:** Set up automated data refresh via Power BI Gateway and implemented Row-Level Security (RLS) for secure access control.

---

## **Final Output**  

### **Screenshots**  
**Sales Overview Dashboard**  
![Sales Overview](https://github.com/RyanLi11/XGRIP-EXECUTIVE-DASHBOARD/blob/main/Snapshot%20of%20Dashboard%20Light%20Mode.png)

**Product Analysis Dashboard**  
![Product Analysis](https://github.com/RyanLi11/XGRIP-EXECUTIVE-DASHBOARD/blob/main/Products%20page.png)

**Map Analysis Dashboard**  
![Map Analysis](https://github.com/RyanLi11/XGRIP-EXECUTIVE-DASHBOARD/blob/main/Map%20page.png)  

**Light and Dark Mode Example**  
![Light and Dark Mode](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/light%20dashboard.png)

---

## **Access the Dashboard**  
Explore the live dashboard here: **[Link to Online Reports Page](https://app.powerbi.com/view?r=eyJrIjoiMDE5N2U2ZTAtZDA2Zi00MDgyLWI0MjMtZTlkYjc1ODc0MWVkIiwidCI6ImY3NDM5NmYzLTgwMTUtNGI3NC1iNDY4LWNkYTA0NTEzZDg0YyJ9)**  

---

## **How to Use the Dashboard**  
1. Use slicers to filter data by region, product category, or time period.  
2. Navigate between pages using bookmarks and buttons.  
3. Drillthrough on products or returns charts for detailed insights.  
4. Toggle between light and dark modes for your viewing preference.
