
# 📊 Bellabeat Case Study — Google Data Analytics Capstone

This project was completed as part of the **Google Data Analytics Professional Certificate**. The goal is to analyze Fitbit smart device usage data and provide insights and strategic recommendations to **Bellabeat**, a high-tech company that manufactures health-focused smart products for women.

## 🚀 Project Objectives

- Understand daily activity patterns, sleep behavior, and heart rate trends among users
- Identify opportunities for Bellabeat to enhance app engagement and health tracking
- Showcase real-world data cleaning, analysis, and visualization using R

## 🗃️ Dataset

- Sourced from: [FitBit Fitness Tracker Data on Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)
- Includes data from 30 Fitbit users over 31 days (March-April 2016)
- Files used:
  - `dailyActivity_merged.csv`
  - `sleepDay_merged.csv`
  - `heartrate_seconds_merged.csv`

## 🛠️ Tools & Libraries

- **R**, **RStudio**
- `tidyverse`, `lubridate`, `ggplot2`
- **R Markdown** for full analysis and report

## 📂 Files Included

- `Bellabeat_Case_Study_Analysis.Rmd` — Reproducible R Markdown analysis
- `Bellabeat_Case_Study_Final_Report.docx` — Written business report with recommendations
- `Bellabeat_Visual_Dashboard.html` — HTML dashboard with all plots
- `merged_data.RData` — Cleaned dataset used in analysis

## 📈 Key Insights

- Average steps per day: **9,891**
- Most active days: **Saturday and Thursday**
- Positive correlation between **steps and calories burned**
- Sleep efficiency is consistent; longer sleep ≠ higher activity
- Heart rate increases on more active days, but trends vary

# 📊 Sample Visualizations

<img width="363" alt="image" src="https://github.com/user-attachments/assets/5bc93586-6985-4c2b-b49d-05ff806e709f" />
<img width="379" alt="image" src="https://github.com/user-attachments/assets/5515167d-a0c3-4b09-9ffa-40ebd9dfa72b" />
<img width="362" alt="image" src="https://github.com/user-attachments/assets/dec29b42-c3d4-4edb-a05d-35374f36792d" />
<img width="371" alt="image" src="https://github.com/user-attachments/assets/b0d39e71-e325-46f7-9cf9-d9980293de65" />
<img width="395" alt="image" src="https://github.com/user-attachments/assets/5e7ce05d-8796-4488-ae93-f3cf07481186" />

## 💡 Recommendations

- Promote daily step goals and challenges in the Bellabeat app
- Introduce smart sleep insights based on consistency
- Personalize workout suggestions using heart rate trends
- Encourage reflection with weekly summaries and comparisons

## 📌 How to Reproduce

1. Clone this repo or download the `.Rmd` file
2. Place the original CSVs in your working directory
3. Run the full R Markdown or load `merged_data.RData`
4. Knit the Rmd to HTML or PDF

```r
install.packages(c("tidyverse", "lubridate", "ggplot2", "gridExtra"))
load("merged_data.RData")
rmarkdown::render("Bellabeat_Case_Study_Analysis.Rmd")
```

---

📬 **Let’s connect!** If you're reviewing this project on GitHub or Kaggle, feel free to leave feedback or suggestions.
