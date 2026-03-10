# Healthcare Management System

**Author:** Khadeim Rahman  

A simple web-based healthcare management system built with python (flask) and SQLite  
Admins can manage patients and appointments, while users can view only their own appointments.  

---

## Features

### Admin

default admin account:
admin - admin123

- Add, edit, and delete patients
- Schedule appointments for patients and assign them to users
- View dashboard with patient condition chart
- Access all patient and appointment information

### User
- Register and log in
- View only their own appointments
- View profile information
- Dashboard with patient overview (read-only)

---

## Technologies Used

- Python 
- Flask
- SQLite
- HTML, CSS, JavaScript
- Chart.js (for charts)
- Werkzeug (for password hashing)

---

## Setup Instructions

1. **Install Python 3**  
2. **Create and activate a virtual environment** (optional but recommended)  
3. **Install dependencies**:  
   ```bash
   pip install Flask Werkzeug
4. **Run with:**:
python app.py and open link in browser