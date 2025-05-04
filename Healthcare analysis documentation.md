
# Healthcare analysis

In this project, I analyzed Healthcare dataset of 55,500 unique patients across 10 major hospitals in the united states. The dataset captures a broad view of hospital admissions, medical conditions, medications, insurance providers, and treatment costs. This project aims to uncover insights that can drive better healthcare decisions, optimize cost and improve patient outcomes.






## Authors

- [Dziedzoave wisdom](https://github.com/DZIEDZOAVE-WISDOM)

Email: wdziedzoave1@st.knust.edu.gh


## Data source:
Onyx Data DataDNA


## Data cleaning and preparation;
#### Tool used: Microsoft Excel

1. I downloaded the dataset from the website and saved it on my onedrive.
2. I loaded the dataset through power query in Excel.
3. on power querry, I checked for duplicates as well as empty cells.
4. I also made sure all the columns are in their correct data type
5. after ensuring that the data is consistent for analysis, I loaded and applied the steps taken to continue the analysis in excel.
6. I inserted the data into a table to ensure efficient calculations with table formulas to avoid errors.
7. I created a new column to group the ages of the patients into Adolescent/youth, Adults, child and Elderly for the purpose of analysis.
8. I also created a column for the number of days that the patients stayed in the various hospitals(discharged date minus date of admission).
9. I used flash fill to extract the years in the "date of admission" to create a column seperately for years.
10. for data summarization and analysis, the main tool used was "pivot tables".




![samples of pivot tables created](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-analysis/blob/main/Pivot%20tables.png)


## Dashboards


![Main dashboard](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-analysis/blob/main/H_Dashboard%201.png)



![Second dashboard](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-analysis/blob/main/H_Dashboard%202.png)


![Third dashboard](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-analysis/blob/main/H_Dashboard%203.png)
## INSIGHTS
1. Adults (25-64 years) accounted for the highest proportion of admissions (59%), followed by the Elderly (65+ years) at 31%, with other age groups making up the remaining 10%.
2. A+ was the most prevalent blood group (35%), followed by O+ (25%) and O- (15%), with all other groups representing 5% each.
3. Treatment costs showed minimal variation, with Asthma commanding the highest mean expenditure($25,678) and Arthritis the most economical ($25,298), representing a marginal 1.5% differential
4. Hypertension was associated with the lengthiest hospital stays among all medical conditions, whereas asthma patients required significantly fewer hospitalization hours. The average duration across all patients was 15 days.
5. Patients admitted electively remained hospitalized for significantly longer durations than those admitted through emergency channels
6. Admission types were nearly evenly distributed, with elective cases slightly leading at 34%, while both emergency and urgent admissions accounted for 33% each.
7. Aetna's treatment cost at NewYork-Presbyterian Hospital ($22,366) was significantly the lowest and well below the average($25,539), while Cigna consistently had the highest average treatment costs across all hospitals.
8. The average treatment cost declined from  $25,700 in 2019 to $25,380 in 2024, reflecting a consistent downward trend in healthcare expenses over time.
9. Historically, February has consistently shown the lowest patient admission numbers, while August typically experiences the highest volumes. Additionally, there has been a dramatic reduction in overall admissions, decreasing from 7,387 patients in 2019 to just 3,854 by 2024.
10. Lipitor emerged as the most frequently prescribed medication for all medical conditions, with Ibuprofen ranking second. In contrast, Penicillin showed the lowest prescription rates. Notably, all available medications were utilized in treating every condition category.
11. Females accounted for the majority of admissions (50%), followed by males (40%), while non-binary patients represented the smallest proportion at 10%.
12. The majority of test results were abnormal (55%), while 35% proved inconclusive and only 10% fell within normal parameters.
13. Houston Methodist Hospital accounted for the highest proportion of patient admissions (36.76%), while NewYork-Presbyterian Hospital recorded the lowest (4.21%).
## RECOMMENDATIONS
 ### 1. Optimize Healthcare Resources for the Adult and Elderly Demographics.
Since adults (25–64 years) and the elderly (65+) represent 90% of admissions, healthcare facilities should prioritize:

Resource allocation (staffing, beds, specialized care units) to these age groups.

Implement age-targeted preventive programs, especially for chronic conditions like hypertension, which also drive up hospitalization durations.

Design telehealth or outpatient follow-up strategies for elderly patients to reduce readmissions and improve care continuity.



### 2. Control Costs by Leveraging Low-Cost Providers and Monitoring Prescription Patterns.
Encourage insurance negotiations with low-cost providers like NewYork-Presbyterian Hospital (especially for Aetna-insured patients), and audit Cigna’s high-cost trends to identify inefficiencies.

Conduct a cost-benefit analysis of medication use—since Lipitor and Ibuprofen dominate prescriptions, ensure they're clinically necessary and cost-effective.

Use historical cost trends (a decline from $25,700 to $25,380) to forecast budgets and promote further savings through preventive care.



### 3.  Align Staffing and Resource Planning with Seasonal and Admission Type Trends.
Since August sees the highest admissions and February the lowest, adjust staffing, inventory, and operational capacity seasonally to reduce bottlenecks.

Because elective admissions last longer despite being slightly more frequent, explore early discharge planning, pre-admission screening, and care pathway standardization to reduce length of stay without compromising care.

Enhance hospital efficiency by investing in decision-support tools to better handle emergency and urgent admissions (which still make up 66%).