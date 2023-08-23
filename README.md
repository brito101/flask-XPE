# Steps

1. Create virtual environment: `python3 -m venv ./env`

2. Active virtual environment: `source ./env/bin/activate`

3. Install Django: `pip3 install flask`

4. Version check: `python3 -m flask --version`

5. Freeze requirements: `pip3 freeze > requirements.txt`

6. Create app.py

7. Declare Flask APP: `set FLASK_APP = app.py`

8. Start web application: `flask run`

9. HML Form: `pip3 install flask-wtf && pip3 freeze > requirements.txt`

10. Install Migrate: `pip3 install Flask-Migrate && pip3 freeze > requirements.txt`

11. Install ALCHEMY: `pip3 install flask-sqlalchemy && pip3 freeze > requirements.txt`

12. Create Model

13. `flask db init`

14. `flask db migrate`

15. `flask db upgrade`
