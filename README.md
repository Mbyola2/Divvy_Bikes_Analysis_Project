# Divvy Bike share Analysis: Understanding Member vs. Casual Riders

![Project Thumbnail/] (Optional: A compelling chart image, e.g., the monthly trend, from your `screenshots/` folder)

## 🎯 Project Overview
This project leverages Divvy BikeShare trip data to conduct a comprehensive analysis of how annual members and casual riders utilize the bike-sharing service differently. The insights aim to inform strategic decisions for optimizing operations, marketing, and converting casuals to members for Divvy BikeShare.

## ❓ Business Question
**"How do members and casual riders use Divvy bikes differently, and what are the key implications for Divvy BikeShare's business strategy?"**

## 📂 Data Source & Tools
* **Data Source:** Divvy BikeShare trip data (CSV files for a full year, e.g., January 2024 - December 2024).
* **Tools Used:**
    * **Microsoft Excel:** For data cleaning, transformation, complex pivot table analysis, and advanced charting.
    * **Microsoft Word:** For the comprehensive project report detailing methodology and findings.
    * **Google Cloud Storage:** Utilized for hosting the large Excel workbook containing raw data and detailed analysis (due to GitHub file size limits).

---

## 💡 Executive Summary & Key Insights

*(This is the most important section for a recruiter. Use bolding, clear language, and embed your most impactful charts as images here. Screenshots (98), (99), (100), (103), (102), (104) provide great material for this.)*

1.  **Members Drive Volume, Casuals Drive Seasonal Peaks:**
    * Members consistently account for **~63%** of all rides, forming the core user base.
    * Casual riders demonstrate extreme seasonality, with usage **surging dramatically in summer months (e.g., July/August)** and dropping significantly in winter.
    * *(Optional: Embed your "Total number of ride length by month" chart here - Screenshot (98).png or (101).png)*

2.  **Distinct Daily Usage Patterns:**
    * **Members** show high, consistent ridership during **weekdays**, indicating commuting or routine use.
    * **Casual riders** exhibit pronounced peaks on **weekends**, suggesting leisure or recreational usage.
    * *(Optional: Embed your "User Types by days of the week" chart here - Screenshot (103).png)*

3.  **Casual Riders Take Longer Trips:**
    * On average, casual riders take significantly **longer trips** compared to members across all days of the week. This points to recreational or exploration-based use.
    * *(Optional: Embed your "Average ride length per weekday" chart here - Screenshot (102).png or (104).png)*

4.  **Rideable Type Preference:**
    * Both user types primarily use classic and electric bikes.
    * However, casual riders show a relatively higher proportion of **electric scooter** usage compared to members, hinting at different preferences for short, effortless trips.
    * *(Optional: Embed your "Users by rideable Type" chart here - Screenshot (99).png)*

---

## 📈 Methodology (Brief Overview)

* **Data Acquisition & Combining:** Loaded 12 monthly CSV files using Excel Power Query. Files were combined and transformed, leveraging consistent column structures.
* **Data Cleaning:** Filtered rows, removed unwanted columns. Specifically addressed negative 'ride length' values by using the absolute value (ABS) function and removing inconsistent records to ensure data integrity.
* **Feature Engineering:** Calculated `ride_length` from start/end times.
* **Analysis:** Utilized Excel's pivot tables and charting features to identify trends, aggregations, and comparisons across user types, time periods (monthly, daily), and rideable types.

---

## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):**
    * Contains all raw data, detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:** [Download Divvy Bike Share Analysis Workbook (.xlsx)](https://docs.google.com/spreadsheets/d/1w5MpDWtkH3bndmDN2HgLajPrI9w2YhJg/edit?usp=sharing&ouid=102853951415568760346&rtpof=true&sd=true)
    * *Note: This file is hosted externally on Google Drive due to GitHub's file size limitations for direct repository uploads, ensuring optimal performance and accessibility.*

* **Comprehensive Project Report (Microsoft Word .docx):**
    * Provides an in-depth discussion of the project scope, detailed methodology, all findings, conclusions, and strategic recommendations.
    * **Access:** [Divvy_Bike_Analysis_Report.docx](Divvy_Bike_Analysis_Report.docx)

* **Project Summary Presentation (Microsoft PowerPoint .pptx):**
    * A concise and visually impactful presentation summarizing the key insights and strategic implications.
    * **Access:** [Divvy_Bike_Key_Findings_Presentation.pptx](Divvy_Bike_Key_Findings_Presentation.pptx)

* **Raw Data (Optional):**
    * If you choose to upload the raw CSVs, link to the folder: [raw_data/](data/)

---

## 🚀 Key Recommendations & Business Implications

*(Extract the most impactful recommendations from your full report here)*

* **Seasonal Marketing:** Implement aggressive campaigns targeting casual riders in spring/summer to convert them to members.
* **Dynamic Fleet Management:** Optimize bike rebalancing and availability based on strong seasonal and daily peaks, especially in recreational areas during summer weekends.
* **Membership Incentives:** Develop compelling offers to encourage casual riders (especially those taking longer trips) to become members.
* **Service Reliability:** Maintain high service quality for consistent member usage year-round, including off-peak seasons.

---

## ✍️ Author
Abiola Adeniyi Adeyemo
https://www.linkedin.com/in/abiola-adeyemo-85031b135
[Your Portfolio/Website Link (Optional)]
