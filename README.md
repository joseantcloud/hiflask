# HiFlask

A minimal Flask “Hello World” web app that renders a Bootstrap-styled page.

## What’s included

- **Flask app**: serves a single route (`/`) from `app.py`
- **Template**: `templates/index.html` rendered with `render_template`
- **Styling**: Bootstrap via CDN

## Project structure

```text
hiflask/
├─ app.py
└─ templates/
   └─ index.html
```

## Requirements

- Python 3.9+ (any modern Python 3 should work)
- pip

## Setup & run (local)

1. **Clone the repo**
   ```bash
   git clone https://github.com/joseantcloud/hiflask.git
   cd hiflask
   ```

2. **Create & activate a virtual environment**
   - macOS / Linux
     ```bash
     python3 -m venv .venv
     source .venv/bin/activate
     ```
   - Windows (PowerShell)
     ```powershell
     py -m venv .venv
     .\.venv\Scripts\Activate.ps1
     ```

3. **Install dependencies**
   ```bash
   pip install Flask
   ```

4. **Run the app**
   ```bash
   python app.py
   ```

5. **Open in your browser**
   - Visit: `http://127.0.0.1:5000/`

## Development notes

- The server runs with `debug=True` in `app.py`. For production, disable debug and run behind a production WSGI server (e.g., gunicorn/uwsgi).

## License

MIT (or choose your preferred license).