# Student Sleep, Activity & Energy Analysis 📊

## 📌 Project Overview
This project analyzes how **daily physical activity (steps)** and **overnight sleep duration** impact a student’s **energy, focus, mood, and stress levels**.  
The objective is to identify the **optimal “sweet spot”** for sleep and steps that maximizes daily energy and productivity.

---

## 🎯 Research Question
> How do small changes in a student's daily activity (steps) and overnight sleep affect their next-day focus and energy levels?

---

## 🧠 Key Objectives
- Analyze the relationship between **sleep duration and energy level**
- Study how **steps per day** affect **energy, mood, focus, and stress**
- Identify the **optimal range (sweet spot)** for sleep and steps
- Quantify **energy loss** when students deviate from the ideal lifestyle

---

## 📂 Dataset Description
The dataset includes self-reported student data with the following key variables:
- Steps per Day
- Sleep Duration (last night)
- Sleep Quality
- Energy Level
- Focus Level
- Mood Rating
- Anxiety/Stress Level
- Daytime Sleepiness

Data cleaning and encoding were performed before analysis (binary encoding, categorical mapping, and feature engineering). :contentReference[oaicite:0]{index=0}

---

## 🔍 Methodology
- **Data Cleaning & Encoding**
  - Binary encoding (Yes/No → 1/0)
  - Sleep goal feature creation (≥7 hours)
- **Statistical Analysis**
  - Pearson Correlation Analysis
- **Regression Models**
  - Linear Regression (Sleep → Energy)
  - Polynomial Regression (Steps → Energy)
- **Optimization**
  - Derivative analysis to find the **sweet spot** for steps
- **Integration Model**
  - Combined impact of sleep and steps on predicted energy
  - Weekly energy loss calculation

---

## 📈 Key Findings
- Sleep duration has a **strong positive correlation** with energy and focus
- Steps per day show a **non-linear relationship** with energy
- Optimal daily activity is around **~9,800–10,000 steps**
- Ideal sleep duration lies between **7–8 hours**
- Deviating from these ranges leads to measurable **weekly energy loss**

---

## 🛠️ Tools & Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📊 Visualizations
- Scatter plots (Steps vs Energy, Sleep vs Energy)
- Regression trend lines
- Bar charts (Sleep Goal vs Stress & Mood)
- Marginal benefit and sweet spot graphs

---

## 📁 Repository Structure
