# Cypress cucumber with application actions [![Circle CI](https://circleci.com/gh/cypress-io/cypress-example-todomvc.svg?style=svg)](https://circleci.com/gh/cypress-io/cypress-example-todomvc) [![Build status](https://ci.appveyor.com/api/projects/status/6wjyoye82orkkyny/branch/master?svg=true)](https://ci.appveyor.com/project/cypress-io/cypress-example-todomvc/branch/master)

https://www.cypress.io/blog/2019/01/03/stop-using-page-objects-and-start-using-app-actions/
This repo contains an example automation tessting written in Cypress v9 and BDD framework cypress-cucumber-preprocessor.

The tests are written to be directly compared to the official https://computer-database.herokuapp.com/ website.

Each test covers the basic function in herokuapp with BDD Gherkin languages and app actions approach

Refer link: [Stop using Page Objects and Start using App Actions](https://www.cypress.io/blog/2019/01/03/stop-using-page-objects-and-start-using-app-actions/)

## Help + Testing

The steps below will take you all the way through Cypress. It is assumed you have nothing installed except for node + git.

**If you get stuck, here is more help:**

* [Gitter Channel](https://gitter.im/cypress-io/cypress)
* [Cypress Docs](https://on.cypress.io)
* [Cypress CLI Tool Docs](https://docs.cypress.io/guides/guides/command-line)

### 1. Install Node

[NodeJs download](https://nodejs.org/en/download/)

### 2. Install Cypress

[Follow these instructions to install Cypress.](https://docs.cypress.io/guides/getting-started/installing-cypress)

### 3. Install cypress-cucumber-preprocessor

[Fololow these instruction to install and run cypress cucumber BDD](https://www.npmjs.com/package/cypress-cucumber-preprocessor)

### 4. Execute testing for this repo

#### a. install the node_modules
```npm install```

#### b. Run test with cypress headless
```npx cypress run```

![cypress-v9-cucumber-headless](https://user-images.githubusercontent.com/47560307/179453901-25e85b6e-9f5d-4e44-8a7c-b00930f7b133.gif)


#### c. Open Cypress UI and select specs to run
```npx cypress open```

![cypress-v9-cucumber-ui](https://user-images.githubusercontent.com/47560307/179453914-8334e62f-d9a6-47e5-bd61-3f6e0f9beb74.gif)

# Have fun!!!

