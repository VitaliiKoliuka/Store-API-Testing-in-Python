# 🛒 Store API Testing in Python

A Python-based API testing project designed to validate Store Fake APIs using modern automation practices. This project demonstrates end-to-end API testing, including data-driven testing and API chaining using `pytest`.

---

## 📌 Project Overview

The project involves building and testing APIs for three modules: **Products**, **Cart**, and **User**. The APIs support CRUD operations, filtering, sorting, user-specific data and date-based queries. The design covers both functional requirements and user story-based scenarios. 

It is built as a **learning + portfolio project** to showcase API automation skills.

---

## 🚀 Key Features

- ✅ API testing using `requests`
- ✅ Test execution with `pytest`
- ✅ Data-driven testing with JSON
- ✅ API chaining (CRUD flow)
- ✅ Reusable fixtures (`conftest.py`)
- ✅ Clean and modular structure

---

## 🛠️ Tech Stack

- **Language:** Python 3  
- **Framework:** Pytest  
- **Libraries:** Requests  
- **Tools:** PyCharm / GitHub  

---

## 📁 Project Structure

Store-API-Testing-in-Python\
│\
├── configurations\
│ └── config.ini\
│\
├── datamodels\
│ ├──__init__.py\
│ ├── Adress.py\
│ ├── Cart.py\
│ ├── CartProduct.py\
│ ├── Geolocation.py\
│ ├── Login.py\
│ ├── Name.py\
│ ├── Product.py\
│ └── User.py\
│\
├── logs\
│ └── test_logging.log\
│\
├── payloads\
│ ├──__init__.py\
│ └── Payload.py\
│\
├── reports\
│ ├── allure-html\
│ ├── allure-results\
│ └── assets\
│\
├── routes\
│ ├──__init__.py\
│ └── Routes.py\
│\
├── testCases\
│ ├──__init__.py\
│ ├── conftest.py\
│ ├── pytest.ini\
│ ├── test_cart_tests.py\
│ ├── test_product_datadriven_tests.py\
│ ├── test_product_tests.py\
│ └── test_user_tests.py\
│\
├── testData\
│ └── product.json\
│\
├── utils\
│ ├──__init__.py\
│ ├── ConfigReader.py\
│ ├── DataProvider.py\
│ └── data_utils.py\
│\
├── requirements.txt # Dependencies\
├── run.bat\
└── README.md


## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/VitaliiKoliuka/Store-API-Testing-in-Python.git
cd Store-API-Testing-in-Python

### 2. Create virtual environment

python -m venv venv

### 3. Activate environment

Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate

### 4. Install dependencies
pip install -r requirements.txt

