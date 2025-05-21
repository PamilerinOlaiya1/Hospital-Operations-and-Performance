# Hospital-Operations-and-Performance

## Project Overview
This data analysis project examines operational and performance metrics across 10 major U.S. hospitals, focusing on admissions, medical conditions, medications, insurance coverage, and treatment costs. By analyzing patterns
in hospital data, this project aims to uncover valuable insights that can enhance healthcare decision-making, optimize treatment costs, and improve patient outcomes.
Through systematic analysis of a comprehensive dataset covering 55,500 patients, we've identified key trends in healthcare delivery, patient demographics, diagnostic results, and billing patterns that can inform strategic 
decisions in hospital management and healthcare policy.

## Problem Statement
Hospitals generate vast amounts of data related to admissions, medical conditions, medications, insurance providers, and treatment costs. However, without thorough analysis, valuable insights that could enhance healthcare 
decision-making, optimize treatment costs, and improve patient outcomes remain hidden.
There is a need to systematically analyze this data to uncover trends, highlight inefficiencies, and support stakeholders in making informed, data-driven decisions for better healthcare delivery.

## Purpose of the Analysis

- To analyze hospital admissions, medical conditions, medications, insurance providers, and treatment costs across 10 major U.S. hospitals
- To uncover key insights that can inform better healthcare decisions and policies
- To identify patterns and trends that impact patient care quality and hospital operations
- To highlight areas for optimizing treatment costs while maintaining or improving patient outcomes
- To support stakeholders with data-driven insights for strategic decision-making in healthcare management

## Tools Used
I used PowerQuery to clean the data, then i created DAX measures for calculations and also used PowerBI for visualization

## Key Findings
### Summary of Key KPIs
- The dataset contains records from 10 hospitals, with a total patient count of 55,500
- Total billing amount charged by all hospitals amounts to $1.417 billion
- Average billing per patient: $25,539
- Average hospital stay: 15 days per patient

### Overview of Key Findings

1. Patient Population Profile
Our analysis reveals a diverse patient population across the 10 major hospitals. Gender distribution shows a slight female majority (50%) compared to males (40%) and non-binary patients (10%). The age spectrum is
 dominated by middle-aged adults, seniors, and younger adults, with fewer elderly and teenage patients. Blood type analysis indicates A+ as the predominant group, followed by O+ and O-, with other blood types being relatively uncommon.
2. Disease Burden and Treatment Patterns
Chronic conditions dominate the healthcare landscape, with diabetes and hypertension each affecting a quarter of all patients, closely followed by obesity (23%). These three conditions constitute nearly three-quarters of the disease
burden across all hospitals. The remaining patients present with arthritis, cancer, or asthma. This disease profile shapes medication usage patterns, with drugs targeting metabolic and cardiovascular conditions showing the highest prescription
 rates. Middle-aged adults (45-59) bear the heaviest burden of chronic conditions, particularly diabetes and hypertension.
3. Hospital Operations and Financial Patterns
The data reveals significant variation in patient distribution across facilities, with Houston Medical Hospital and Johns Hopkins handling nearly 60% of all patients in the study. Despite these volume differences, average billing remains remarkably consistent across all institutions (approximately $25,000-$25,700 per patient). Medicare emerges as the dominant insurance provider, covering over half of all patients, while United Health Care, Aetna, and Cigna handle the remainder with similar
 billing averages.
4. Diagnostic Outcomes and Quality Indicators
Diagnostic testing results present concerning patterns, with only 10% of all tests yielding normal results. The majority show abnormal (55%) or inconclusive (35%) outcomes, pointing to potential issues in diagnostic accuracy or patient
population health status. Houston Methodist and Johns Hopkins report the highest volumes of both abnormal and inconclusive results, reflecting their larger patient populations. Notably, arthritis stands out as the only condition regularly yielding
 normal test results, while conditions like hypertension, diabetes, and obesity show predominantly abnormal or inconclusive outcomes.

## Key Insights
- Diagnostic Uncertainty: A majority of test results are abnormal (55%) or inconclusive (35%), with only 10% in the normal range, suggesting high prevalence of health concerns and diagnostic uncertainty.
- Hospital-Specific Patterns: Johns Hopkins reported the highest inconclusive test results (9,399), while Houston Methodist recorded the highest abnormal results (11,241).
- Condition-Specific Outcomes: Normal test results were recorded exclusively for Arthritis (5,550 cases), while other conditions showed no normal outcomes.
- Insurance Provider Patterns: Aetna is the only insurance provider collecting below-average billing amounts ($25.43K per patient) and has the lowest patient count (5.6K).
- Hospital Efficiency: New-York Presbyterian, Northwestern, and UCSF Medical Center have relatively low patient volumes (2.3K-2.5K) despite collecting below-average billing amounts ($25.1K-$25.3K).
- Chronic Condition Demographics: Diabetes, hypertension, and obesity occur most frequently among middle-aged adults (45-59) and younger adults (30-44), indicating a concentration of chronic health issues in these demographics.

## Recommendations
1. The high percentage of abnormal (55%) and inconclusive (35%) test results highlights significant diagnostic uncertainty across the system. This calls for standardization of testing protocols, recalibration of lab equipment,
   and enhanced training for clinicians interpreting results. Investing in AI-driven diagnostic tools can help reduce ambiguity, especially in inconclusive cases, while creating a feedback loop for tracking patient outcomes will improve
   future diagnostic accuracy.

2. Johns Hopkins reports the highest number of inconclusive results, while Houston Methodist sees the most abnormal results. These discrepancies warrant internal audits and benchmarking against top-performing hospitals. Collaborative learning
   initiatives between these institutions could identify root causes—whether related to equipment, protocols, or patient populations—and promote best practices.

3. Reassess Testing Criteria for Non-Arthritis Conditions
Only Arthritis shows normal test results, suggesting that other conditions may be over-diagnosed or tested using overly sensitive criteria. Re-evaluating diagnostic thresholds and developing condition-specific follow-up protocols can ensure
more accurate and meaningful results, reducing unnecessary treatments and anxiety for patients.

4. Target Chronic Disease Prevention in Working-Age Adults
Chronic conditions such as diabetes, hypertension, and obesity are most prevalent among adults aged 30–59. This demographic should be the focus of targeted preventive efforts, including workplace wellness programs, community screenings, and digital health tools like telehealth and wearable monitoring. Integrating these services into primary care can support early detection and long-term management.

5. Promote System-Wide Best Practices
Across all areas, there is a need to adopt standardized reporting, enhance transparency in communicating test results to patients, and use data analytics to predict risk and optimize resource allocation. Encouraging policy advocacy for national
 standards in diagnostics and billing can further reduce disparities and improve equity in care delivery.
