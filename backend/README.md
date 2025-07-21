# FastAPI + Neon Postgres

## Local development

1. **Create venv and activate venv**
In Windows Bash navigate to backend directory:
python -m venv .venv
source .venv/Scripts/activate

2. **Install dependencies**
In backend directory:
pip install -r requirements.txt

3. **Configure DB**
In backend/app create a .env file, set DATABASE_URL

4. **Run locally**
In backend/app:
uvicorn main:app --reload
Navigate to provided url

