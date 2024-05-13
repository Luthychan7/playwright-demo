# 🎭Playwright learning
![Playwright tests status](https://github.com/Luthychan7/playwright-demo/actions/workflows/playwright.yml/badge.svg)

This repo is a playground I'm using to learn test automation with Playwright. It's a work in progress, but it already showcases a few things, such as:

- **Playwright capabilities:**
    - Tests implemented using Typescript
    - Different locator strategies used depending on context
    - Structured the tests logically to have a single assertion per test
    - Tests are [configured](https://github.com/Luthychan7/playwright-demo/blob/main/playwright.config.ts#L34) to run in the three main browser engines: Chromium, Firefox and Webkit.
- **Security features:**
    - Credentials are stored as Github secrets, injected as environment variables
    - Using `.env` for local development (that file is excluded from source control)
- **CI/CD featues:**
    - Tests run automatically for PRs and `main` branch (workflow [here](https://github.com/Luthychan7/playwright-demo/blob/main/.github/workflows/playwright.yml))
    - The test report is accessible as an artifact.
    - This readme file shows the Github actions status badge too.

## Useful links

- [Playwright Docs](https://playwright.dev/docs/intro)
- [Playwright API](https://playwright.dev/docs/api/class-playwright)
