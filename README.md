# Pennywise - Micro-expense & Subscription Dashboard

Run locally:
    python -m pip install -r requirements.txt
    python app.py
Open http://127.0.0.1:5000

Deploy on Render:
    Build Command: pip install -r requirements.txt
    Start Command: gunicorn app:app

Note: SQLite (microexpense.db) is created automatically. On Render's free tier the disk is
wiped on each redeploy, so data resets unless you attach a persistent disk.
