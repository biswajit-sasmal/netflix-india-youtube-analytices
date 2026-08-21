# 🎬 Netflix India YouTube Channel Analytics

> **Data Analytics Project | AtliQ Technologies Virtual Internship – 2**

An end-to-end exploratory data analysis project focused on the **Netflix India YouTube channel**, designed to identify the factors and content patterns associated with video performance and convert those findings into actionable content-strategy insights.

---
<p align="center">
  <img src="https://gifdb.com/images/high/netflix-intro-498-x-278-gif-g0ezmnxq43bx7vum.gif" alt="Netflix Intro Animation" width="650">
</p>

## 📌 Project Overview

The project analyzes Netflix India's YouTube video metadata and performance metrics to answer a set of research questions around:

- 👀 Video views and engagement
- 💬 Comments and audience interaction
- ⏱️ Video duration
- 🏷️ Tags and keywords
- 📅 Publishing day and frequency
- 📝 Title length and title keywords
- 🎯 Content themes and topics
- ⭐ High-performing videos

The analysis was performed using **Python and Pandas**, with visualizations created to communicate the major findings.

---

## 🎯 Project Objective

**Identify the key factors driving YouTube video performance on Netflix India's channel and translate the findings into actionable content-strategy recommendations.**

---

## 🔬 Research Questions

The analysis addresses the following research questions:

1. Does video duration influence views and comments?
2. Is there a relationship between views and comments?
3. Does tag count influence video views?
4. Does the publishing day or time influence engagement?
5. Which video is the most popular, and why did it perform well?
6. Does title length influence views?
7. What is the overall distribution of video views?
8. Are certain topics or themes consistently performing better?
9. Are there videos without tags that still perform well?
10. What is the channel's video publishing frequency?
11. Which keywords are used most frequently in tags?
12. Which keyword is used most frequently in YouTube titles?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| 🐍 **Python** | Data analysis and EDA |
| 🐼 **Pandas** | Data cleaning, transformation and analysis |
| 📊 **Matplotlib** | Data visualization |
| 📓 **Jupyter Notebook** | Analysis workflow |
| 📑 **CSV** | Input and processed datasets |
| 💻 **Git & GitHub** | Version control and project documentation |
| 🎞️ **PowerPoint** | Presentation of business insights |

---

## 📂 Project Structure

```text
Netflix_india_input_file/
│
├── 📁 data cleaning/
│   └── Data Cleaning Script.ipynb
│
├── 📁 raw files/
│   ├── Metadata.txt
│   ├── netflix_india_yt_data.csv
│   └── youtube_research_questions.pdf
│
├── 📁 processed files/
│   ├── netflix_india_yt_data.csv
│   ├── video_tags_list.csv
│   └── video_title_keyword.csv
│
├── 📁 research analysis solutions/
│   ├── AD-HOC Business Questions.ipynb
│   └── EDA & Research Analysis.ipynb
│
├── 📁 screenshots/
│   ├── Video_title_length_views_count_bar_chart.png
│   ├── comment_count_and_video_duration_scatter_plot.png
│   ├── video_duration_and_comment_count_bar_chart.png
│   ├── video_publishing_weekday_and_views_count_bar_chart.png
│   ├── video_tags_and_views_count_bar_chart.png
│   ├── video_tags_count_and_view_count_scatter_plot.png
│   ├── video_views_distribution_histogram_plot.png
│   ├── view_count_and_comment_count_scatter_plot.png
│   ├── view_count_and_video_duration_bar_chart.png
│   ├── view_count_and_video_duration_scatter_plot.png
│   └── weekday_wise_video_publishing_frequency_bar_chart.png
│
└── 📁 presentation/
    └── Netflix India Youtube Channel Video Performance Insights.pptx
```

---

## 🔄 Analysis Workflow

```text
📥 Raw YouTube Data
        ↓
🧹 Data Cleaning
        ↓
🔧 Data Transformation
        ↓
🔎 Exploratory Data Analysis
        ↓
📊 Research Question Analysis
        ↓
💡 Business Insights
        ↓
🎯 Content Strategy Recommendations
        ↓
📑 Final Presentation
```

---

## 📊 Key Analysis Areas

### 👀 Video Performance
Analyzed views, comments and other performance metrics to understand how videos perform across the channel.

### ⏱️ Video Duration
Examined whether video length is associated with views and comment activity.

### 💬 Views & Comments
Studied the relationship between video reach and audience interaction.

### 🏷️ Tags & Keywords
Analyzed tag counts and frequently used keywords to understand their relationship with video performance and discoverability.

### 📅 Publishing Strategy
Analyzed publishing weekdays, publishing frequency and performance patterns across the publishing schedule.

### 📝 Title Analysis
Investigated title length and the most frequently used keywords in YouTube titles.

### 🎯 Content Themes
Compared performance across different content themes to identify topics that consistently perform better.

### ⭐ Top-Performing Content
Identified the most popular video and examined the characteristics that may have contributed to its strong performance.

---

## 📈 Visual Analysis

The repository contains visualizations covering:

- 📊 View distribution
- 🔗 Views vs. comments
- ⏱️ Duration vs. views
- 💬 Duration vs. comments
- 🏷️ Tags vs. views
- 📈 Tag count vs. views
- 📅 Publishing weekday vs. views
- 📅 Publishing frequency by weekday
- 📝 Title length vs. views

These charts support the statistical and exploratory analysis performed in the notebooks.

---

## 📓 Notebooks

### 🧹 Data Cleaning Script
**`data cleaning/Data Cleaning Script.ipynb`**

Contains the data-preparation workflow used to clean and prepare the YouTube dataset for analysis.

### 🔎 EDA & Research Analysis
**`research analysis solutions/EDA & Research Analysis.ipynb`**

Contains the primary exploratory analysis and solutions to the defined research questions.

### 💡 AD-HOC Business Questions
**`research analysis solutions/AD-HOC Business Questions.ipynb`**

Contains additional business-oriented analysis beyond the core research questions.

---

## 📁 Data Assets

### Raw Files
The `raw files` directory contains the original input dataset, metadata and research-question document.

### Processed Files
The `processed files` directory contains analysis-ready datasets and derived files:

- `netflix_india_yt_data.csv`
- `video_tags_list.csv`
- `video_title_keyword.csv`

---

## 📑 Presentation

The final business-insights presentation is available in:

**`presentation/Netflix India Youtube Channel Video Performance Insights.pptx`**

The presentation converts the analytical findings into a concise business story covering channel performance, content patterns, key findings and recommendations.

---

## 💡 Business Value

This analysis is intended to help a social-media/content analytics team understand:

- Which content characteristics are associated with stronger performance
- How audience engagement relates to video reach
- Whether publishing patterns matter
- How titles, tags and topics are used across the channel
- Which content patterns can inform future YouTube strategy

> **Important:** The analysis identifies patterns and relationships in the available dataset. These findings should not automatically be interpreted as causal relationships.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/netflix-india-youtube-analytics.git
cd netflix-india-youtube-analytics
```

### 2️⃣ Install required libraries

```bash
pip install pandas matplotlib jupyter
```

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4️⃣ Run the notebooks

Recommended order:

```text
1. Data Cleaning Script.ipynb
2. EDA & Research Analysis.ipynb
3. AD-HOC Business Questions.ipynb
```

---

## 📌 Project Deliverables

| Deliverable | Location |
|---|---|
| 🧹 Data Cleaning | `data cleaning/` |
| 📊 Processed Dataset | `processed files/` |
| 🔎 Research Analysis | `research analysis solutions/` |
| 📈 Visualizations | `screenshots/` |
| 📑 Business Presentation | `presentation/` |
| 📋 Research Questions | `raw files/` |

---
## 🎥 Video Presentation

A concise video walkthrough of the project is available below, covering the **project objective, data analysis approach, key findings, and business insights** derived from the Netflix India YouTube channel analysis.

> 🎬 **Project Presentation Video:** *Add your YouTube / Google Drive / Loom presentation link here*

---
## 🙏 Acknowledgement

Special thanks to the **Codebasics entire team** for providing this valuable virtual internship opportunity and for creating a practical environment to apply data analytics skills to a real-world business problem.

I would also like to sincerely acknowledge **Dhaval Patel** and **Hemanand Vadivel** for their guidance, teaching, and support throughout this virtual internship task.

Thank you for the opportunity to learn, analyze, and build this project. 🙏
