🎓 Student Tracking App

A simple and effective student tracking system built using **Streamlit** and **MongoDB**. This app helps track student **attendance**, **session participation**, **feedback**, and provides an **admin dashboard** with **college-wise analytics**.

##  Live Demo

 Deployed App: [Click to View](https://student-trackinggi-exp8hk4qm2bd6rfsxbqzoi.streamlit.app/)  
 GitHub Repo: [student-tracking](https://github.com/sigmadosase/student-tracking)

##  Features

-  Student Registration & Login
-  Daily Attendance Marking
-  Feedback Collection
-  Session Tracking (Topic + Duration)
-  Admin Dashboard with:
-  College-wise search
-  View attendance logs
-  Session and feedback overview
-  Drill-down into per-college data

##  Tech Stack

- **Frontend:** Streamlit (Python)
- **Backend:** Python
- **Database:** MongoDB (via PyMongo)
- **Deployment:** Streamlit Cloud
- 
##  How to Run Locally
### 1. Clone the Repository
git clone https://github.com/sigmadosase/student-tracking.git
cd student-tracking

2. Install Dependencies
Make sure Python 3.9+ is installed, then run:
pip install -r requirements.txt
If requirements.txt is missing, install manually:

pip install streamlit pymongo bcrypt
3. Start MongoDB Locally
Make sure MongoDB server is running locally at mongodb://localhost:27017.

4. Run the App
streamlit run app.py

Author
Made with ❤ by Md Arman


Note
If you face current_date not defined, make sure utils.py includes:

from datetime import datetime

def current_date():
    return datetime.today().strftime("%Y-%m-%d")
