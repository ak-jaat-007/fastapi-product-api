# 🧾 Inventory Management Backend API

A small backend application to manage inventory for a small business using **FastAPI** and **SQLite**.

---

## 📦 Features

- ✅ User authentication with token-based login (OAuth2)
- ✅ Add new products
- ✅ Update product quantity
- ✅ View all products with their quantities
- ✅ API documentation via Swagger UI

---

## 🚀 Setup Instructions

### 1. Clone the Project

```bash
git clone https://github.com/ak-jaat-007/fastapi-product-api.git
cd fastapi-product-api
```

### 2. Create Virtual Environment & Activate

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Initialize the Database

```bash
python init_db.py
```

### 5. Run the FastAPI Server

```bash
uvicorn main:app --reload
```

---

## 📘 API Documentation

Once the server is running, visit:

- Swagger UI: [http://localhost:8000/docs](http://localhost:8000/docs)
- ReDoc: [http://localhost:8000/redoc](http://localhost:8000/redoc)

---

## 🧾 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

- GitHub: [@ak-jaat-007](https://github.com/ak-jaat-007)
