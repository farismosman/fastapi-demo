In this project we consume multiple data files to create a consolidated view as per business requirements.

# Getting Started
1. Clone the repository.
2. Navigate into the cloned directory and create a python virtual environment using virtualenv and pip.
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