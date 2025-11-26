This project is used to analyse elements that affect the underemployement in the UK, and this is a part of my data analysis job at Quilombo UK

First: I extract the columns needed through 2022 and 2021 calandars, understanding society made by the uk househould longtitudial study
Second: Use the main_data_edit.ipynb and sub_data_edit to merge the data of two years, sub_data is used to get immigration status
Third: All the analysis are available on analysis.ipynb file

Background Context
Underemployment refers to situations where individuals are in work, but their employment does not fully match their skills, qualifications, or desired working hours — or does not provide fair or adequate compensation for those skills. It represents a mismatch between potential and actual work use, typically reflecting involuntary rather than chosen circumstances.
There are main forms:
•	Skills underemployment (overqualification): when someone’s education level is higher than what their job requires (for example, a university graduate in a routine or service role).
•	Wage underemployment: The person’s hourly wage is lower than would be expected given their education or occupation level.
These may overlap into a combined/multiple underemployment — when two or more forms occur simultaneously, for instance, a graduate mother working part-time below her skill level may face both.
Underemployment is often invisible in labour statistics, yet it has major effects on mobility, income, and health. Many people remain in mismatched or unstable jobs for years, becoming trapped rather than progressing.

At the same time, not all underemployment is experienced as negative. Some objectively underemployed people might report satisfaction or good well-being — what we refer to as adaptive underemployment (the “Paul Effect”). This helps distinguish between those who feel trapped and harmed by their situation and those who have adapted or found balance despite the mismatch. Recognising this difference is important for understanding how underemployment interacts with health, resilience, and life circumstances.

Our goal is to measure how often people move out of underemployment (upward mobility), fall into it (downward mobility), or remain stuck (stagnation) — and how these patterns differ by gender, migration status, age, or caring responsibilities.
This first phase will start that process by mapping and defining key indicators of underemployment — skills mismatch, hours mismatch, wage mismatch and their combination — and preparing the foundation for future longitudinal analysis.
Datasets and Scope
To start building evidence on mobility within underemployment in the UK using the datasets already available:
•	Understanding Society: Calendar Year Datasets (2020, 2021, 2022)

Scope and population:
Inclusion criteria: Include individuals who are:
•	Working-age individuals (16–64) who are employed or self-employed.
•	Have valid data on education, occupation, hours, and/or pay.
•	Report being in paid work during the reference period.
•	Provide information relevant to underemployment, satisfaction, or well-being.

Exclusion criteria: Exclude individuals who are:
•	Full-time students whose primary status is study (even if working part-time)
•	Retired individuals or those above the statutory retirement age.
•	Workers constrained by external regulations (e.g. visa hour limits) 
•	Part-time workers by choice, who report being satisfied and do not want additional hours.
•	Unpaid family workers or volunteers.
Why this scope?
This scope focuses on the working-age population (16–64) engaged in paid employment, allowing us to capture underemployment as a structural feature of the UK labour market rather than a lifestyle choice or voluntary arrangement.
The selected datasets — Understanding Society, Calendar Year 2020–2022 — cover a critical period that spans the pandemic and its immediate recovery, when underemployment likely increased as working hours were reduced and many skilled workers accepted lower-level or insecure jobs.
Mapping these patterns helps to:
1.	Identify who is affected (by gender, migration status, age, and sector).
2.	Define and test variables and indicators for later longitudinal analysis.
3.	Establish baseline trends for Quilombo’s internal reports, visual outputs, and future publications — including partial or preliminary results.
<img width="468" height="648" alt="image" src="https://github.com/user-attachments/assets/eae0b26c-0a05-4492-adc3-7b6379e2c139" />
