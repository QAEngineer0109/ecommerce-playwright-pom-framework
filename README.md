🛒 E-Commerce Playwright POM Framework
📌 Overview

This project is a Playwright-based end-to-end automation framework built using the Page Object Model (POM) design pattern.

It automates key user flows of an e-commerce application including:

User Login

Add to Cart

Complete Purchase

Affiliate Registration

Order Confirmation Validation

The project is integrated with GitHub and executed through Jenkins CI.

🧰 Tech Stack

Playwright

JavaScript (Node.js)

Page Object Model (POM)

Git & GitHub

Jenkins (CI Integration)

📂 Project Structure
ecommerce-playwright-pom-framework/
│
├── pages/              # Page Object classes
├── tests/              # Test specifications
├── playwright.config.js
├── package.json
└── README.md
📄 Pages Folder

Contains reusable page classes:

HomePage

LoginPage

ProductPage

CheckoutPage

AffiliatePage

AccountPage

Each page encapsulates:

Locators

Actions

Assertion helper methods (where applicable)
🧪 Test Strategy

This framework follows the Page Object Model (POM) pattern:

Page classes contain:

UI locators

Reusable action methods

UI assertion helpers

Test files contain:

Test logic

Test data

Expected results

This separation improves:

Maintainability

Reusability

Readability

Scalability

▶️ Running Tests Locally
Install Dependencies
npm install
Run All Tests
npx playwright test
Run Specific Test
npx playwright test tests/TC04_CompletePurchase.spec.js
Run in Headed Mode
npx playwright test --headed
🏷️ Tagged Test Execution

The framework supports running tests by tags:

npm run regression
npm run sanity
npm run datadriven

(Ensure test cases include appropriate tags.)

🔁 Continuous Integration (CI)

This project is integrated with Jenkins:

Source Code Management: GitHub

Build Trigger: Manual / SCM Polling

Execution: Playwright CLI via Jenkins job

Result Reporting: Console Output & Playwright Reports

🎯 Key Features

Modular Page Object Design

Parameterized methods (e.g., login, form submission)

Dynamic date handling

CI/CD integration

Structured test organization

📚 Learning Objectives

This project was developed as part of structured automation training to:

Strengthen understanding of POM architecture

Practice refactoring tests into reusable page methods

Integrate Playwright with Jenkins

Improve debugging and CI troubleshooting skills

🚀 Future Improvements

Environment-based configuration (dev/stage/prod)

Test data externalization

.env credential handling

Parallel test optimization

Enhanced reporting integration

👨‍💻 Author

QA Automation Engineer transitioning from manual to automation testing.
Focused on building maintainable automation frameworks and CI-integrated test pipelines.
