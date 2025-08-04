# 🧪 QA API Test Suite

An end-to-end REST API test lab built and automated by me to showcase QA engineering skills.  

This project demonstrates black-box testing, API validation, automation workflows, and live test reporting — all powered by Python and hosted via GitHub Pages. 

---

##  🚀  Live Demo
[![Live Demo](https://img.shields.io/badge/Demo-Click_Here-green?style=for-the-badge)](https://codemagicianequinox.github.io/QA-API-Test-Lab/)

🔹 Click the demo button above to view a simulated test output report powered by a static HTML/JS frontend and dynamically loaded test result file.

---

## 🔧 Tech Stack

- 🐍 **Python 3.x** — Scripting and test logic  
- 🧪 **Pytest** — Test framework  
- 🌐 **Requests** — HTTP client for REST calls  
- 🖥️ **Bash CLI** — Automation and test execution  
- 🗂️ **Git + GitHub** — Version control + code hosting  
- 🕸️ **GitHub Pages** — Hosting for the HTML-based test report viewer  

---

## 📋 Test Cases

The suite uses `pytest` to perform automated testing against [JSONPlaceholder](https://jsonplaceholder.typicode.com), a free fake REST API for prototyping and testing.

| Endpoint             | Test Description                  |
|----------------------|------------------------------------|
| `/users`             | Validate status and response shape |
| `/users/{id}`        | Parametrized test for known users  |
| `/users/999`         | Check behavior on invalid user ID  |

---

## 🧪 Key Features

- ✅ REST API functional validation  
- ✅ Parametrized test coverage  
- ✅ CLI automation with `pytest`  
- ✅ Dynamic test report viewer in the browser  
- ✅ Clean UI built with HTML + JavaScript  
- ✅ Fully hosted on GitHub (code + demo)

---


## 🛠 How to Run Locally 

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/qa-api-lab.git
   QA-API-Test-Lab

2. Install dependencies:
   ```bash
   Copy
   Edit
   pip install -r requirements.txt

3. Run the test suite:
   ```bash
   pytest tests/

4. (Optional) Generate your own test report:
   ```bash
   pytest tests/ > docs/test_report.txt
   
---

## 📌 Notes

- All tests use live public endpoints, so the lab is runnable without setup.

- This repo is intentionally designed to mimic a QA Engineer workflow — from test case to visual reporting.
