# Test Case Rules

Whenever a new test case is added or updated, the following checks must be completed before considering the work done:

1. Run the TypeScript type check:
   npm run type-check

2. Run the lint check:
   npm run lint

3. Run the relevant Playwright test(s):
   npx playwright test
   or a focused run for the affected spec

4. Fix any issues reported by the checks before merging or sharing the work.

5. Keep test names, fixtures, and page objects aligned with the project structure under src.

This rule ensures every new test case is validated, clean, and ready to run.
