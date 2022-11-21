
# REACT BEST PRACTISES 

go to [best practise](https://reactpatterns.com/)

# RUN LINTER
  ```bash
    yarn lint
  ```

# RUN PRETTIER
  ```bash
    yarn format
  ```

# RUN UNIT TEST
  ```bash
    yarn test
  ```

  ```bash
    yarn coverage
  ```

More on [Vitest doc](https://vitest.dev/guide/)

# RUN PLAYWRIGHT TEST (END TO END TEST)

Inside that directory, you can run several commands:

  ```bash
    yarn playwright test
  ```
    Runs the end-to-end tests.

  ```bash
  yarn playwright test --project=chromium
   ```
    Runs the tests only on Desktop Chrome.
  ```bash
  yarn playwright test example
  ```
    Runs the tests in a specific file.
  ```bash
  yarn playwright test --debug
  ```
    Runs the tests in debug mode.
  ```bash
  yarn playwright codegen
  ```
    Auto generate tests with Codegen.

We suggest that you begin by typing:
    ```bash
    yarn playwright test
    ```

More on [playwright doc](https://playwright.dev/docs/intro)

# RUN PROJECT

### Install depedencies
  ```bash
    yarn
  ```

### Run project
  ```bash
    yarn dev
  ```
