# Selenium POM Automation Suite 🚀

## 📌 Project Overview
This project is a robust automation framework designed to test the login functionality of a web application. It uses the **Page Object Model (POM)** to ensure the code is maintainable, readable, and scalable.

## 🛠️ Tech Stack
* **Language:** Python 3.10
* **Framework:** Pytest
* **Library:** Selenium WebDriver
* **CI/CD:** GitHub Actions
* **Pattern:** Page Object Model (POM)

## 🏗️ Framework Structure
- `pages/`: Contains Page Objects (locators and actions).
- `mytest/`: Contains test scripts and `conftest.py` for driver initialization.
- `.github/workflows/`: CI/CD pipeline configuration.

## 🚀 Key Features
- **Headless Execution:** Designed to run on Linux servers without a GUI.
- **Dynamic Waits:** Implemented `WebDriverWait` to handle synchronization issues.
- **CI/CD Integration:** Automated test execution on every `push` to the master branch.
Resolved environment-specific issues between Windows and Linux (GitHub Actions) by implementing headless configurations and flexible PYTHONPATH management.
