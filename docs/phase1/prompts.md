# Phase 1 Prompt Summary

This project was configured and corrected as part of the initial setup and validation workflow for the Playwright framework.

## Key requirements captured during the setup

1. Fix the broken Playwright configuration and restore valid bracket structure.
2. Keep the environment-based base URL logic working with QA, DEV, STG, and PROD values.
3. Ensure the custom reporter path resolves correctly from the src folder structure.
4. Update the TypeScript configuration so aliases work for the src layout.
5. Add path mappings for the main folders under src, including api, config, fixture, pages, testData, tests, and utils.
6. Keep TypeScript type checking and linting as mandatory steps for all new or updated test cases.
7. Document the validation rules in the rules folder and in the GitHub Copilot instructions.
8. Maintain project structure and naming consistency under src.

## Mandatory validation rule

Whenever a new or updated test case is added, complete the following before finishing the work:

- npm run type-check
- npm run lint
- npx playwright test

## Repo guidance

- Keep test names, fixtures, page objects, helpers, and utilities aligned with the src folder structure.
- Use the alias-based imports whenever possible for cleaner and safer imports.
- Keep the GitHub Copilot instructions and local rules in sync.
