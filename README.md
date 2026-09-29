# 📊 Data Jobs Market Analysis | Power BI

![Data Jobs Dashboard Preview](./images/main-dashboard.png)
*(Replace the path above with your actual image filename once uploaded)*

## 📖 Overview
This Power BI project provides an interactive, comprehensive analysis of the 2024 Data Jobs market. It is designed to help data professionals, career switchers, and recruiters understand current hiring trends, salary benchmarks, and the most in-demand skills across various data roles (e.g., Data Analyst, Data Scientist, Data Engineer).

## ✨ Key Features

### 📄 Page 1: Executive Summary Dashboard
*   **High-Level KPIs:** Instant visibility into Total Job Count (479K), Average Yearly Salary ($113K), and Average Hourly Salary ($47.62).
*   **Trend Analysis:** A line chart tracking the trend of job postings throughout 2024.
*   **Top Roles:** A bar chart highlighting the most in-demand job titles (led by Data Engineer and Data Analyst).
*   **Interactive Slicers:** A "Select Job Title" slicer allows users to filter the entire page dynamically.
*   **Salary vs. Hourly Matrix:** A detailed table comparing median and average salaries across roles.

### 🔍 Page 2: Drillthrough Detail View
![Drillthrough Page Preview](./images/drillthrough-page.png)
*(Replace the path above with your drillthrough page screenshot)*

*   **Dynamic Drillthrough:** Users can right-click any job title on Page 1 to drill through to this specific page for deep-dive metrics.
*   **Role-Specific KPIs:** Focuses on a single job title (e.g., Data Scientist) showing exact yearly/hourly rates.
*   **Workplace Insights:** Donut charts displaying the percentage of remote work (WFH), degree requirements, and health insurance offerings.
*   **Global Footprint:** A map visual showing where the top job locations are worldwide.
*   **Platform & Type Analysis:** Breakdown of which platforms (LinkedIn, Indeed, etc.) are posting these jobs and the types of employment (Full-time, Contract, etc.).

## 🛠️ Technical Stack & Skills Demonstrated
*   **Tool:** Microsoft Power BI Desktop
*   **Data Transformation:** Power Query (ETL) used to clean, split, and format raw job posting data.
*   **Data Modeling:** Created a robust data model to support cross-filtering and drillthrough capabilities.
*   **DAX (Data Analysis Expressions):** Utilized for calculating dynamic measures, including:
    *   Median vs. Average Salary calculations.
    *   Dynamic text titles based on drillthrough filters.
    *   Percentage calculations for WFH and Degree metrics.
*   **UI/UX Design:** Implemented a custom, cohesive blue-tone theme. Designed with a "Card" based layout for high readability. Added custom tooltips and clear navigation cues.

## 🧠 Challenges & Learnings
*   **Challenge:** Implementing a seamless drillthrough experience. 
    *   *Learning:* Discovered that standard buttons do not automatically pass slicer context in Power BI. Resolved by utilizing Power BI's native right-click drillthrough functionality, which ensures the correct filter context is passed to the detail page perfectly.
*   **Challenge:** Designing a layout that holds a massive amount of data without looking cluttered.
    *   *Learning:* Utilized rounded container shapes (cards) and a strict color palette to group related metrics visually, improving the overall user experience.
