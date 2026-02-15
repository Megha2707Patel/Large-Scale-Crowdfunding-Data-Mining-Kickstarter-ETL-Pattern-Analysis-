# 📊 Kickstarter Campaign Data Mining & Analysis

**Python | Selenium | BeautifulSoup | Pandas | NumPy | Matplotlib**

---

## 🚀 Project Overview

This project explores crowdfunding success patterns by mining and analyzing **70,000+ Kickstarter campaigns** using automated web scraping and data analysis techniques.

An end-to-end **ETL (Extract, Transform, Load)** pipeline was built to collect campaign data directly from **Kickstarter**, clean and structure it efficiently, and uncover actionable insights through exploratory data analysis (EDA).

The goal was to understand:

* What makes a Kickstarter campaign successful?
* Which categories perform best?
* How funding goals impact success probability?
* Whether launch timing affects campaign outcomes?

---

## 🛠 Tech Stack

| Category        | Tools Used              |
| --------------- | ----------------------- |
| Programming     | Python                  |
| Web Scraping    | Selenium, BeautifulSoup |
| Data Processing | Pandas, NumPy, Regex    |
| Visualization   | Matplotlib              |
| Development     | Jupyter Notebook        |

---

## 📌 Key Features

### 🧠 Automated ETL Pipeline

* Built a fully automated scraping system using **Selenium** (dynamic rendering) and **BeautifulSoup** (HTML parsing).
* Extracted **70K+ campaign records** with ~95% scraping reliability.
* Implemented delay handling, scrolling automation, and structured DOM extraction.

### ⚙️ Optimized Data Processing

* Cleaned raw text fields using **regex-based transformations**.
* Standardized funding goals, currency formats, and campaign statuses.
* Reduced processing time by ~30% through vectorized Pandas operations.
* Structured the dataset for scalable analysis.

### 📈 Exploratory Data Analysis (EDA)

* Performed category-wise success rate comparisons.
* Analyzed funding goal distributions and their impact on outcomes.
* Studied seasonal launch performance trends.
* Generated clear visualizations using Matplotlib.

---

## 🔍 Key Insights

### 1️⃣ Tech Campaigns Perform Better

Tech-related projects showed a **40% higher success rate** compared to most other categories.

### 2️⃣ Early-Year Advantage

Campaigns launched in early months demonstrated stronger performance trends overall.

### 3️⃣ Optimal Funding Range

Projects with moderate funding goals between **$5K–$50K** had significantly higher success probability.

---

## 📂 Project Structure

```
📁 Kickstarter Campaign Analysis
│
├── Kickstarter_group_combined_code.ipynb
├── README.md
├── kickstarter_url.csv
└── Output_kickstarter_data.csv
```

### 📄 File Descriptions

* **Kickstarter_group_combined_code.ipynb**
  Complete scraping + cleaning + analysis pipeline.

* **kickstarter_url.csv**
  Dataset containing Kickstarter URLs used for scraping.

* **Output_kickstarter_data.csv**
  Cleaned dataset sample (reduced to meet GitHub’s 25MB upload limit).

* **README.md**
  Project documentation and insights summary.

---

## ⚙️ How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/kickstarter-analysis.git
cd kickstarter-analysis
```

### 2️⃣ Install Dependencies

```bash
pip install selenium beautifulsoup4 pandas numpy matplotlib
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:
`Kickstarter_group_combined_code.ipynb`

---

## 📊 Sample Analysis Workflow

1. Scrape campaign URLs
2. Extract metadata:

   * Title
   * Category
   * Funding Goal
   * Amount Raised
   * Launch Date
   * Campaign Status
3. Clean & transform data
4. Perform statistical summaries
5. Visualize trends
6. Interpret results

---

## 📈 Example Visualization Areas

* Success rate by category
* Funding goal distribution
* Monthly launch performance
* Success vs funding goal scatter trends

---

## 💡 Business Value

This project demonstrates:

* Ability to build scalable scraping pipelines
* Strong data cleaning and transformation skills
* Analytical thinking and hypothesis validation
* Insight generation for data-driven decision-making
* Real-world dataset handling at scale (70K+ records)

Such insights can help investors, entrepreneurs, and marketing teams make informed campaign strategy decisions.

---

## 🎯 Skills Demonstrated

* Web automation
* ETL pipeline development
* Data wrangling
* Statistical reasoning
* Data visualization
* Performance optimization
* Large-scale dataset handling

---

## 📬 Future Improvements

* Deploy pipeline using cloud scheduler (AWS / GCP)
* Add advanced statistical modeling
* Implement predictive success classifier
* Build interactive dashboard (Streamlit / Power BI)

---



Just tell me what you need next.
