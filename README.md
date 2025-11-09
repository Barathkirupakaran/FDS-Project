# 🎓 Student Alcohol Consumption Analysis  
**A Django Web Application for Data Analysis and Visualization**

---

## 🧠 Project Overview  
This project analyzes **student alcohol consumption** patterns and their relationship with **academic performance**, **family background**, and **lifestyle factors** using **Python, Django, Pandas, NumPy, and Plotly**.  

It is based on the **UCI Machine Learning Repository’s Student Alcohol Consumption Dataset**, containing data from **649 Portuguese secondary school students**.

---

## 🚀 Features  
- Interactive **dashboard** displaying summary statistics  
- **Charts** showing consumption patterns by age, gender, and study time  
- **Correlation diagrams** highlighting key relationships  
- Data processed and merged from two CSV files  
- Clean, responsive UI built with HTML, CSS, and Django templates  
- Color-coded badges for alcohol consumption levels  
- Real-time data rendering with Plotly visualizations  

---

## 📂 Project Structure  
student-alcohol-django-app/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
│
├── student_alcohol/ # Project configuration
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── consumption/ # Main Django app
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── templates/consumption/
│ ├── base.html
│ ├── index.html
│ ├── charts.html
│ └── diagrams.html
│
├── data/
│ ├── student-mat.csv
│ └── student-por.csv
│
└── Server Start guide.txt

yaml
Copy code

---

## ⚙️ Technology Stack  

| Category | Tools Used |
|-----------|------------|
| **Backend** | Django 4.2, Python 3.13 |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Plotly, Matplotlib |
| **Database** | SQLite3 |
| **IDE** | Visual Studio Code |

---

## 📊 Data Insights  
- Students with **lower alcohol consumption** tend to have **higher academic performance**  
- **Weekend consumption (Walc)** is significantly higher than **weekday (Dalc)**  
- Students with **more study time** show **lower consumption levels**  
- **Family support and parental education** play key roles in influencing behavior  

---

## 🧩 Key Pages  

### 🏠 **Home Page (Dashboard)**  
Displays overall statistics such as total students, average grades, and alcohol levels, along with sample data and key insights.  

### 📈 **Charts Page**  
Interactive bar charts showing consumption by **age**, **gender**, **study time**, and **grades**.  

### 🔗 **Diagrams Page**  
Correlation heatmaps and charts highlighting relationships between behavioral and academic factors.  

---

## 💻 Installation & Running the Project  

### Step 1 — Clone this Repository  
```bash
git clone https://github.com/YourUsername/student-alcohol-django-app.git
cd student-alcohol-django-app
Step 2 — Create and Activate Virtual Environment
bash
Copy code
python -m venv .venv
.\.venv\Scripts\activate      # Windows
source .venv/bin/activate     # Mac/Linux
Step 3 — Install Requirements
bash
Copy code
pip install -r requirements.txt
Step 4 — Run the Server
bash
Copy code
python manage.py runserver
Visit the application in your browser at:
👉 http://127.0.0.1:8000/

📚 Dataset Information
Dataset Name: Student Alcohol Consumption (UCI)

Attributes: 33 variables

Total Records: 649 students

Files Used:

student-mat.csv

student-por.csv

Key Variables:

Dalc: Weekday alcohol consumption (1–5 scale)

Walc: Weekend alcohol consumption (1–5 scale)

G1, G2, G3: Academic grades

Studytime, Failures, Famrel, Freetime, Goout

🧮 Analysis Highlights
Observation	Finding
Academic Impact	Higher alcohol consumption = Lower grades
Weekend vs Weekday	Weekend drinking 50% higher
Gender	Males consume more on average
Study Time	More study hours = Less alcohol
Family Support	Strong family ties = Healthier habits

🧠 Learnings
Implemented Django MVT architecture for full-stack web development

Used Pandas & NumPy for real-world data processing

Created interactive charts using Plotly

Practiced data visualization, UI design, and debugging

Improved understanding of educational analytics and data interpretation

🔮 Future Enhancements
Add machine learning predictions for academic risk

Integrate user login and dataset upload functionality

Deploy on cloud platforms (Heroku / AWS)

Expand dataset and introduce real-time updates

📜 References
UCI Machine Learning Repository – Student Alcohol Consumption Dataset

Django Documentation v4.2

Pandas & NumPy Official Docs

Plotly Python Visualization Library

Matplotlib Guide

W3Schools & MDN for frontend reference

👨‍💻 Author
Name: Cutepanda
Date: November 2025
Institute: SRM Institute of Science and Technology
Field: B.Tech – Computer Science (Big Data Analytics)
Developed as part of: Full Stack Development & Data Science Project

🌐 Live Demo / GitHub Link
🔗 [Add your GitHub Repository URL or Demo Link here]

🏁 Server Start Quick Reference
If you ever need to start your server manually:

bash
Copy code
cd C:\Programs\FDS_Project\student-alcohol-django-app
.\.venv\Scripts\activate
python manage.py runserver
⭐ If you find this project helpful, don’t forget to star the repository!

yaml
Copied

---

Would you like me to:
1. Generate this as a **ready `.md` file** for you to upload directly to GitHub,  
2. Or make it visually enhanced with **badges and screenshots sections** for better presentation on your repo homepage?






