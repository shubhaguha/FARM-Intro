Introducing FARM: FastAPI, React, & MongoDB
===

[Blog post](https://www.mongodb.com/developer/how-to/FARM-Stack-FastAPI-React-MongoDB/)

Setup
---

### Backend

```shell
cd backend
python3.9 -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt

export DEBUG_MODE=True
export DB_URL="mongodb+srv://<username>:<password>@<url>/<db>?retryWrites=true&w=majority"
export DB_NAME="farmstack"

python main.py
```

Visit <http://localhost:8000/docs> in your browser.

### Frontend

```shell
cd frontend
npm install
npm start
```

Visit <http://localhost:3000> in your browser.
