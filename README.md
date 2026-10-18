# LifeLine AI — The Emergency Resource Intelligence Network

**Tagline:** The right resource. The right place. The right time.

## About
LifeLine AI is a web-based emergency resource coordination prototype. It manages emergency requests for blood, medical supplies, and ambulances, tracks request status, and displays resource-demand analytics.

## Features
- Submit emergency resource requests
- View and manage requests
- Update request status
- Analyze resource demand, urgency, and locations
- Highlight unresolved critical requests
- Rule-based request prioritization

## Technologies
- Frontend: HTML, CSS, JavaScript
- Backend: Python, FastAPI
- Database: SQLite
- ORM: SQLAlchemy

## Run locally
Install Python and the dependencies:

```bash
pip install -r requirements.txt
```

From the project root, start the backend:

```bash
python -m uvicorn backend.main:app --reload
```

In a second terminal, start the frontend:

```bash
cd frontend
python -m http.server 5500
```

Open `http://127.0.0.1:5500/index.html` in your browser.

The current prototype runs locally. IBM LinuxONE deployment and integration with real-world resource providers are planned future work.
