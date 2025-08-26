# Simple Flask App for Render Deployment

This is a simple Flask application with Home, About Us, and Service (Calculator) pages.

## How to Deploy on Render

1. Push your code to a GitHub repository.
2. Go to https://render.com and create a new Web Service.
3. Connect your GitHub repository.
4. Set the build and start commands:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
5. Make sure your repository contains:
   - `app.py`
   - `requirements.txt`
   - `Procfile`
   - `templates/` folder with HTML files
6. Deploy and visit your Render URL.

---

### Local Development
Run locally with:
```
python app.py
```

---

### Project Structure
```
app.py
requirements.txt
Procfile
templates/
  home.html
  about.html
  service.html
```
