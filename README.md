# Analysis of Clickbait Headlines in Taiwanese Online News

## 📊 Project Overview
**Duration:** September 2023 - December 2023  
**Repository:** `Analysis-of-Clickbait-Headlines-in-Taiwanese-Online-News`

This project analyzes trends and category differences in the quality of Taiwanese online news, focusing on the prevalence of clickbait headlines. The goal is to raise public awareness about media literacy and promote critical thinking when consuming news.

---

## 📌 Background
In the digital age, online media is the fastest and most widespread source of information. With people exposed to massive amounts of news daily, ensuring the quality of online content has become a societal concern. Inaccurate or sensational headlines without substance often overshadow critical information, limiting public discourse and hindering positive societal changes.

---

## 🚩 Challenges
- **Misinformation:** Inaccurate content misguides public perception.
- **Sensationalism:** Headlines designed to attract clicks may lack meaningful content.
- **Media Influence:** Clickbait can divert attention from important issues, reducing societal awareness and critical thinking.

---

## 🎯 Objectives
- **Trend Analysis:** Examine trends and category differences in Taiwanese online news.
- **Impact Assessment:** Understand how societal events influence news quality.
- **Media Literacy:** Promote awareness of media consumption habits and encourage critical evaluation of news content.

---

## 🚀 Features
### 1. **Interactive Dashboard** (`app.py`)
- Built with **Streamlit** and **Plotly** for dynamic visualizations.
- Allows filtering by date, media outlet, news category, and clickbait method.
- Tabs include:
  - **Three-Month Analysis:** Media-wise clickbait trends.
  - **Long-Term Trends:** Analysis from 2018 to 2023.
  - **Clickbait Detector:** Predict if a headline is clickbait.

### 2. **Clickbait Detection Model** (`is_clickbait.py`)
- Utilizes keyword-based rules derived from linguistic research.
- Detects patterns such as emotional language, sensational phrases, and interrogative forms.

### 3. **Data Visualization**
- Time-series trends for media outlets and categories.
- Clickbait methods and their prevalence across news categories.

---

## 📊 Sample Visualizations
- **Clickbait Ratio by Media:** Bar charts comparing different outlets.
- **Trends Over Time:** Line charts showing fluctuations in clickbait usage.
- **Category Analysis:** Bubble charts highlighting dominant clickbait techniques in each category.

---

## ⚙️ Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Analysis-of-Clickbait-Headlines-in-Taiwanese-Online-News.git
   cd Analysis-of-Clickbait-Headlines-in-Taiwanese-Online-News
  
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   
3. **Run the App:**
   ```bash
   streamlit run app.py
   
---

## 📋 Technologies Used
- **Python:** (`pandas`, `numpy`)
- **Streamlit** for interactive web apps
- **Plotly** for data visualization
- **Regex** for clickbait detection

---

## 🤝 Contributors
- Tsai, Ping-Yun
- Hsieh, Ping-Ju
- Lin, Yi-Ting
- Tsai, Yi-Fang
- Lai, En-Te
- Ting, Tzu-En

