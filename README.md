# Global_BoxOffice_powerbi_dashboard
# 🎬 Global Box Office Performance Dashboard (Power BI)

## 📌 Project Overview

This project analyzes global movie box office performance from **2020–2024** using **Power BI** to generate actionable business intelligence insights.

The dataset was collected from **Box Office Mojo** using **web scraping techniques**, then transformed and analyzed through **Power Query and DAX** to build an interactive dashboard that reveals revenue trends, film performance segmentation, and market distribution.

The goal of this project was to convert **raw web data into meaningful analytical insights** using modern BI techniques.

---

# 📊 Data Collection (Web Scraping)

The dataset used in this project was gathered from **Box Office Mojo**, one of the most trusted sources for global movie revenue data.

Using **web scraping techniques**, movie performance data was collected for the following years:

• 2020  
• 2021  
• 2022  
• 2023  
• 2024  

The extracted dataset included information such as:

- Movie titles
- Worldwide gross revenue
- Domestic revenue
- International revenue
- Revenue performance brackets

This raw dataset was then imported into **Power BI** for further processing.

---

# 🧹 Data Cleaning & Transformation (Power Query)

After importing the scraped dataset into Power BI, the **Power Query Editor** was used to clean and transform the data.

Key transformation steps included:

• Removing unnecessary columns  
• Replacing null values with suitable values  
• Eliminating duplicate entries  
• Standardizing revenue formats  
• Adding calculated columns for analysis  
• Structuring the dataset for analytical modeling  

These transformations ensured the dataset was **clean, reliable, and optimized for analysis**.

---

# ⚙️ Data Modeling & Calculations (DAX)

To generate analytical insights, multiple **DAX (Data Analysis Expressions)** measures and parameters were created.

Key measures included:

**Total Revenue**

SUM(Worldwide_Gross)

**Average Revenue**

AVERAGE(Worldwide_Gross)

**Domestic Revenue**

SUM(Domestic_Gross)

**International Revenue**

SUM(International_Gross)

Additional parameters and calculated columns were created to support:

• Revenue segmentation analysis  
• Performance grouping  
• Year-based filtering  
• Dynamic dashboard interaction  

These calculations enabled the dashboard to generate **dynamic and real-time insights**.

---

# 🎛 Interactive Dashboard Features

## Year Slicer (2020–2024)

The dashboard includes an interactive **Year slicer** that allows users to filter the analysis by year.

When a year is selected:

• All visualizations update automatically  
• Revenue metrics change dynamically  
• Movie performance insights adjust in real time  

This creates a **fully interactive business intelligence experience**.

---

# 📈 Key Visualizations

## 🎥 Top 10 Movies by Worldwide Gross

A **bar chart visualization** displaying the top-performing movies based on global box office revenue.

This chart helps identify blockbuster films that dominate worldwide revenue.

---

## 📊 Revenue Segmentation by Film Performance

Movies are grouped into revenue performance categories:

• < $100M  
• $100M – $300M  
• $300M – $600M  
• $600M – $1B  
• $1B+

This segmentation allows quick identification of **film performance distribution across revenue tiers**.

---

## 🌍 Revenue Split (Domestic vs International)

A **donut chart visualization** showing the contribution of:

• Domestic Revenue  
• International Revenue  

This helps analyze how much the **global market contributes to movie success**.

---

## 📉 Revenue & Average Trend (2020–2024)

A combined chart visualizing:

• Total box office revenue per year  
• Average movie revenue trends  

This helps identify **industry growth patterns and revenue fluctuations across years**.

---

# 🛠 Tools & Technologies Used

Power BI  
Power Query  
DAX (Data Analysis Expressions)  
Data Visualization  
Web Scraping  
Data Transformation  

---

# 📷 Dashboard Preview
