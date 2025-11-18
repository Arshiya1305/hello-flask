# hello-flask

Simple Flask "Hello, World!" web app for demo.

## Run locally

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
export FLASK_APP=app.py    # Windows PowerShell: $env:FLASK_APP="app.py"
flask run

