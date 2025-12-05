<div align="center">

# 📊 Data Jobs Dashboard - Power BI

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white)](https://github.com/snowjug/Data_jobs_Dashboard_powerbi)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

### An Interactive Power BI Dashboard for Analyzing Global Data Job Market Trends

*Forked from [shrutee2255/Data_jobs_Dashboard_powerbi](https://github.com/shrutee2255/Data_jobs_Dashboard_powerbi)*

[View Dashboard](#-dashboard-preview) • [Features](#-key-features) • [Installation](#-getting-started) • [Usage](#-usage) • [Contributing](#-contributing)

---

![Data Jobs Dashboard Overview](dashboard.png)

*Interactive Power BI Dashboard showcasing global data job market insights*

---

</div>

## 🌟 Project Overview

Welcome to the **Data Jobs Dashboard** – a comprehensive, interactive Power BI solution designed to provide deep insights into the global data job market. This dashboard transforms raw job posting data into actionable intelligence, helping job seekers, recruiters, and market analysts make data-driven decisions.

### 🎯 What This Dashboard Offers

- 📈 **Real-time Job Market Analysis** - Track job availability across different data roles
- 🌍 **Global Geographic Distribution** - Visualize job hotspots worldwide
- 💰 **Salary Intelligence** - Compare compensation packages across roles and regions
- 🔍 **Interactive Exploration** - Dynamic filtering for personalized insights
- 📊 **Trend Analysis** - Identify growing sectors and in-demand skills

---

## ✨ Key Features

### 🗺️ **1. Geographic Job Distribution Map**

- **Interactive world map** displaying job density by country
- **Heat map visualization** with size/color-coded markers representing job volume
- **Drill-down capability** to explore regional job markets
- **Tooltips** showing detailed country statistics on hover

### 📊 **2. Role-Based Job Demand Analysis**

- **Horizontal bar charts** showcasing top data roles:
  - 💼 Data Engineer
  - 📊 Data Analyst
  - 🔬 Data Scientist
  - 🤖 Machine Learning Engineer
  - 📈 Business Intelligence Analyst
  - And more specialized roles
- **Comparative analysis** to identify high-demand positions

### 💎 **3. Key Performance Indicators (KPIs)**

Three prominent KPI cards displaying:
- **📌 Total Job Count** - Overall market size
- **💵 Average Annual Salary** - Yearly compensation trends
- **⏰ Average Hourly Rate** - Hourly wage benchmarks

### 🎚️ **4. Advanced Interactive Filters**

Dynamic filtering options including:
- **Job Title** - Filter by specific roles
- **Location/Country** - Focus on geographic regions
- **Salary Range** - Set compensation thresholds
- **Experience Level** - Junior, Mid, Senior positions
- **Employment Type** - Full-time, Part-time, Contract, Remote

### 📈 **5. Additional Insights**

- Salary distribution by job role
- Trending skills and technologies
- Year-over-year job growth trends
- Remote vs. on-site opportunities

---

## 🗂️ Dataset Information

### Data Source

The dashboard leverages a comprehensive dataset containing:

| Field | Description |
|-------|-------------|
| **Job Title** | Specific role designation (e.g., Data Analyst, Data Engineer) |
| **Country/Location** | Geographic location of the job posting |
| **Salary Information** | Annual and hourly compensation details |
| **Company Name** | Hiring organization |
| **Job Type** | Employment classification (Full-time, Contract, etc.) |
| **Experience Level** | Required experience tier |
| **Posted Date** | Job listing publication date |

### Dataset Files

- `job_postings_flat.csv` - Main dataset containing job posting details

> **Note:** The dataset is continuously updated to reflect current market trends.

---

## 🛠️ Tools & Technologies

<div align="center">

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Dashboard creation & visualization |
| ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square&logo=microsoft&logoColor=white) | Data transformation & cleaning |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data preprocessing |
| ![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Calculated measures & columns |

</div>

---

## 🚀 Getting Started

### Prerequisites

- **Microsoft Power BI Desktop** (Latest version recommended)
  - [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- Basic understanding of Power BI interface
- Windows 10 or later (for Power BI Desktop)

### 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/snowjug/Data_jobs_Dashboard_powerbi.git
   cd Data_jobs_Dashboard_powerbi
   ```

2. **Open Power BI File**
   - Launch **Power BI Desktop**
   - Open the `.pbix` file from the repository
   - If prompted, allow data refresh

3. **Data Refresh (Optional)**
   - Navigate to **Home** > **Refresh**
   - Ensure the `job_postings_flat.csv` path is correctly linked

---

## 📖 Usage

### Interacting with the Dashboard

1. **Explore KPIs**
   - View high-level metrics at the top of the dashboard
   - Observe changes as you apply filters

2. **Use Geographic Map**
   - Click on countries to filter data
   - Zoom in/out for detailed regional analysis

3. **Analyze Job Roles**
   - Hover over bars to see exact job counts
   - Click on roles to cross-filter other visuals

4. **Apply Custom Filters**
   - Use slicers on the right/left panels
   - Select multiple options using `Ctrl + Click`
   - Clear filters with the eraser icon

5. **Export Insights**
   - Export visuals: Right-click > **Export data**
   - Create custom reports using Power BI's export features

---

## 🔍 Key Insights Derived

Based on the analysis, you can discover:

- 🌐 **Top Countries** for data jobs (e.g., USA, UK, Germany, India)
- 💼 **Most In-Demand Roles** and their growth trends
- 💰 **Salary Benchmarks** by role and location
- 📍 **Remote Work Opportunities** vs. traditional positions
- 📚 **Skill Requirements** trending in the market

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Ideas for Contribution

- 🆕 Add new visualizations
- 📊 Include additional datasets
- 🐛 Fix bugs or improve performance
- 📝 Enhance documentation
- 🎨 Improve UI/UX design

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👏 Acknowledgments

- **Original Creator:** [shrutee2255](https://github.com/shrutee2255) for the initial dashboard concept
- **Data Sources:** Job posting aggregators and public datasets
- **Power BI Community** for continuous inspiration and support

---

## 📧 Contact

Have questions or suggestions? Feel free to reach out!

- **GitHub:** [@snowjug](https://github.com/snowjug)
- **LinkedIn:** [Atharv Patil](https://linkedin.com/in/atharv2405)

---

<div align="center">

### ⭐ If you find this project helpful, please consider giving it a star!

**Made with ❤️ and Power BI**

[⬆ Back to Top](#-data-jobs-dashboard---power-bi)

</div>
