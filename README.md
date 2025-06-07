## 🔧 Data Cleaning & Transformation

This project focuses on cleaning and transforming job listing data. Key steps include:

- **Removed invalid characters**: Fixed encoding issues like `â€™`, `â€¢`, and others.
- **Cleaned textual clutter**: Removed headers like "Who are we?", question marks, asterisks, and “Thank you” lines.
- **Normalized revenue data**:
  - Removed "(USD)", "/ Non-applicable", and extra spaces.
  - Replaced `"million"` with `"M"` and `"billion"` with `"B"`.
  - Changed `"to"` to a hyphen (`-`) for consistency in ranges.
- **Split salary estimates**: Separated combined salary fields into `Salary Estimate Min` and `Salary Estimate Max` for analysis.
- **Removed -1 values** in the `Competitors` column.
- **Standardized job titles and company descriptions** for better readability.

## 📊 Cleaned Dataset

You can find the cleaned and transformed dataset here:  
[Cleaned_Glassdoor_DS_Postings.xlsx](./Cleaned_Glassdoor_DS_Postings.xlsx)

## 📂 Original Dataset

The original dataset used in this project is publicly available on Kaggle:  
[Data Science Job Posting on Glassdoor - Uncleaned_DS_jobs.csv](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor?select=Uncleaned_DS_jobs.csv)
