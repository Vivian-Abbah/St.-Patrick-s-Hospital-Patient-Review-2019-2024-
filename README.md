# St.-Patrick-s-Hospital-Patient-Review-2019-2024-
INTRODUCTION

In the heart of healthcare lies a silent but powerful force—data. From patient outcomes to medication efficiency, billing to admissions, each data point tells a story. Between 2019 and 2024, St. Patrick’s Hospital has navigated a complex healthcare landscape shaped by innovation, patient demands, insurance shifts, and unprecedented global health events. But what do the numbers actually say?

This analysis aims to peel back the layers of hospital operations, leveraging data-driven storytelling to uncover what truly drives outcomes, costs, and patient care effectiveness. Using Microsoft Excel for in-depth analysis and visualization, this report presents a comprehensive review of billing patterns, patient demographics, prevalent conditions, insurance providers, and test results over a five-year period.

Whether you are a hospital administrator, policymaker, or health data enthusiast, this report provides actionable insights to enhance healthcare delivery, operational efficiency, and strategic planning.
 
Data Source
The dataset was extracted from St. Patrick’s Hospital’s internal data warehouse, covering the years 2019 to 2024. It reflects records from the hospital’s billing department, patient registration logs, insurance claims, laboratory tests, and physician visit tracking systems.

Data Collection Process
Data was recorded and aggregated through the hospital's Electronic Health Records (EHR) system, billing software, and laboratory information management systems. Cross-verification was performed with insurance claim reports.

Data Structure
Rows: Individual patient transactions or medical events.

Columns: Variables such as medical condition, doctor, medication, admission type, blood type, test results, insurance provider, etc.

Key Features & Their Significance
Medical Conditions: Helps identify disease prevalence and cost burden.

Admission Types & Length of Stay: Reflects urgency and care demand.

Doctors & Patient Counts: Highlights workload distribution.

Billing Data by Condition and Insurer: Provides financial insights.

Test Results & Medication: Links diagnostics to treatments and outcomes.

Data Limitations
Incompleteness: Some test results are marked as “Inconclusive.”

Sampling Bias: The dataset only reflects patients admitted, excluding outpatient services.

Time Lag: Some billing and insurance data may reflect delays due to claim processing cycles.

Cleaning Steps
Removed duplicate patient IDs.

Standardized medication names.

Converted financial fields from text to numerical formats.

Filled missing test results using “Inconclusive” as a neutral value.

Handling Missing Values
For test types or medication info, “Not Applicable” or “Inconclusive” categories were used.

Unmatched billing entries were cross-verified with insurer aggregates.

Data Transformations
Aggregated billing by condition and provider using pivot tables.

Generated new metrics: average admissions per year, average patients per doctor, etc.

Normalized length of stay by admission type.

Data Splitting
Dependent variables: Revenue, test results, patient count.

Independent variables: Medical condition, doctor, insurance provider, blood type, admission type.

Industry Context
This project falls within the Healthcare Analytics sector, focusing on hospital operations and clinical performance insights.

Stakeholders
Hospital management

Insurance liaison teams

Medical staff (Doctors, Nurses, Lab Technicians)

Healthcare policymakers

Industry Value
This data enables:

Optimized resource allocation

Better patient-doctor ratios

Strategic insurance partnerships

Improved treatment protocols

Pre-Analysis: Early Observations
Before diving deep, several compelling trends emerged:

Key Early Trends
Elective admissions dominate all other types.

Arthritis is the most common condition, yet it ranks third in billing, suggesting efficient management or shorter stays.

Lipitor and Ibuprofen are the most frequently administered medications, likely tied to cardiovascular and musculoskeletal conditions.

Correlations Noticed
High revenue correlates with conditions like Diabetes and Obesity—possibly due to chronic treatment requirements.

Patients with blood types A- and A+ appear slightly more common.

Initial Insights
The hospital’s revenue model is heavily dependent on five core conditions and five insurance providers.

There may be disparities in how test results drive medication decisions.

In-Analysis: Deep Dive into the Data
Unconfirmed Patterns
There seems to be a consistent yearly admission rate (~52/year) except a drop in 2023. Was this due to external factors (e.g., pandemics)?

Penicillin is the least used medication among the top five. Could this reflect a shift in prescription trends due to resistance?

Excel Techniques Used
Pivot Tables: For aggregating billing, test results, and patient distribution.

SUMIFS & COUNTIFS: To analyze relationships between doctor and patient counts.

Charts (Bar, Line, Pie): To visualize billing, test results, and trends over time.

Preliminary Recommendations
Reallocate resources toward conditions generating the highest revenue (e.g., Diabetes).

Investigate 2023 admission dip for underlying causes.

Standardize test protocols to reduce “Inconclusive” results.

Post-Analysis & Final Insights
Key Findings
Total revenue over five years: $1.4 Billion+.

Top 3 conditions by billing: Diabetes, Obesity, and Arthritis.

Average admissions per year: 52.

Most used medication: Lipitor.

Top billing insurer: Cigna ($284M).

Comparison with Initial Hypotheses
While Arthritis is the most common condition, it’s not the highest in billing—suggesting effective early intervention.

Blood type distribution was more balanced than initially expected, though A- and A+ slightly lead.

Surprising Observations
Ibuprofen, a relatively inexpensive medication, is among the most used—likely due to high incidence of pain-related conditions.

Elective admissions dominate despite high emergency infrastructure investment.

Data Visualizations & Dashboard Breakdown
Bar Charts: Used to represent billing by condition and provider, patient count per doctor.

Line Chart: Year-over-year admission trend reveals a stable pattern with a dip in 2023.

Pie Charts: Used for test results and admission type distribution.

Dynamic Dashboard: Filters available for:

Medical conditions

Blood types

Doctor names

Visual Highlights
The dashboard clearly shows which doctors are managing the most patients.

Insurance contributions are tightly clustered, emphasizing the need for diversified partnerships.

Recommendations and Observations
Actionable Insights
Focus resources on top 3 billing conditions to maximize financial efficiency.

Expand capacity for elective procedures, as they dominate admissions.

Standardize medication protocols for common conditions to reduce variability.

Negotiate better rates with Blue Cross and UnitedHealthcare, as their contributions are lower than others.

Operational Suggestions
Train more staff on high-use medications like Lipitor and Ibuprofen.

Revisit 2023 admission policy or external impacts to avoid future dips.

Enhance data accuracy in test reporting to reduce inconclusive rates.

Conclusion
The St. Patrick’s Hospital Patient Review (2019–2024) paints a data-rich picture of how a modern healthcare facility operates, adapts, and grows. From the sharp dominance of elective admissions to the consistent reliance on a handful of medications and insurance partners, the data reveals clear patterns that can drive smarter decisions.

Yet, with this clarity comes responsibility—improving test result reliability, managing doctor workload more evenly, and adapting to patient demographics must become strategic priorities. As we close this chapter, the insights gleaned from this analysis serve not just as a retrospective, but as a compass for future care excellence.

References & Appendices
References
St. Patrick’s Hospital Internal EHR System

Hospital Billing System Reports (2019–2024)

Insurance Claim Reports (Cigna, Medicare, Blue Cross, etc.)

Pharmaceutical Usage Logs

Appendices
Appendix A: Pivot Table Formulas

Appendix B: Raw Extracted Dataset Snapshot

Appendix C: Chart Creation Guide in Excel

Appendix D: Admission Policy Memo (2023)![Picture4](https://github.com/user-attachments/assets/d1619570-ff8c-4647-8ce5-a9ddcc3f30e9)

