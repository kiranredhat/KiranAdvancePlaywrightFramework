# Kiran Advance Playwright Framework

## 1. Overview
This project is a Playwright automation framework built for UI testing with a structured src-based architecture.

## 2. Tech Stack
- Playwright
- TypeScript
- Node.js
- ESLint
- Dotenv
- Allure and HTML reporting

## 3. Project Structure
- src/api
- src/config
- src/fixture
- src/pages
- src/testData
- src/tests
- src/utils
- rules/
- .github/

## 4. Installation
```bash
npm install
```

## 5. Environment Configuration
Create a local environment file and set the required base URLs and environment values.

Example:
```bash
TTA_ENV=qa
QA_BASE_URL=https://app.thetestingacademy.com
```

## 6. Running Tests
```bash
npx playwright test
```

## 7. Running a Specific Browser
```bash
npx playwright test --project=chromium
npx playwright test --project=firefox
npx playwright test --project=webkit
```

## 8. Type Check
```bash
npm run type-check
```

## 9. Linting
```bash
npm run lint
```

## 10. Reporting
The framework generates:
- HTML report
- JSON report
- Allure report

## 11. Required Rule for New Test Cases
For every new or updated test case, the following checks must be completed before finishing the work:

```bash
npm run type-check
npm run lint
npx playwright test
```

## 12. GitHub Copilot Rules
The repo also includes a Copilot instruction file in [.github/copilot-instructions.md](.github/copilot-instructions.md) that follows the same validation requirement.

## 13. Final Notes
This project follows a consistent src-first structure and a strict validation workflow so automated tests remain clean, reliable, and maintainable.
