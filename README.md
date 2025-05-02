# Facility-Monitor


# How to Run the Flask App

## Prerequisites
- Python 3.x installed
- `pip` package manager

---

## Steps to Run

1. **Clone the repository (if not already)**
```bash
git clone https://github.com/DonAshley187/Facility-Monitor.git
cd Facility-Monitor

# Create virtual environment
python3 -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (macOS/Linux)
source venv/bin/activate4

#Packages installation
pip install Flask
pip install flask-qrcode
pip install werkzeug
pip install pdfkit

# macOS/Linux
export FLASK_APP=app.py
export FLASK_ENV=development

# Windows (CMD)
set FLASK_APP=app.py
set FLASK_ENV=development

# Windows (PowerShell)
$env:FLASK_APP = "app.py"
$env:FLASK_ENV = "development"

flask run
