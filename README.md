# 📊 Smart Recruiter & Spam Detector System

An intelligent, end-to-end system that allows companies to:
- 📌 Filter top candidates based on resumes, skills, experience, and certifications
- 🧠 Predict recruiter decisions and salary expectations using machine learning
- 📈 Visualize insights like salary vs. experience, and job role distribution using Plotly
- 🤖 Detect spam emails using a custom SVM-based classifier
- 💬 Interact with shortlisted candidates via a chatbot (API-ready)

---

## 🚀 Features

### ✅ Resume Filtering & Recommendation
- Top 5 candidate recommendations based on:
  - Skill match
  - Experience
  - Projects
  - Certifications
- Job-role based filtering (`e.g., "Python Developer"`)
- ML model to predict recruiter decision and salary

### 📉 Data Visualizations (Plotly)
- Salary vs. Experience scatter/line plots
- Job Role distribution pie chart
- Visuals of recommended candidates

### 📧 Spam Detection System
- Uses custom Support Vector Machine (SVM) with polynomial & linear kernels
- Laplace smoothed frequency table-based email classification

### 💬 Chatbot Integration (API Ready)
- Easily integrate chatbot APIs to communicate with selected candidates

---

## 🛠️ Tech Stack

- **Python**: Data processing, machine learning
- **Pandas, NumPy**: Data cleaning, manipulation
- **scikit-learn**: ML modeling (SVM, classification)
- **PrettyTable**: Results formatting
- **Plotly**: Interactive data visualizations
- **Flask / FastAPI (optional)**: API backend integration
- **Frontend**: Built with [Lovable AI](https://lovable.so) or manually using React/Tailwind (user-defined)

---

## 📁 Directory Structure

