# data-analysis-report

# ENU Digital Infrastructure Data Analysis 📊
This repository contains a comprehensive statistical analysis of the digital infrastructure and educational environment at the L.N. Gumilyov Eurasian National University (ENU). The study evaluates satisfaction levels among faculty members and students regarding university-provided digital tools.

## 📌 Project Overview
The analysis is based on survey data collected from faculty (PPS) and students. It examines the efficiency and accessibility of various digital resources, including Wi-Fi connectivity, SmartENU, Platonus, and Microsoft 365 services.

## 🛠 Tech Stack
* **Language:** Python 3.10
* **Key Libraries:**
  * `pandas` & `numpy` — Data manipulation and cleaning.
  * `scipy.stats` — Advanced statistical testing.
  * `matplotlib` — Data visualization and plotting.

## 🔬 Methodology
The project employs rigorous statistical methods to ensure data validity:
1. **Shapiro-Wilk Test:** Used to check the normality of the data distribution.
2. **One-Sample t-test:** Conducted to compare mean satisfaction scores against a defined threshold (6.0).
3. **Bonferroni Correction:** Applied to mitigate the risk of Type I errors during multiple hypothesis testing (Target α = 0.00455).
4. **Spearman Correlation:** Used to identify relationships between different digital usage metrics.

## 📈 Key Findings
- **Infrastructure Satisfaction:** Statistical evaluation of user satisfaction with Platonus and SmartENU platforms.
- **Connectivity Analysis:** Assessment of Wi-Fi quality and its impact on the educational process.
- **Correlation Insights:** Visual representation of the link between faculty digital skills and their adoption of cloud-based tools.
- **Visualizations:** The project includes high-quality histograms and scatter plots that illustrate the distribution of survey responses.
