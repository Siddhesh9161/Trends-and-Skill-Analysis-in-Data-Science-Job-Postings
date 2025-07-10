
# Trends and Skill Analysis in Data Science Job Postings

## Project Overview

This project analyzes job market trends and in-demand skills for data science roles using real-world job posting data. It is designed to help job seekers and students understand the current hiring landscape through data-driven insights and visualizations.

## Objectives

* Clean and preprocess structured and unstructured job posting data
* Extract technical and soft skills using Natural Language Processing (NLP)
* Identify trends in job titles, companies, locations, and required skills
* Visualize findings using charts, maps, and word clouds

## Tools and Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, spaCy, WordCloud
* **Environment:** Jupyter Notebook
* **Version Control:** Git, GitHub

## Folder Structure

```
├── data/
│   ├── job_postings.csv
│   ├── job_skills.csv
│   ├── job_summary.csv
├── output/
│   ├── cleaned_dataset.csv
│   ├── top_job_titles_bar_chart.png
│   ├── top_companies_bar_chart.png
│   ├── top_cities_bar.png
│   ├── top_countries_map.png
│   ├── skill_wordcloud.png
│   ├── top_skills_bar.png
│   ├── skill_by_level_grouped_bar.png
│   ├── company_skill_demand_chart.png
├── notebooks/
│   └── skill_trend_analysis.ipynb
├── report/
│   └── final_project_report.pdf
├── README.md
```

## Key Insights

* **Top Skills:** Python, SQL, Machine Learning, AWS, Communication
* **Top Job Titles:** Data Scientist, Data Analyst, Data Engineer
* **Top Hiring Companies:** Amazon, Accenture, Deloitte, Google
* **Top Locations:** USA, India, Canada
* **Skill Trends by Job Level:**

  * Entry-Level: Python, SQL, Excel
  * Mid-Level: Python, SQL, Tableau, AWS
  * Senior-Level: Big Data, Cloud, Machine Learning

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/data-science-job-trends.git
   cd data-science-job-trends
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook notebooks/skill_trend_analysis.ipynb
   ```

## Data Source

This dataset was provided during the **AI & Data Science Internship Assignment** at **GennieSphere** and contains 12,000+ real-world job postings in the data domain.

## Author

**Siddhesh Wagh**
MCA Student | AI & Data Science Internship assignment
GennieSphere

## License

This project is open for educational and non-commercial use.

---


