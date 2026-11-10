# Manufacturing Quality Analysis

## Project Overview
This project analyzes manufacturing production quality performance using Excel and Power BI. The objective is to identify defect patterns, evaluate rework outcomes, examine scrap rates, and highlight areas that require quality improvement.

The analysis covers 10,000 production events across different material grades, plants, production lines, and shifts.

## Tools & Technologies
- Microsoft Excel – Data preparation and exploratory analysis
- Power BI – Data visualization and interactive dashboard
- DAX – KPI and performance metric calculations

## Key Business Questions
1. Which defect types occur most frequently?
2. Which defect types have the highest scrap rates?
3. How do production outcomes differ between reworked and non-reworked events?
4. Which material grades, plants, and shifts show higher failure rates?
5. Which production segments require further investigation?

## Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of manufacturing quality performance.

![Executive Overview](01_Executive_Overview.png)

### 2. Defect Analysis
Examines defect frequency, pass/fail outcomes, rework performance, and scrap rates across defect categories.

![Defect Analysis](02_Defect_Analysis.png)

### 3. No Recorded Defect Analysis
Examines production events where no defect was recorded, including pass/fail outcomes and rework patterns.

![No Recorded Defect](03_No_Recorded_Defect.png)
## Key Findings

### 1. Defect Frequency vs. Scrap Severity
- Dimension recorded the highest number of defect events (332).
- Scratch recorded the highest scrap rate (19.03%), followed by Crack (18.65%).
- The most frequent defect type does not necessarily have the highest scrap rate.

### 2. Rework Performance
- Reworked defect events achieved a pass rate of 72.19%.
- Non-reworked defect events achieved a pass rate of 53.18%.
- This represents a difference of 19.01 percentage points.

The results show an association between rework and better pass outcomes, although they do not establish causation.

### 3. Production Quality Patterns
- Grade C recorded the highest failure rate among material grades (32.25%).
- Plant 1 recorded the highest failure rate among plants (32.27%).
- Night Shift recorded the highest failure rate among shifts (35.07%).

### 4. Detailed Investigation
Further analysis of Grade C at Plant 1 during Night Shift revealed:
- Failure rate: 56.67% (17 out of 30 defect events).
- Contamination contributed the highest scrap count (3 events).
- Finish recorded the highest scrap rate (50%, based on 2 out of 4 events).

The small sample size should be considered when interpreting these results.

## Business Recommendations
1. Investigate contamination issues through reviews of machine cleanliness, material handling, and inspection procedures.
2. Evaluate rework procedures and post-rework inspection effectiveness.
3. Strengthen scrap prevention and monitor defect frequency and severity across production segments.
4. Continue monitoring quality performance by material grade, plant, production line, and shift.

## Data Limitation
The `No Recorded Defect` category represents production events where no defect was recorded in the dataset. It does not necessarily confirm that no underlying quality issue existed.

## Project Files
- Power BI dashboard (`.pbix`)
- Cleaned dataset (`.csv`)
- Dashboard screenshots

## Conclusion
This analysis highlights the importance of evaluating both defect frequency and severity when improving manufacturing quality. The findings can help management prioritise quality investigations, review rework practices, and strengthen scrap prevention efforts.
