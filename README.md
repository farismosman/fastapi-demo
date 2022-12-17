This a fastapi project based on https://github.com/marciovrl/fastapi. In the project a few JSON files that get queried based on the incoming request.

# Getting Started
1. Clone the repository.
2. Navigate into the cloned directory and create a python virtual environment using python-3.8 using virtualenv and pip.
3. Activate the environment and install the requirements using
```bash
pip install -r requirements.txt
```
4. Run server

```
uvicorn app.main:app --reload
```

5. Run test

```
pytest test/test.py
```
6. Install and HTTP client such as postman to test the API.
7. The API document can be accessed at http://localhost:8000/docs