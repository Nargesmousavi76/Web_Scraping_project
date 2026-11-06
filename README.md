# 💻 Technolife Laptop Scraper & Data Visualization

A Python project that extracts laptop product information from the **Technolife** online store, stores the collected data in an SQLite database, and displays the products in an interactive web application using **Streamlit**.

## 🚀 Project Overview

This project consists of two main Python scripts:

### 1️⃣ Web Scraping & Database (`scraping.py`)

In this part, laptop product information is scraped from the Technolife website using **BeautifulSoup** and **Requests**.

The extracted information includes:

- 📝 Product Description
- 💰 Product Price
- 🖼️ Product Image URL
- 🔗 Product Page Link

All collected information is stored in an SQLite database named `LaptopData.db`.

### 2️⃣ Data Visualization (`app.py`)

In this part, **Streamlit** and **Pandas** are used to retrieve and display laptop information from the SQLite database.

Features:

- 🖼️ Display laptop product images
- 📝 Show product descriptions
- 💰 Display product prices
- 🔗 Provide direct links to product pages
- 📊 Display all collected information in a data table
- 🎨 Organize products in a four-column layout

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| 🐍 Python | Main programming language |
| 🌐 Requests | Sending HTTP requests |
| 🍜 BeautifulSoup4 | Extracting information from HTML |
| 🗄️ SQLite3 | Storing product information |
| 🐼 Pandas | Reading and managing database data |
| 🎈 Streamlit | Creating the web application |

## 📦 Installation

First, install the required libraries:

```bash
pip install requests beautifulsoup4 pandas streamlit
```

## ▶️ How to Run

**Step 1: Run the Web Scraper**

```bash
python scraping.py
```

This script extracts laptop information from Technolife and saves it in `LaptopData.db`.

**Step 2: Run the Streamlit Application**

```bash
streamlit run app.py
```

The application will open in your browser and display the collected laptop products.

## 📂 Project Structure

```text
Laptop_Project/
│
├── scraping.py       # Web scraping and database creation
├── app.py            # Streamlit application
├── LaptopData.db     # SQLite database
└── README.md         # Project documentation
```

## 🎯 Learning Objectives

- 🌐 Practice Web Scraping with Python.
- 🔍 Extract product information from an online store.
- 🗄️ Create and manage SQLite databases.
- 📊 Retrieve and organize data using Pandas.
- 🎨 Build a simple web application with Streamlit.
- 🔗 Work with product images and external links.

---

⭐ **A practical project combining Web Scraping, Database Management, Data Processing, and Web Application Development with Python!**
