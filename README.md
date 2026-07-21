# playwright-enterprise-framework
# Enterprise Playwright & TypeScript Automation Framework

A production-ready test automation framework built with **Playwright** and **TypeScript**, designed to showcase scalable, maintainable, and robust testing practices for modern web applications and APIs.

---

## 🚀 Features

* **Page Object Model (POM):** Clean separation of test logic and page interactions for high maintainability.
* **Cross-Browser & Multi-Device:** Pre-configured for Chromium, Firefox, WebKit, and mobile viewports.
* **API & UI Testing:** Integrated end-to-end (E2E) UI validation alongside API assertions.
* **CI/CD Integration:** Automated test execution via **GitHub Actions** on every push and pull request.
* **Rich Reporting:** Built-in HTML reports with step-by-step traces, screenshots, and video recordings on failure.
* **Parallel Execution:** Fast execution using Playwright’s native worker-based parallelism.

---

## 🛠️ Tech Stack

* **Core:** Playwright, TypeScript, Node.js
* **CI/CD:** GitHub Actions
* **Reporting:** Playwright HTML Reporter

---

## 📁 Project Structure

```text
.
├── .github/
│   └── workflows/          # GitHub Actions CI pipeline configuration
├── pages/                  # Page Object Model classes
├── tests/
│   ├── api/                # API test suites
│   ├── e2e/                # End-to-end UI scenarios
│   └── fixtures/           # Custom Playwright fixtures
├── playwright.config.ts    # Global Playwright configuration
├── package.json
└── README.md

⚙️ Getting Started
Prerequisites
Node.js (v18 or higher)

npm or yarn

Installation
Clone the repository:

Bash
git clone [https://github.com/zanellilucastomas-web/playwright-enterprise-framework.git](https://github.com/zanellilucastomas-web/playwright-enterprise-framework.git)
cd playwright-enterprise-framework
Install dependencies:

Bash
npm install
Install Playwright browsers:

Bash
npx playwright install --with-deps
🧪 Running Tests
Run all tests (Headless):

Bash
npx playwright test
Run UI tests in headed mode:

Bash
npx playwright test --headed
Run tests in interactive UI Mode:

Bash
npx playwright test --ui
Generate and view the HTML Report:

Bash
npx playwright show-report
🔄 CI/CD Pipeline
This project includes a GitHub Actions workflow (.github/workflows/playwright.yml) that automatically:

Triggers on pushes and pull requests to main.

Installs required dependencies and browser binaries.

Runs the test suite in parallel.

Uploads test execution reports as artifacts upon run completion.
