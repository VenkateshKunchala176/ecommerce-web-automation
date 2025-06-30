# 🛒 E-Commerce Web Automation Framework

## 📌 Project Summary
An end-to-end Selenium TestNG framework built for automating user journeys on an e-commerce platform. This framework is designed following QA best practices, with CI integration and robust reporting.

## 🔧 Tech Stack
- Java + Selenium WebDriver
- TestNG (for test orchestration)
- Page Object Model (POM)
- Postman (API testing)
- Jenkins (CI/CD)
- Maven (build & dependency management)

## 🧪 Features
- Scalable test structure using Page Object Model
- Data-driven testing using TestNG XML and external files
- Automated API tests via Postman for integrated flows
- CI pipeline with Jenkins & GitHub Actions
- Auto-screenshot & logging on test failure

## 🚀 How to Run
1. Clone this repo
2. Import into IntelliJ or Eclipse
3. Run using TestNG or via Maven:
   ```bash
   mvn clean test
   ```

## 📂 Folder Structure
```
src/test/java
  ├── pages        # Page classes for POM
  ├── tests        # Test classes
  └── utils        # Helpers (e.g., driver setup, logging, config)
testdata/          # External data files
reports/           # Screenshots, logs
.github/workflows/ # GitHub Actions CI
```
