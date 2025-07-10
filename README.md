# 🎮 Video Game Sales Insights & Visualization

This project was developed as part of a Data Visualization & Storytelling course and aims to provide meaningful business insights from historical video game sales data. To view the whole dashboard go on to [Tableau Public](https://public.tableau.com/app/profile/jaya.chandra.kadiveti/viz/VideoGamesSalesAnalysis_17518890328660/DeveloperDashboard)

Two primary audiences were targeted:
1. **Game Publishers** looking to optimize their genre strategy for sales
2. **Game Developers** exploring in-demand genre-platform combinations for career planning

---

## 🧰 Tools Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft%20Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft%20PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![CSV](https://img.shields.io/badge/CSV%20Data%20Wrangling-217346?style=for-the-badge&logo=files&logoColor=white)
![Storytelling](https://img.shields.io/badge/Data%20Storytelling-BE7C4D?style=for-the-badge&logo=noun-project&logoColor=white)

---

## 📊 Dataset
The dataset [vgsales.csv](data/vgsales.csv) contains over 16,000 records and includes:
- Game titles, release year, platform, genre
- Regional sales (NA, EU, JP, Other)
- Global sales

---

## 🧹 Data Cleaning Summary (Python)

- Removed duplicates and null `Year` values.
- Standardized data types and fixed year outliers.
- Applied log transformation and IQR filtering.
- Explored genre/platform/publisher performance by region.

---

## 📈 Dashboards Built

### 1. 📊 Publisher Dashboard
- 📆 Global sales trend by year
  
  <img width="767" height="338" alt="Yearly sales line chart" src="https://github.com/user-attachments/assets/07324362-4c51-4408-bbc3-44962fed56ac" />

- 🌍 Region-wise revenue (Donut Chart)
  
  <img width="489" height="312" alt="Region donut chart" src="https://github.com/user-attachments/assets/46db50c7-60d1-438a-8f25-563a597deac2" />

- 🏆 Top and bottom publishers
  
  <img width="706" height="319" alt="Top vs Bottom competitors bar chart" src="https://github.com/user-attachments/assets/7a9604b8-50b5-4d42-b0e0-0d22042bd536" />

- 🧩 Genre tornado chart (Sales vs Count)
  
  <img width="550" height="324" alt="Genre count vs sales chart" src="https://github.com/user-attachments/assets/b3c8082f-a70a-4818-8244-669016a437b9" />

- 🔍 Competitor breakdown
  
   <img width="706" height="319" alt="Top vs Bottom competitors bar chart" src="https://github.com/user-attachments/assets/472cefd9-8520-437f-9cab-ac27ae39c948" />

### 2. 🧠 Developer Dashboard
- 📦 Platform sales and game count (Tornado Chart)

  <img width="378" height="340" alt="Platform count vs sales Tornado Chart" src="https://github.com/user-attachments/assets/35635572-2647-4794-a943-d4bbea0afa66" />

- 🎯 Genre spread using Box Plot

  <img width="876" height="347" alt="Genre Box Plot" src="https://github.com/user-attachments/assets/e6c27bd5-ef3a-4ec4-8832-5493f4cf026b" />

- 🌐 Regional genre heatmap (with embedded bar charts)

  <img width="874" height="319" alt="Region vs Genre Heatmap" src="https://github.com/user-attachments/assets/4e762ef7-87c7-4cf9-a811-6245561e991d" />

- 💬 Platform popularity (Bubble Chart)

  <img width="364" height="373" alt="Platforms bubble chart" src="https://github.com/user-attachments/assets/a14be377-5c0c-4ab0-9c99-360a4d95a1b4" />


---

## 🗂️ Final Outputs

- 📊 [Publisher_Insights_Presentation.pptx](presentations/Publisher_Final_Presentation.pptm)
- 🧠 [Developer_Insights_Presentation.pptx](presentations/Developer_Final_Presentation.pptm)
- 📁 Tableau Dashboards [Tableau Public](https://public.tableau.com/app/profile/jaya.chandra.kadiveti/viz/VideoGamesSalesAnalysis_17518890328660/DeveloperDashboard)
- 📄 [Final Cleaned Dataset](data/vg_sales_Final.csv)

---

## 💡 Key Business Insights

### For Publishers
- NA and EU dominate the market in sales volume.
- Action, Sports, and Shooter genres lead in profitability.
- Nintendo, EA, and Activision dominate publisher rankings.

### For Developers
- Platform games show low risk and consistent performance.
- PS2, X360, and PS3 lead in platform sales.
- Developers should pitch to top publishers and prioritize dominant platforms.

---

## 📁 Folder Structure

```
video-game-sales-insights-viz/
├── data/
│   └── vgsales.csv
│   └── vg_sales_Final.csv
├── presentations/
│   ├── Publisher_Final_Presentation.pptm
│   └── Developer_Final_Presentation.pptm
├── report/
│   └── Video_Game_Sales_Report.docx
└── README.md ✅
```

---

## 👨‍💻 Author
**Jaya Chandra Kadiveti**  
📧 [Kadivetijayachandra@gmail.com](mailto:Kadivetijayachandra@gmail.com)
