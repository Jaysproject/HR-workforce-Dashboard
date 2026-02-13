# HR-workforce-Dashboard
Project Analysis Workforce Analytics & Attrition Insights Dashboard

An end-to-end Power BI Workforce Analytics & Attrition Insights Dashboard was developed for this project in order to give HR and business executives dependable, understandable information about hiring practices, employee attrition, and workforce composition. Strategic workforce planning, talent management, and retention decision-making were all intended to be supported by the dashboard.

Sources and Structure of Data

Three main datasets employee master data, new hire and transfer data, and termination recordsextracted from an HR system served as the foundation for the analysis. Every dataset had a unique analytical function. While the datasets for new hires and terminations recorded workforce movement events, the employee master data represented the current workforce snapshot. It was essential to keep these datasets distinct in order to prevent double counting and guarantee accurate reporting.

Data Transformation and Cleaning

In order to comply with corporate reporting requirements, the data was standardised and verified using Power Query. This involved handling missing or inconsistent values, renaming columns for business clarity, promoting headers, and fixing data types. System identifiers and titles that are readable by humans were clearly distinguished from duplicate or unclear fields, like multiple position columns. To facilitate tenure and seniority analysis, calculated fields were developed, such as Years of Service and Job Level groupings.

Limitations in data quality were handled with extra care. For instance, assumptions regarding promotions or lateral moves were purposefully avoided because internal employee movements were not consistently classified in the source data. Rather, the dashboard ensures analytical integrity by transparently reflecting only what the data can consistently support.

KPI Development and Business Logic

Workforce analytics were supported by the implementation of key business logic. Using uniform HR definitions, termination reasons were divided into two categories: voluntary and involuntary exits, allowing for insightful attrition analysis. Reusable DAX measures were used to create core KPIs like headcount, average age, average years of service, new hires, termination count, and turnover rate, guaranteeing uniformity across visuals and filters.

The Data Modelling Method

Using employee identifiers, a star-schema data model was put into place, connecting the hiring and termination event tables to the employee master table. While keeping a distinct division between workforce events and workforce state, this structure permitted time-based analysis. Controlled filter direction was used in the design of relationships to prevent ambiguity and performance problems.

Dashboard Layout and Perspectives

The finished dashboard was divided into sections that made sense. Visual representations of workforce composition shed light on the distribution of workers among organisational units, subgroups, and employee groups. While attrition analysis finds trends, exit patterns, and roles with a higher risk of attrition, hiring activity visuals show the inflow of external talent over time. Executive-friendly layout and chart titles make it possible to quickly understand insights without the need for technical interpretation.

Value of the Business

Stakeholders can evaluate the health of the workforce, spot possible retention issues, and comprehend hiring reliance on outside talent thanks to the dashboard. Additionally, it draws attention to data quality issues, bolstering conversations about better workforce data collection and HR process enhancement.
