# 🧪 Automation Testing Website (Selenium + BDD Framework)

## 📌 Project Overview
This is a robust **Automation Testing Framework** developed for an e-commerce web application.

It is built using **Selenium WebDriver, Cucumber (BDD), TestNG, and Java**, following industry-standard automation practices such as **Page Object Model (POM)** and modular test design.

The framework is designed to automate end-to-end user flows including:
- User authentication (Login/Logout)
- Product search and filtering
- Add to cart functionality
- Checkout process
- Order validation

---

## 🏗️ Architecture / Framework Design
This framework follows a **hybrid automation architecture** combining:

- 🧩 Page Object Model (POM)
- 🧪 BDD (Cucumber Feature Files)
- ⚙️ TestNG Test Execution Layer
- 🔁 Reusable Utility Layer
- 🔗 Hook-based setup & teardown

This ensures **scalability, maintainability, and reusability**.

---

## 🚀 Tech Stack
- Java (Core Language)
- Selenium WebDriver
- Cucumber (BDD Framework)
- TestNG (Test Execution & Assertions)
- Maven (Build Tool)
- WebDriver Manager (Browser Management)
- Page Object Model (Design Pattern)

---

## 📂 Project Structure

```
AutomationTestingWebsite/
│
├── src/
│ └── test/
│ ├── java/
│ │ ├── features/
│ │ ├── stepDefinitions/
│ │ ├── runners/
│ │ ├── hooks/
│ │ ├── pages/
│ │ ├── utils/
│ │ └── testData/
│ │
│ └── resources/
│ ├── config/
│ ├── drivers/
│ └── reports/
│
├── pom.xml
└── README.md
```
---

## 🎯 Key Features

- 📌 BDD approach using Cucumber (Gherkin syntax)
- 🧱 Page Object Model (POM) design pattern
- 🔄 Reusable and maintainable framework structure
- 🧪 Automated functional test coverage
- 🌐 Cross-browser testing support
- ⚡ Maven-based dependency management
- 📊 Test execution reports generation
- 🔗 Easy integration with CI/CD pipelines (Jenkins/GitHub Actions)

---

## ▶️ How to Run the Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/AutomationTestingWebsite.git
2️⃣ Import Project

Open in:

IntelliJ IDEA OR
Eclipse IDE
as a Maven Project
3️⃣ Install Dependencies
mvn clean install
4️⃣ Run Tests

You can run tests using:

TestRunner class (Cucumber Runner)
OR testng.xml file
OR Maven command:
mvn test
📊 Reports

After execution, test reports will be available in:

/target

(Depends on reporting plugin used: Cucumber / Extent Reports)

🔧 Future Improvements

CI/CD integration with Jenkins / GitHub Actions
Extent Reports / Allure Reports integration
Parallel test execution
Dockerized test execution environment
API + UI hybrid automation layer

👨‍💻 Author
Sainsa Rethmi Thennakoon
