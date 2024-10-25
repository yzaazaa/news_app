# News App

A simple web application for seeing news using the python news api client

---

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)

---

## Requirements

- Python 3.8+
- Django 3.2+
- SQLite (default database, can be configured for others)
- Other dependencies listed in `requirements.txt`

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yzaazaa/news_app.git
cd news_app
python3 -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

```bash
SECRET_KEY=your-secret-key
NEWSAPI_KEY=your-api-key
```
Generate Secret key: https://djecrety.ir/
Generate news api key: https://newsapi.org/


### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

Visit http://localhost:8000 in your browser
