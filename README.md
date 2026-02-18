
# Simple Chat Agent

A simple Flask-based chat agent designed to be hosted on [Render](https://render.com).

## How to host on Render

1. Connect your GitHub account to Render.
2. Create a new **Web Service**.
3. Select this repository.
4. Render will automatically detect the settings:
   - **Runtime**: Python
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app:app`
5. Deploy!
