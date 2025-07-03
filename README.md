# Student Portal Django Project

A Django-based web portal for students, supporting user management and portal functionality.

## Project Structure

- `manage.py`: Django’s command-line utility for administrative tasks.
- `student/`: Main Django project settings and configuration.
  - `settings.py`: Project settings.
  - `urls.py`: URL routing for the project.
  - `asgi.py`/`wsgi.py`: Entry points for ASGI/WSGI servers.
- `dashboard/`: (App directory; contents not listed, but typically contains views, models, templates, etc.)
- `static/`: Directory for static files (CSS, JS, images, etc.).
- `db.sqlite3`: SQLite database file (auto-generated; not usually uploaded to GitHub).
- `.idea/`: IDE configuration files (PyCharm, etc.).
- `env1/`: Local Python virtual environment (should be excluded via `.gitignore`).
- `.gitignore.txt`: Lists files and directories to be ignored by git.
- `README.md`: Project documentation (this file).

## Getting Started

### Prerequisites

- Python 3.x
- pip
- (Recommended) Virtual environment

### Installation

```bash
git clone https://github.com/NMalik31/Student-Portal-Django.git
cd Student-Portal-Django

# If using virtual environment:
python -m venv env1
env1\Scripts\activate   # On Windows
# source env1/bin/activate   # On macOS/Linux

pip install -r requirements.txt  # If you have a requirements.txt

python manage.py migrate
python manage.py runserver
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## Notes

- The `db.sqlite3` and `env1/` directories are local and should be ignored by git. If not, add them to your `.gitignore.txt`.
- The `dashboard` app handles core portal functionality (see code for details).

## Screenshots

### Home Page
![Home Page](screenshots/screenshot(8))
