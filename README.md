# 🧠 Medical Machine Learning: Predicting and Correlating Diabetes Rates in San Diego

🚀 **Goal**  
Analyze and model the prevalence of diabetes across San Diego County using **Big Data** and **Machine Learning**, focusing on potential racial correlations. We’ve built an analytical model, performed demographic correlation analysis, and created an interactive website to visualize our insights.

🔗 **Website:** [Visit Project Website](https://sites.google.com/view/mmlbda/team?authuser=0)


---

## 📌 Project Summary

This project investigates how race correlates with the prevalence of diabetes across 17 cities in San Diego County. Our approach combines geospatial visualization, statistical modeling, and machine learning—specifically an overdetermined least squares regression optimized via gradient descent. The final model outputs **Race Linked Coefficients (RLCs)** which are used to estimate diabetes prevalence in other populations.

---

## 📊 Tools & Technologies

- 🗺️ **Kepler.gl** – Geospatial visualization  
- 📊 **Tableau** – Interactive charts & dashboards  
- 🧠 **Python** – Data wrangling, regression modeling, neural network simulation  
- 🧮 **MATLAB** – Matrix computations, backpropagation  
- 🧑‍💻 **VSCode** – Code development  
- 🌐 **Google Sites** – Interactive infographic website  

---

## 🧬 Target Demographics

- Hispanic/Latino  
- Black  
- Asian Pacific Islander (API)  
- White  

*Population samples include only these four racial groups.*

---

## 🏙️ Target Cities

17 cities in San Diego County were selected based on data availability, including:

- Lemon Grove  
- Chula Vista  
- National City  
- ... *(full list available on website)*

---

## ⚕️ Defining a Diabetes Case

A diabetes "case" is any event involving:
- Death
- ER Admission
- Hospitalization
- In-patient Treatment
- Physical Rehabilitation
- SNF/Nursing Home

---

## 🔍 Key Findings

- **Top 3 Cities with Highest Diabetes Prevalence:**  
  1. **Lemon Grove**  
  2. **Chula Vista**  
  3. **National City**

- These cities had **Hispanic/Latino** as the dominant demographic group (>50%).

- **Correlations Observed:**
  - 🧑🏿‍🦱 Black: **Strong positive correlation**
  - 🧑🏽 Hispanic/Latino: **Moderate positive correlation**
  - 🧑🏻 White: **Moderate negative correlation**
  - 🧑🏼‍🦱 API: **Moderate positive correlation**

---

## 🧮 Machine Learning Model

### 🔗 Race Linked Coefficients (RLCs)

A unique scalar value per race to model:



### 🧠 Neural Network Inspired Optimization

- Solves an **overdetermined system** using **least squares regression**
- Optimized via **gradient descent with backpropagation**
- Model achieves **~95% accuracy** on training data
- Enables **future forecasting** based on population growth trends

---

## ⚠️ Data & Assumptions

- Adults aged **18+**
- Population sample limited to 4 racial groups
- **Confounding variable:** Age distribution not controlled (age 65+ more vulnerable)
- **Cases per 100,000** = (Total Cases ÷ Population) × 100,000

---

## 📚 Research Inspiration

Inspired by work from the Technical University of Munich on **neural networks solving linear systems**.

---

## 👥 Meet the Team

| Name               | LinkedIn | GitHub |
|--------------------|----------|--------|
| Siddhant Borse     | [LinkedIn](#) | [GitHub](#) |
| Pranjal Patel      | [LinkedIn](#) | [GitHub](#) |
| Jesse Hurtado      | [LinkedIn](#) | [GitHub](#) |
| Atharva Kulkarni   | [LinkedIn](#) | [GitHub](#) |

---

## 📌 Future Improvements

- Incorporate **age** and **income** as confounding variables  
- Add **forecast automation** using demographic projection APIs  
- Explore **classification models** for high-risk population segmentation  

---

## 📄 License

MIT License © 2025 — Medical ML Team

---

## ⭐ Show Your Support!

Give this repo a ⭐ if you found it insightful or useful. Feel free to fork and build upon it!
