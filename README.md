# Books Online - Price Monitoring System

This repository contains a beta version of a price monitoring system for **Books Online**. The system extracts book details from [Books to Scrape](http://books.toscrape.com/) and saves the data as CSV files.

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Output](#output)

---

## Installation

To set up and run the project, follow these steps:

### 1. Clone the Repository

```sh
git clone https://github.com/jrmenges/Python_Basics.git
cd Python_Basics
```

### 2. Create and Activate a Virtual Environment

#### Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Jupyter Notebook (if not already installed)

```sh
pip install notebook
```

---

## Running the Application

Start **Jupyter Notebook** by running:

```sh
python -m notebook
```

Then open the appropriate notebook:

- **Project**: `Book_Scrape_Project.ipynb`

Run each notebook cell sequentially to execute the scripts.

---

## Output

The extracted data is stored as a CSV file inside the root folder. The images are stored in `/Book Images`.
