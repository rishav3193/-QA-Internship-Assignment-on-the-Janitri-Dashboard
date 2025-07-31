# -QA-Internship-Assignment-on-the-Janitri-Dashboard
# 🧪 Janitri Dashboard – Login Page Test Automation

This repository contains manual and automated test cases for the login page of the **Janitri Dashboard**.

> ✅ Task Completed as part of a QA Internship Assignment  
> 🔗 Test URL: [https://dev-dash.janitri.in](https://dev-dash.janitri.in)

---

## 📌 Project Structure

JanitriLoginAutomation/
├── pom.xml
└── src/
└── test/
├── base/
│ └── BaseTest.java
├── pages/
│ └── LoginPage.java
└── tests/
└── LoginTest.java


---

## 🔧 Tech Stack

- **Java**
- **Selenium WebDriver**
- **TestNG**
- **Maven** (for dependency management)
- **Page Object Model (POM)** design pattern

---

## ✅ Manual Test Cases

A comprehensive `.xlsx` file with 10+ test cases is included separately.  
It includes:
- Functional Tests
- UI Tests
- Negative Scenarios
- Boundary Tests

> 📁 File: `Login_Test_Cases.xlsx`

---

## 🔁 Automated Test Scenarios

All tests are implemented using **TestNG + POM structure**.

| Test Case | Description |
|-----------|-------------|
| `testLoginButtonDisabledWhenFieldsAreEmpty` | Checks if login button is disabled when fields are blank |
| `testPasswordMaskedButton` | Verifies password masking and toggle visibility |
| `testInvalidLoginShowErrorMsg` | Enters random credentials and verifies error message |
| `testPageElementsPresence` | Validates presence of email, password, login button, eye icon |

---

## 🚀 How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/your-username/JanitriLoginAutomation.git
cd JanitriLoginAutomation

#mvn clean install
#mvn test


