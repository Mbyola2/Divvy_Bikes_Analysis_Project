## Divvy Bike share Analysis: Understanding Member vs. Casual Riders

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


1.  ** Who takes the most frequent trips?! [image](https://github.com/user-attachments/assets/948267f5-de9c-4bd2-a12d-265c1e6b39f0)
    * Members consistently account for 3,708,910 rides (~63%** of all rides) forming the core user base.
    * Casual riders account for ~2,151,658 rides (approximately ~37% of total rides).


 2. **Which rideable type is the most preferred? ![image](https://github.com/user-attachments/assets/77f77d13-72a3-4696-a27a-a46b98fe3a46)
    * Both user types primarily use classic and electric bikes.
    * However, casual riders show a relatively higher proportion of **electric scooter** usage compared to members, hinting at different preferences for short, effortless trips.   

3. **Which months have the highest number of cycling trips?![image](https://github.com/user-attachments/assets/ed51aa42-23b6-49ad-a292-d7c6a70a64dc)
   *Usage peaks in summer (July-August) and drops significantly in winter, suggesting recreational or tourist by casual riders.
   *whereas member riders members have a more consistent year-round usage, with higher baseline ridership during winter months, indicating commuting.

4. **Which month has the highest length of cycling trips?![image](https://github.com/user-attachments/assets/372004fb-103a-455a-a08b-e38ab949507d)
   *Casual Users:Strong seasonal pattern, peaking in summer (July-August) with significantly lower usage in winter, suggesting recreational use.
   *Member Riders: Also peaks in summer, but maintains substantial usage year-round, indicating commuting-focused behavior.

5.  **What are the most cycling popular days?
    * Members** show high, consistent ridership during **weekdays**, indicating commuting or routine use.
    * Casual riders** exhibit pronounced peaks on **weekends**, suggesting leisure or recreational usage.

6.  **What are the most longest Average Length ride?
   *Casual riders generally take significantly longer trips than member riders. 
---

## 📈 Methodology (Brief Overview)

* **Data Acquisition & Combining:** Loaded 12 monthly CSV files using Excel Power Query. Files were combined and transformed, leveraging consistent column structures.
* **Data Cleaning:** Filtered rows, removed unwanted columns. Specifically addressed negative 'ride length' values by using the absolute value (ABS) function and removing inconsistent records to ensure data integrity.
* **Feature Engineering:** Calculated `ride_length` from start/end times.
* **Analysis:** Utilized Excel's pivot tables and charting features to identify trends, aggregations, and comparisons across user types, time periods (monthly, daily), and rideable types.

---
## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):**
    * Contains all detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:**(https://docs.google.com/spreadsheets/d/1w5MpDWtkH3bndmDN2HgLajPrI9w2YhJg/edit?usp=sharing&ouid=102853951415568760346&rtpof=true&sd=true) < [Download Divvy Bike Share Analysis Workbook (.xlsx)]
    * *Note: This file is hosted externally on Google Drive due to GitHub's file size limitations for direct repository uploads, ensuring optimal performance and accessibility.*

* **Comprehensive Project Report (Microsoft Word .pdf):**
    * Provides an in-depth discussion of the project scope, detailed methodology, all findings, conclusions, and strategic recommendations.
    * **Access:** (Divvy_Bike_Analysis_Report.pdf)[Divvy_Bike_Analysis_Report.pdf]

* **Project Summary Presentation (Microsoft PowerPoint .pptx):**
    * A concise and visually impactful presentation summarizing the key insights and strategic implications.
    * **Access:** (Divvy_Bike_Key_Findings_Presentation.pptx) [Divvy_Bike_Key_Findings_Presentation.pptx]

* **Raw Data (Optional):**
  *The raw CSVs for January2024 to December2024, link to the folder can be access here: https://divvy-tripdata.s3.amazonaws.com/index.html
---
## 🚀 Key Recommendations & Business Implications


* **Seasonal Marketing:** Implement aggressive campaigns targeting casual riders in spring/summer to convert them to members.
* **Dynamic Fleet Management:** Optimize bike rebalancing and availability based on strong seasonal and daily peaks, especially in recreational areas during summer weekends.
* **Membership Incentives:** Develop compelling offers to encourage casual riders (especially those taking longer trips) to become members.
* **Service Reliability:** Maintain high service quality for consistent member usage year-round, including off-peak seasons.

---

## ✍️ Author
Abiola Adeniyi Adeyemo
[https://www.linkedin.com/in/abiola-adeyemo-85031b135]

