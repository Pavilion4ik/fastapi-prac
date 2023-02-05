# fastapi_prac

# Here it`s my practice project
It`s a trade API, where you can record your trading operations.

# How to run
Python3 must be already installed!

```shell
git clone https://github.com/Pavilion4ik/fastapi_prac.git
cd fastapi_prac
python3 -m venv venv 
source venv/bin/activate
pip install -r requirements.txt
uvicorn src.main:app --reload
```

# How to check
You must go to http://127.0.0.1:8000/docs and you will see swagger-documentation for API.

# Technologies used:
* Alembic
* SQLAlchemy
* FastAPI
* FastAPI-users
* FastAPI-cache
* Celery
* Redis
