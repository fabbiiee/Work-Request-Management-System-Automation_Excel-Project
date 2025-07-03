# Work Request Management System Automation Project.

## Overview
This project was developed to improve how internal task requests are submitted, tracked, and fulfilled across multiple departments in a mid-sized organization. The existing manual process led to inconsistent records, delays, and difficulty in tracking performance. I built an Excel-based system that automated the intake, validation, and reporting of work requests using dynamic tables, Power Query, and dashboard visualization.
The result was a fully functional, interactive system that saved administrative time, improved data quality, and empowered managers to make data-driven decisions about workflow and team performance.

## Data Source
The data originated from simulated internal logs submitted by different departments. Each entry included:
•	Point of contact
•	Extension number
•	Request category
•	Department name
•	Key update (status or summary)
•	Optional details
These logs were designed to mimic real-world request handling within business support units like HR, Finance, Operations, and more.
Tools Used:
•	Microsoft Excel (core tool for structure and formulas)
•	Conditional Formatting (to highlight priorities and status)
•	Data Validation (for controlled dropdowns and clean input)
•	Basic Formulas: IF, COUNTIFS, SEARCH, TEXT, etc.

## Data cleaning 
Although the dataset was small, I used Power Query and Excel tools to clean and structure the data. Key steps included standardizing department names, removing blank entries, correcting inconsistent text formats, and applying data validation to reduce input errors. This ensured accurate reporting and a smooth automation flow.
Analysis techniques: Understanding the dataset and the goals of the project will always be the first thing to consider as a data analyst, so that was my first technique. Then, I analyzed the data primarily through the “Category” and “Key Update” columns.
•	Request volumes were counted and compared across categories to identify the most common operational needs.
•	The “Key Update” column was scanned for keywords like Urgent, Critical, or Escalated using Excel’s SEARCH function.
•	These flags were used to classify request urgency and feed into the conditional formatting logic.
This approach allowed the dashboard to surface meaningful trends and highlight action items with minimal manual intervention.

## Visualizations used
The final output was a clean, interactive Excel table with built-in filters and conditional formatting.
Instead of charts, the formatted table served as the primary visual tool, highlighting urgent requests in red and making the data easy to interpret at a glance for majorly non-technical staff.

## Key Insights
Requests flagged with terms like “Urgent” or “Critical” were easily identified using keyword detection, allowing priority items to stand out automatically.
•	The Category and Department columns made it easy to spot which units were making the most requests, helping managers allocate attention where it was needed.
•	The color-coded system (via conditional formatting) enabled quick, non-technical understanding of task priority and status — without needing charts or pivot tables.
•	Having a unified structure for all departments ensured cleaner records and reduced manual follow-up

## Challenges and learnings 
I faced some challenges and learned a lot while working on this project and the problems and learnings were as follows; 
•	Designing a flexible yet robust structure that supports automation while being easy to use was a key challenge.
•	Handling keyword-based urgency detection required careful formula logic to avoid false positives.
•	Learned how to create scalable Power Query steps that refresh without breaking when new categories or departments are added.
•	Gained more experience with conditional formatting logic based on dynamic text and date fields.


## Conclusion
The Work Request Management System Automation Project successfully replaced a manual logging process with a dynamic, semi-automated Excel solution. The system improved tracking, reduced administrative workload, and provided actionable insights for internal operations. It demonstrates the power of Excel and Excel formulas in building lightweight but effective workflow automation tools.
This project is a strong example of how operational efficiency can be improved with well-structured data systems without the need for expensive or complex software.
