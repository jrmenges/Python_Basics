# Books Online - Price Monitoring System

This repository contains a beta version of a price monitoring system for **Books Online**. The system extracts book details from [Books to Scrape](http://books.toscrape.com/) and saves the data as CSV files.

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Output](#output)

---

## Installation

To set up and run the project, follow these steps:

### 1. Open Command Prompt/Terminal

#### Windows:
```sh
1. Press 'Win + R' on your keyboard.
2. Type 'cmd' and press 'Enter'
3. A Command Prompt window will open.
```

#### macOS:
```sh
1. Press `Command (⌘) + Space` to open Spotlight Search.
2. Type `Terminal` and press `Enter`.
```

### Linux:
```sh
1. Use the shortcut `Ctrl + Alt + T` to open the terminal.
2. Alternatively, open the **Applications Menu**, search for **Terminal**, and click on it.
```

### 2. Clone the Repository

```sh
In the Command Prompt/Terminal:
1. Type: git clone https://github.com/jrmenges/Python_Basics.git
2. Press Enter
3. Type: cd Python_Basics
4. Press Enter
```

### 3. Create and Activate a Virtual Environment

#### Windows:
```sh
In the Command Prompt:
1. Type: python -m venv venv
2. Press Enter
3. Type: venv\Scripts\activate
4. Press Enter
```

#### macOS/Linux:
```sh
In the Terminal:
1. Type: python3 -m venv venv
2. Press Enter
3. Type: source venv/bin/activate
4. Press Enter
```

### 4. Install Requirements

```sh
In the Command Prompt/Terminal:
1. Type: pip install -r requirements.txt
2. Press Enter:
```
---

## Running the Application

Start **Jupyter Notebook** by running:

```sh
python -m notebook
```

Then open the appropriate notebook:

- **Project**: `Phase_4.ipynb`

Run each notebook cell sequentially to execute the scripts.

---

## Output

The extracted data is stored as a CSV file inside the root folder. The images are stored in `/Book Images`.
