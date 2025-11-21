# scrapy - MVP

This project fetches recent posts from configured blog RSS or HTML pages, filters them by keywords, builds a compact HTML newsletter, and emails it to you. It supports a local run and scheduled runs via GitHub Actions.

## Quickstart (beginner-friendly)

1. Install Python 3.10+ and Git.

2. Clone or create the repo and open a terminal inside the project folder.

3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # macOS / Linux
   source venv/bin/activate
   # Windows (PowerShell)
   venv\Scripts\Activate.ps1
