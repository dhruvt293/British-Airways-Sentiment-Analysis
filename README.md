# ✈️ AeroSentix: British Airways Passenger Sentiment Analytics

![Deloitte Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Deloitte.svg/1200px-Deloitte.svg.png)

_A corporate data analytics project analyzing passenger sentiment and airline performance._

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-005587?style=for-the-badge&logo=data-datacamp&logoColor=white)
![Deloitte Project](https://img.shields.io/badge/Deloitte-Simulation-86BC25?style=for-the-badge)

## 📑 Project Overview

**AeroSentix** is a comprehensive Data Analytics project developed as part of a **Deloitte** corporate assignment. The core objective of this project is to analyze thousands of passenger reviews for British Airways to uncover underlying sentiments, evaluate key performance indicators (KPIs), and present actionable business insights to stakeholders through interactive **Tableau** dashboards.

![Main Tableau Dashboard Preview](https://dummyimage.com/1000x500/000000/86bc25.png&text=Main+Tableau+Dashboard+Preview)

---

## 🎯 Business Problem

In the highly competitive aviation industry, customer satisfaction is directly correlated with brand loyalty and revenue. British Airways executives need a granular understanding of passenger experiences to identify pain points and optimize service quality. 

**Key Objectives:**
- Conduct sentiment analysis on unstructured review data.
- Identify the impact of variables such as `seat_type`, `aircraft`, and `route` on passenger ratings.
- Provide data-driven recommendations to improve in-flight and ground services.

---

## 📊 The Data

The dataset comprises comprehensive passenger reviews covering various aspects of the flight experience:
- **Passenger Demographics & Flight Details**: `traveller_type`, `seat_type`, `route`, `date_flown`, `aircraft`
- **Quantitative Ratings (1-10)**: `seat_comfort`, `cabin_staff_service`, `food_beverages`, `ground_service`, `value_for_money`, `entertainment`
- **Qualitative Feedback**: Written review `content` and `recommended` status.
- **Geographic Data**: Included `Countries.csv` for regional analysis of passenger origins.

---

## 📈 Visualizations & Dashboards

This project includes a series of corporate-standard Tableau dashboards designed for executive presentation:

### 1. Executive Summary & Sentiment Overview
Provides a high-level view of overall passenger satisfaction, Net Promoter Score (NPS) approximations, and time-series trends of ratings.

![Executive Summary](https://dummyimage.com/800x400/000000/86bc25.png&text=Executive+Summary+Dashboard)

### 2. Service Quality Deep-Dive
Analyzes the breakdown of ratings across different service pillars (Food & Beverage, Seat Comfort, Cabin Staff) across different classes (Economy, Business, First).

![Service Quality](https://dummyimage.com/800x400/000000/86bc25.png&text=Service+Quality+Analysis)

### 3. Route & Aircraft Performance
Geographic and fleet-specific performance metrics to identify underperforming routes or specific aircraft models (e.g., A380 vs. A320) that require attention.

![Aircraft Dashboard](https://dummyimage.com/800x400/000000/86bc25.png&text=Route+and+Aircraft+Performance)

---

## 💡 Key Business Insights

1. **Service Discrepancies**: Significant variations in `cabin_staff_service` ratings were observed depending on the route and time of year.
2. **Aircraft Impact**: Legacy aircraft received consistently lower `seat_comfort` scores compared to newer fleet additions.
3. **Value Proposition**: A strong correlation exists between `value_for_money` and `ground_service` experiences, indicating that the passenger journey begins well before boarding.

---

## ⚙️ Tools & Technologies

- **Tableau Desktop**: Primary tool for data visualization, dashboard creation, and interactive reporting.
- **Data Processing (Excel/CSV)**: Data cleaning, formatting, and structural preparation.
- **Deloitte Standard Reporting**: Adhering to corporate guidelines for color palettes (e.g., Deloitte Green, Black, Grey), typography, and presentation clarity.

---

## 🚀 How to Run the Project

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/dhruvt293/British-Airways-Sentiment-Analysis.git
   ```
2. Ensure you have **Tableau Desktop** or **Tableau Reader** installed.
3. Open the `.twbx` (Tableau Packaged Workbook) file located in the repository.
4. Interact with the dashboards to explore the data.

---

*This project was completed as part of a Deloitte Data Analytics simulation. The data utilized is publicly available and for educational/demonstration purposes.*
