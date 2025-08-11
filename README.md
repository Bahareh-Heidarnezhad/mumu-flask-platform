# MUMU — Web Design Course Project

MUMU is an 8‑page full‑stack web application built with **Flask** and **MongoDB**.  
It was developed as part of a web design course to provide a closed‑community platform for Modul University students to list services, leave reviews, and exchange feedback.

---

## Features
- **User Authentication**: Signup and Login pages
- **Dashboard**: Overview of activity and available services
- **Booking & Reviews**: Book services and leave feedback
- **Messaging**: Private communication between users
- **Notifications**: Alerts for messages, bookings, and reviews
- **Profile Management**: Edit profile and setup page
- **Services**: Post and browse service listings

---

## Tech Stack
**Backend**: Python 3.x, Flask, PyMongo (MongoDB)  
**Frontend**: HTML5, CSS3, Jinja2 templates  
**Database**: MongoDB  
**Structure**: Flask Blueprints for modular routing

---

## Project Structure
```
MUMU/
├── app.py
├── db.py
├── booking.py
├── dashboard.py
├── hi.py
├── hom22.py
├── login.py
├── message.py
├── notification.py
├── profilesetup.py
├── signup.py
├── templates/        # HTML templates
├── static/
│   ├── css/          # Stylesheets
│   ├── images/       # Images & logos
│   ├── js/           # JavaScript files (if any)
│   └── uploads/      # Uploaded user content
└── instance/         # Local instance data (optional)
```

---

## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

2. **Create & activate a virtual environment**
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run MongoDB**  
Make sure you have a local MongoDB instance running on `mongodb://localhost:27017/`.

5. **Start the app**
```bash
export FLASK_APP=MUMU/app.py      # macOS/Linux
$env:FLASK_APP="MUMU/app.py"      # Windows PowerShell
flask run
```
Open your browser and go to: `http://127.0.0.1:5000/`

---

## License
This project is open source and available under the [MIT License](LICENSE).

---
