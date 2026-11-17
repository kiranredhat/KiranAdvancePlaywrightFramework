# Copilot Instructions for Test Changes

For every new or updated test case, complete the required validation before finalizing the work:

1. Run the TypeScript type check:
   npm run type-check

2. Run the lint check:
   npm run lint

3. Run the relevant Playwright test(s):
   npx playwright test
   or a focused run for the affected spec

4. Fix any issues reported by the checks before merging or sharing the work.

5. Keep test names, fixtures, page objects, and utilities aligned with the src folder structure.

This is required for all new test cases and test updates.
