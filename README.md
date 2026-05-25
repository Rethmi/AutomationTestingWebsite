# 🧪 Automation Testing Website

## 📌 Overview
This is an Automation Testing Framework for an e-commerce web application.  
It is built using **Selenium WebDriver, Cucumber, TestNG**, and follows the **BDD (Behavior Driven Development)** approach.

The project automates key user flows such as login, product search, cart operations, and checkout process.

---

## 🚀 Tech Stack
- Java
- Selenium WebDriver
- Cucumber (BDD)
- TestNG
- Maven
- Page Object Model (POM)

---

## 📂 Project Structure

src/test/java
│
├── features # Cucumber feature files
├── stepDefinitions # Step definition classes
├── runners # Test runner classes
├── hooks # Setup & teardown hooks
├── pages # Page Object Model classes
│
src/test/resources
│
├── config # Configuration files


---

## 🎯 Features
- BDD framework using Gherkin syntax
- Page Object Model (POM) design pattern
- Reusable and maintainable test scripts
- Test execution using TestNG
- Cross-browser testing support (optional)
- Easy integration with CI/CD pipelines

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/AutomationTestingWebsite.git
Step 1:

Import project into IntelliJ / Eclipse as a Maven project

Step 2:

Install dependencies:

mvn clean install
Step 3:

Run tests:

Run TestRunner class
or
Execute testng.xml
📊 Reports

After execution, test reports will be generated in:

/target/cucumber-reports
👨‍💻 Author

Sainsa Rethmi Thennakoon
