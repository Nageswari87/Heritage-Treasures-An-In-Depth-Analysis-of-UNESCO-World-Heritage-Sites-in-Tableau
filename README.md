# 🌍 UNESCO Heritage Treasures Web Application

## 📊 Abstract
Cultural heritage sites represent the history and identity of nations across the globe. This project, **UNESCO Heritage Treasures Web Application**, is a Flask-based system integrated with Tableau Public to analyze UNESCO World Heritage Sites (2019 dataset). The application provides user authentication and an interactive dashboard to visualize country-wise distribution, endangered sites, and regional inscription trends. This project demonstrates data analytics and full-stack web development using Python, Flask, and Tableau.

---

## 📖 Introduction
UNESCO World Heritage Sites are recognized for their cultural, natural, or mixed significance. Raw datasets can be complex and difficult to interpret. This application transforms UNESCO data into interactive visual dashboards that help users explore meaningful insights easily.

---

## 🎯 Objectives
- Design an interactive UNESCO heritage analysis dashboard  
- Implement user login and registration functionality  
- Visualize global heritage site distribution  
- Analyze endangered sites and risk percentage  
- Study regional inscription trends  
- Integrate Tableau dashboard into a Flask web application  

---

## 📌 Scope of the Project
This project is suitable for academic submissions and data analytics demonstrations. It focuses on visualization and analysis of UNESCO data and does not perform predictive modeling in the current version.

---

## 🏗️ System Architecture
The application follows a client–server architecture:

- Frontend: HTML, CSS  
- Backend: Python Flask  
- Visualization: Tableau Public  
- Data Source: UNESCO CSV Dataset (2019)  

Flask routes handle user requests, and the Tableau dashboard is embedded into the web interface.

---

## 🛠️ Technologies Used
- Python 3  
- Flask  
- Tableau Public  
- HTML5  
- CSS3  
- CSV Dataset  

---

## 📂 Project Structure
```
UNESCOHeritageApp/
├── app.py
├── templates/
│   ├── login.html
│   ├── signup.html
│   └── dashboard.html
├── static/
│   └── heritage.jpg
└── README.md
```

---

## 🔍 Functional Description

### User Authentication
Users can register using email and password. Registered users can log in to access the dashboard.

### Dashboard
After login, users can explore:
- Country-wise heritage distribution (Treemap)  
- Sites at Risk analysis (Pie Chart)  
- Regional inscription trends (Line Chart)  
- Interactive filters (Country, Region, Year, Category)  

### Story Mode
The dashboard includes multiple slides explaining dataset overview, country distribution, endangered sites, regional trends, and final insights.

---

## 🚀 Installation and Execution

1. Install Python (3.7 or above)  
2. Install Flask:

```
pip install flask
```

3. Run the application:

```
python app.py
```

4. Open in browser:

```
http://127.0.0.1:5000
```

---

## ⚠️ Limitations
- Static dataset (2019 only)  
- No real-time API integration  
- No database integration  
- No predictive analytics  

---

## 🔮 Future Enhancements
- Real-time UNESCO API integration  
- Machine learning-based endangered site prediction  
- Database integration (MySQL / SQLite)  
- Mobile-responsive UI  
- Advanced analytics features  

---

## ✅ Conclusion
The UNESCO Heritage Treasures Web Application transforms raw heritage data into interactive visual insights. By integrating Tableau with Flask, the project demonstrates how visualization and web technologies can work together to support data-driven cultural analysis.

---

## 👩‍💻 Author
Developed as part of an academic Data Analytics project.

🌍 *“Preserving the past, visualizing the future.”*
