# Call-Center-Performance-Dashboard

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Result/Findings](#result/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

 This data analysis project focus on evaluating the performance of a call center. It examines key metrics such as call volume, response times, call duration, and customer satisfaction. The analysis helps identify patterns in agent performance, peak call hours, and overall service efficiency. The goal is to optimize operations, improve customer service, and enhance the effectiveness of the call center team.


![Screenshot 2024-05-29 125326](https://github.com/user-attachments/assets/87494461-645c-40aa-b77d-cbe4d582cd01)


### Data Sources

Data was provided online in Excel format. I downloaded the CSV file and imported it into Power BI for cleaning, analysis, and visualization. The data contains a sheet/table called call center with 32,941 rows and 12 columns.

### Tools

- Excel - Cleaning The Data
- Power Bi - Data Analysis and Creating a Report.

### Data Cleaning/Preparation

•	I cleaned the data efficiently and did some transformations with the Power Query Editor of Power BI.

Some of the applied steps included
- Making first row as headers.
- Created new column for date from the payment date which came with time and named: [Date]
- Datatype then changed from 'TEXT' TO 'DATE'.

### Exploratory Data Analysis

 - Show The total call duration in minutes 
 - Show the Total Calls by Day
 - Show the Total Calls by Reason
 - Show the Total Calls by Channel

 - 
![Screenshot 2024-05-29 125645](https://github.com/user-attachments/assets/9b07b472-0347-4f8e-bf21-253d22c0b5cf)

### Data Analysis

Include some dax measures worked with

```Power Bi
Total call duration in hours = [Total call duration in minutes]/60
Total call duration in minutes = SUM('Call Center Files'[Call Duration In Minutes])
Average call duration = AVERAGE('Call Center Files'[Call Duration In Minutes])
```

### Results/Findings

The call center has logged a total of 824,220 minutes (approximately 13,737 hours) of call duration, with an average call time of 25.02 minutes. The response time efficiency stands at 75.26%, reflecting the center’s ability to handle calls promptly while maintaining substantial engagement with customers. These metrics provide valuable insights into overall call handling performance and areas for improvement in response times.

### Recommendations

Based on the analysis, we recommend the following actions :
- Provide additional training for agents to streamline issue resolution.
- Implement FAQs or self-service options for common inquiries to reduce call time
- Introduce automated call-routing systems to reduce customer wait times
- Expand self-service platforms to handle frequent, straightforward issues.
- Address recurring customer pain points to reduce the need for prolonged calls.

### Limitations

The insights depend heavily on the accuracy and completeness of the data collected.
The average call duration may not fully capture the complexity of the issues handled. Some calls might be longer due to the nature of the problem, which could limit the effectiveness of reducing call times without compromising service quality.

### References

1. Call Center Helper: Guides on essential metrics and benchmarks for call center performance.
2. [Call Center Helper - Top 10 Call Center Metrics]


😄

☎️

|Heading1|Heading2|
|--------|--------|
|Content|Content2|
|Excel|Power Bi|
