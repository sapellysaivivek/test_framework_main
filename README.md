# 🚀 Enterprise Selenium Automation Framework

A scalable and maintainable **UI Automation Framework** built using **Python, Selenium, and Pytest** following industry-standard automation practices. The framework automates the **Expand Testing Notes Application** and supports cross-browser execution, Selenium Grid, CI/CD integration, detailed reporting, and AI-assisted locator healing.

---

## 📌 Project Overview

This project demonstrates a production-style automation framework capable of validating end-to-end user workflows through UI automation. The framework is designed with scalability, maintainability, and reusability in mind using the **Page Object Model (POM)**.

---

## ✨ Features

- ✅ Selenium WebDriver Automation
- ✅ Pytest Test Framework
- ✅ Page Object Model (POM)
- ✅ Cross-Browser Testing
- ✅ Selenium Grid Execution
- ✅ Docker Support
- ✅ Jenkins CI/CD Integration
- ✅ Allure Reports
- ✅ Automatic Screenshots on Failure
- ✅ Logging
- ✅ Parallel Execution (pytest-xdist)
- ✅ Test Reruns for Flaky Tests
- ✅ AI-Assisted Self-Healing Locators
- ✅ UI & API Testing

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| UI Automation | Selenium |
| API Testing | Requests |
| Test Framework | Pytest |
| Design Pattern | Page Object Model (POM) |
| Reporting | Allure Reports |
| CI/CD | Jenkins |
| Containerization | Docker |
| Grid Execution | Selenium Grid |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```text
test_framework/
│
├── config/
├── pages/
├── tests/
│   ├── ui/
│   ├── api/
│
├── fixtures/
├── utils/
├── ai/
├── logs/
├── screenshots/
├── reports/
├── allure-results/
├── docker/
├── Jenkinsfile
├── requirements.txt
└── README.md
```

---

# 🧪 Test Coverage

### UI Tests

- Login
- Logout
- Create Note
- Edit Note
- Delete Note
- Validation Messages
- Negative Test Cases

### API Tests

- Authentication APIs
- Create Note
- Get Notes
- Update Note
- Delete Note

### Framework Features

- Cross Browser Testing
- Parallel Execution
- Screenshot Capture
- Logging
- Reporting
- Retry Failed Tests
- AI Locator Healing

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/sapellysaivivek/test_framework_main
```

Navigate into the project

```bash
cd your-repository
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Execute Tests

Run all tests

```bash
pytest -v
```

Run only UI tests

```bash
pytest -m ui
```

Run only API tests

```bash
pytest -m api
```

Run tests in parallel

```bash
pytest -n auto
```

Run with reruns

```bash
pytest --reruns 2 --reruns-delay 5
```

Generate Allure Results

```bash
pytest --alluredir=allure-results
```

Open Allure Report

```bash
allure serve allure-results
```

---

# 🐳 Selenium Grid

Start Selenium Grid

```bash
docker compose up -d
```

Run tests against Selenium Grid

```bash
pytest -m ui
```

---

# 🔄 CI/CD Pipeline

The project integrates with **Jenkins** to automate:

- Source Code Checkout
- Dependency Installation
- Test Execution
- Allure Report Generation
- Build Status
- Test Artifacts

---

# 📊 Reporting

The framework generates:

- Allure Reports
- Screenshots on Failure
- Execution Logs
- Test Results

---

# 📸 Project Screenshots

Add screenshots here:

- Jenkins Pipeline
- Selenium Grid
- Allure Report
- Test Execution

Example:

```
docs/
├── jenkins.png
├── allure.png
└── selenium-grid.png
```

Then display them:

```markdown
## Jenkins Pipeline

![Jenkins](docs/jenkins.png)

## Selenium Grid

![Grid](docs/selenium-grid.png)

## Allure Report

![Allure](docs/allure.png)
```

---

# 🚀 Future Enhancements

- GitHub Actions
- Slack Notifications
- Email Reports
- Performance Testing
- Visual Testing
- Database Validation
- Cloud Browser Execution

---

# 👨‍💻 Author

**Sapelly Sai Vivek**

Recent Computer Science Engineering Graduate

QA Automation Engineer | Python | Selenium | Pytest | Playwright | API Testing | Jenkins | Docker | Selenium Grid

GitHub: https://github.com/sapellysaivivek

LinkedIn: https://[linkedin.com/in/sapelly-sai-vivek](https://www.linkedin.com/in/sapelly-sai-vivek/)

---

## ⭐ If you found this project useful, consider giving it a star!
