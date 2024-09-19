# Project Name

This repository contains both a Flask backend and a React frontend application. Below are the instructions for setting up and running both projects.

## Backend (Flask)

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Setup

1. **Clone the Repository**

   ```

git clone https://github.com/satyajit-patel/llm-back.git
cd llm-back

python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
API_KEY=your_google_api_key
flask --app index run --host=0.0.0.0 --port=5000

git clone <frontend-repo-url>
cd <frontend-repo-directory>
npm install
npm run dev
```

