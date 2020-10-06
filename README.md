Workshop

Basic folder structure example:

.
├── app_cleaner
│   ├── Dockerfile
│   └── src
│       └── test
│           ├── __init__.py
│           ├── __pycache__
│           │   ├── __init__.cpython-38.pyc
│           │   └── test_ex.cpython-38.pyc
│           └── test_ex.py
├── app_mlflow
│   └── Dockerfile
├── app_model
│   ├── Dockerfile
│   └── src
│       ├── model
│       │   ├── __init__.py
│       │   └── train.py
│       └── test
│           ├── __init__.py
│           └── test_train.py
├── clean_data
├── docker-compose.yml
├── LICENSE
├── model_data
├── raw_data
│   ├── googleplaystore.csv
│   ├── googleplaystore_user_reviews.csv
│   └── license.txt
└── README.md