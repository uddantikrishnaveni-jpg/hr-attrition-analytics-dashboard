# HR Workforce & Attrition Intelligence Dashboard

A Power BI dashboard analyzing employee attrition drivers and workforce composition, built to help HR leadership identify at-risk employee segments and make data-informed retention decisions.

## Business Problem

Employee attrition is costly — replacing an employee typically costs 50-200% of their annual salary in recruiting, onboarding, and lost productivity. This project analyzes an HR dataset of ~1,500 employees to answer:

- Which departments and roles have the highest attrition?
- What working conditions (overtime, travel) correlate with employees leaving?
- Which employee segments are most at risk, and what should HR do about it?

## Dataset

HR Analytics Sample Dataset — ~1,500 employee records including demographics, compensation, job role, satisfaction scores, and attrition status.

## Dashboard Pages

**1. Executive HR Overview**
KPI summary (headcount, attrition rate, average age, average salary, employees lost) plus attrition breakdown by department and job role.

**2. Attrition Deep Dive**
Attrition rate segmented by overtime status, job satisfaction, business travel frequency, and age group — isolating the strongest drivers of employee turnover.

**3. Workforce & Compensation**
Headcount and average salary by department, providing compensation context alongside attrition patterns.

**4. HR Action Center**
Key findings translated into concrete, actionable recommendations for HR leadership.

## Key Findings

- Employees who work overtime show **nearly 3x higher attrition** than those who don't
- Frequent business travelers have the highest attrition rate (**~21%**)
- The HR department has the **highest attrition rate** despite being the smallest team by headcount
- Attrition rises noticeably for employees **aged 50+**
- Job satisfaction alone is **not** a strong standalone predictor of attrition

## Recommendations

- Review overtime policies and workload distribution, especially in high-attrition roles
- Reassess travel requirements or provide additional support for frequent travelers
- Investigate root causes of HR department attrition through targeted exit interviews
- Design retention programs tailored to employees aged 50+

## Tools Used

- **Power BI Desktop** — data modeling, DAX measures, dashboard design
- **DAX** — custom measures for Attrition Rate and rounded averages

## Skills Demonstrated

- KPI design and executive summary reporting
- DAX measure creation (`DIVIDE`, `ROUND`, `AVERAGE`)
- Data segmentation and binning (age groups)
- Root-cause style analysis translated into business recommendations
- Multi-page dashboard storytelling for a non-technical audience

## File

`HR_Attrition_Analytics_Dashboard.pbix`
