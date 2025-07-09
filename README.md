# Global AI Job Trends Analysis

This project explores global trends in Artificial Intelligence job markets, examining salary patterns, education levels, remote work models, and job durations using a rich AI job listings dataset.


## Objective

To uncover patterns in AI job roles, compensation, work models, and required qualifications across various industries and geographies.


## Dataset

The dataset contains 15,000 job postings with the following fields:

- **Job Details**: job_title, industry, employment_type, experience_level, education_required, required_skills
- **Company Info**: company_location, employee_residence, company_size, company_name
- **Salary & Benefits**: salary_usd, remote_ratio, benefits_score
- **Timeline**: posting_date, application_deadline


## Some Questions Explored

1. Which job titles command the highest and lowest salaries?
2. How does salary vary by industry, experience level, and company size??
3. What education levels typically lead to higher compensation?
4. Which roles commonly require higher degrees (Bachelor’s, Master’s, PhD)?
5. Do remote jobs tend to offer higher or lower salaries?
6. What is the distribution of remote, hybrid, and in-person work models?
7. Does job description length relate to salary, benefits, or seniority?
8. Which positions tend to have postings open longer?


## Visualizations & Insights

- **Horizontal bar charts** of median salaries by job title
- **Grouped bar plots** showing industry vs. experience level impact on pay
- **Box plots** comparing salary distributions across locations and education levels
- **Pie chart** showing work model distribution (Remote, Hybrid, In-person)
- **Heatmaps** revealing correlations between salary, experience, benefits, and job description length
- **Scatter plot** visualizing relationship between experience and salary
- **Duration analysis** of how long job postings remain open across roles and seniority


## Key Findings

- Senior and research-focused roles tend to pay more.
- Education level is important, but not absolute — all levels (Associate to PhD) are represented across roles.
- Remote work is prevalent and may offer competitive compensation.
- Job description length weakly correlates with seniority and salary.
- Job postings for specialized or senior roles tend to remain open longer.


##  Tech Stack

- **Python** (Pandas, NumPy)
- **Data Visualization**: Matplotlib, Seaborn


