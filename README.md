# 🧪 QA API Test Suite

Automated API testing lab using `pytest` and `requests` to validate endpoints from the [JSONPlaceholder](https://jsonplaceholder.typicode.com) fake REST API.

## 🔧 Tech Stack

- Python 3.x
- Pytest
- Requests

## 📋 Test Cases

| Endpoint             | Test Description                  |
|----------------------|------------------------------------|
| `/users`             | Validate status and response shape |
| `/users/{id}`        | Parametrized test for known users  |
| `/users/999`         | Check behavior on invalid user ID  |

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/qa-api-lab.git
   cd qa-api-lab
