🛒 Ecommerce Playwright POM Framework

A scalable UI automation framework built with Playwright (JavaScript) using the Page Object Model (POM) design pattern to automate core e-commerce workflows.

This project demonstrates clean architecture, reusable page objects, and cross-browser automation aligned with industry best practices.

🚀 Tech Stack

Playwright

JavaScript (Node.js)

Playwright Test Runner

Page Object Model (POM)

🏗 Framework Design

Clear separation of test logic and page interactions

Centralized locators for easier maintenance

Reusable utility modules

Cross-browser support (Chromium, Firefox, WebKit)

Built-in Playwright auto-waiting for stable execution

📁 Project Structure
pages/        → Page Object classes  
tests/        → Test specifications  
utils/        → Shared utilities  
playwright.config.js  
🧪 Test Coverage

Automated user journeys include:

Login (positive & negative)

Product selection

Add to cart

Cart validation

Checkout flow validation

▶️ Running Tests
npm install
npx playwright install
npx playwright test

View HTML report:

npx playwright show-report
🎯 Purpose

This framework highlights:

Strong automation architecture using POM

Maintainable and scalable test design

Practical implementation of modern UI automation practices
