﻿# e-commerce_site
 # 🧪 TestNG Hybrid Automation Framework

This project showcases a robust automation framework built using **TestNG**, designed to facilitate comprehensive software testing across various modules. It follows a **hybrid framework architecture**, integrating modular, data-driven, and keyword-driven principles to enhance scalability, reusability, and maintainability.

---

## ✅ Key Features

- **Hybrid Framework**: Combines the strengths of multiple automation approaches.
- **Regression Testing**: Automates the validation of application stability after updates.
- **TestNG Integration**: Harnesses the full power of TestNG with grouping, prioritization, and parallel execution.
- **Data Providers**: Facilitates data-driven testing using dynamic datasets.
- **Listeners**: Implements TestNG listeners for real-time event handling during test execution.
- **Extent Reports**: Generates detailed, interactive HTML reports with test logs and statuses.
- **Screenshot Capture**: Automatically captures screenshots for failed test cases to aid debugging.
- **Reusable Utilities**: Includes helper classes for browser setup, logging, reporting, and assertions.
- **Cross-Browser Testing**: Supports multiple browsers using WebDriver configuration.

---

## 🛠️ Technologies Used

- **Java**
- **Selenium WebDriver**
- **TestNG**
- **Apache POI (for Excel-based data provider)**
- **Extent Reports**
- **Log4j (optional for logging)**
- **Maven** (for build and dependency management)

---

## 🧩 Folder Structure

```text
src/
├── test/java/
│   ├── tests/               # Test cases
│   ├── listeners/           # TestNG listeners
│   ├── utils/               # Reusable utilities
│   ├── data/                # Data provider methods
│   └── base/                # Base test class
├── main/resources/
│   ├── testdata/            # Excel or JSON files for test data
│   ├── config.properties    # Configuration settings
reports/                     # Extent report output
screenshots/                 # Failed test screenshots
pom.xml                      # Maven configuration

 🚀 How to Run Tests
Clone the repository.
Set up config.properties with browser and base URL.
Use mvn test to execute the TestNG suite.
Navigate to the reports/ folder to view the Extent Report.
