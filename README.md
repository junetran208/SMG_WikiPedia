# This is guideline to set up and execute tests
## Test Suite
   ### 1.API-Search.spec.js is testsuite of API test
   ### 2.UI-Wikipedia-Search.spec.js is testsuite of UI test

## Execute Test
### 1. Install Node

[NodeJs download](https://nodejs.org/en/download/)

### 2. Install Cypress

[Follow these instructions to install Cypress.](https://docs.cypress.io/guides/getting-started/installing-cypress)

### 3. Execute testing for this repo

#### a. install the node_modules
```npm install```

#### b. Run test with cypress headless
```npx cypress run```
#### c. Open Cypress UI and select specs to run
```npx cypress open```
