# 📚 Student Performance Dashboard

## 📌 Overview
This Power BI dashboard analyzes students' academic performance, attendance, and behavior. It helps identify trends and provides insights through interactive visualizations.

---

## 🎯 Objective

- Analyze student scores and performance.
- Monitor attendance records.
- Track behavior patterns.
- Compare results across subjects and terms.

---

## 📂 Dataset

### Students.csv
- StudentID
- Name
- Gender
- Class
- Section

### Scores.csv
- StudentID
- Subject
- ExamType
- Score
- MaxScore
- Term

### Attendance.csv
- StudentID
- Date
- Status
- Reason

### Behavior.csv
- StudentID
- Date
- BehaviorType
- Notes

---

## 🔗 Data Model

**Primary Key**
- StudentID (Students Table)

**Foreign Keys**
- StudentID (Scores Table)
- StudentID (Attendance Table)
- StudentID (Behavior Table)

Relationship Type:
- One-to-Many (1:*)

---

## 📐 DAX Measures

- % Score
- Average Score
- Attendance %
- Behavior Count
- Performance Category (High, Medium, Low)

---

## 📊 Visualizations

📈 **Bar Chart**
- Average Score by Subject and Class

📉 **Line Chart**
- Performance Trend by Term

🍩 **Donut Chart**
- Behavior Type Distribution

📋 **Table**
- Student-wise Scores with Conditional Formatting

🃏 **Cards**
- Total Students
- Average Attendance
- Average Score

---

## 🎛 Interactive Features

- Slicers for Class, Section, Subject, and Term
- Drillthrough Page for Student Profile
- Tooltips for additional insights
- Bookmark Navigation

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling

---

## ✨ Dashboard Features

✔ Data Cleaning  
✔ Relationship Creation  
✔ DAX Measures  
✔ KPI Cards  
✔ Interactive Charts  
✔ Slicers and Filters  
✔ Drillthrough Analysis  

---

## 📁 Files

- Students.csv
- Scores.csv
- Attendance.csv
- Behavior.csv
- Practical project.pbix

---

### 🚀 Project Name
**Student Performance Dashboard – Academic & Behavioral Insights**
