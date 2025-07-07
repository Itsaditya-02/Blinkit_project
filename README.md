# 🛒 Blinkit Grocery Sales Power BI Dashboard

## 📘 Overview
An interactive Power BI dashboard built during my internship to analyze Blinkit’s grocery sales data. It highlights KPIs across outlet size, type, location, fat content, and product categories, offering actionable insights for strategy.

## ⚙️ Features
- **Interactive visuals**: KPI cards, donut charts, bar charts, line charts, and matrix tables  
- **DAX measures**: Total Sales, Average Sales, Item Count, Average Rating  
- **Filters & interactivity**: Slicers for outlet attributes, cross-filtering across visuals  
- **Insights-driven analysis**: Highlights Tier 3 outlets, low-fat preference, top product categories

## 📂 Files Included
| File Name                          | Description                                         |
|-----------------------------------|-----------------------------------------------------|
| `Blinkit_analysis.pbix`           | Power BI Desktop report file                        |
| `dashboard_screenshots.png`       | High-res export of dashboard visuals               |
| `Project_Report.docx` / `.gdoc`   | Structured report with embedded visuals            |
| `Project_Report.pdf`              | Printable PDF version of the report                |

## 🚀 Installation & Usage
1. Clone/download this repo  
2. Open `Blinkit_analysis.pbix` in Power BI Desktop  
3. Place `.pbix` and `.xlsx` (if used) in the same folder for refresh  
4. View screenshots and read the report for metrics, DAX logic, and insights

## 📊 Data Model & DAX
- **Star schema:** Fact-Sales table linked with Item, Outlet, and Date dims  
- **Measures:**
  - `Total Sales = SUM(Sales[Sales])`
  - `Avg Sales = AVERAGEX(...)`
  - `Item Count = DISTINCTCOUNT(Items[ItemID])`
  - `Avg Rating = AVERAGE(Sales[Rating])`

## 💡 Key Insights
- Tier 3 outlets and medium-sized stores outperform others  
- Low-fat items show slightly higher average sales  
- Fruits and snacks are leading product categories  

## 🔍 Future Enhancements
- Add forecasting with DAX or AI visuals  
- Enable drill-through for detailed analysis  
- Publish to Power BI Service with scheduled refresh  

## 🙏 Acknowledgements
Thanks to my mentors and colleagues for their guidance, feedback, and support throughout the internship.

## 📚 References
- YouTube walkthrough: *Amazing Real Time Power BI Project | Start to End Analysis* :contentReference[oaicite:1]{index=1}  
- GitHub: Tejassrivastava8 Blinkit Data Analysis repo :contentReference[oaicite:2]{index=2}  
- Best practices for GitHub project READMEs :contentReference[oaicite:3]{index=3}  

---

**Feel free to review, comment, or contribute! 😊**
