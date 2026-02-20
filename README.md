# 🛒 E-Commerce Playwright POM Framework

## 📌 Overview

This project is a Playwright-based end-to-end automation framework built using the Page Object Model (POM) design pattern.

It automates key user flows of an e-commerce application including:

- User Login
- Add to Cart
- Complete Purchase
- Affiliate Registration
- Order Confirmation Validation

The project is integrated with GitHub and executed through Jenkins CI.

---

## 🧰 Tech Stack

- Playwright
- JavaScript (Node.js)
- Page Object Model (POM)
- Git & GitHub
- Jenkins (CI Integration)

---

## 📂 Project Structure

- pages/
- tests/
- playwright.config.js
- package.json
- README.md

---

## 🧪 Test Strategy

This framework follows the Page Object Model (POM) pattern.

### Page classes contain:
- UI locators
- Reusable action methods
- UI assertion helpers

### Test files contain:
- Test logic
- Test data
- Expected results

This separation improves:
- Maintainability
- Reusability
- Readability
- Scalability

---

## ▶️ Running Tests Locally

Install dependencies:

npm install

Run all tests:

npx playwright test

Run in headed mode:

npx playwright test --headed

---

## 🔁 Continuous Integration (CI)

This project is integrated with Jenkins:

- Source Code Management: GitHub
- Execution: Playwright CLI via Jenkins job
- Result Reporting: Playwright reports

---

## 🎯 Key Features

- Modular Page Object Design
- Parameterized methods (login, form submission)
- Dynamic date handling
- CI/CD integration
- Structured test organization

---

## 👨‍💻 Author

QA Automation Engineer transitioning from manual to automation testing.
Focused on building maintainable automation frameworks and CI-integrated test pipelines.

