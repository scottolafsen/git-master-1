
### Why write tests it feels lame almost insulting! 
Manual testing(logging, clicking) is useful in certain cases, but that it simply doesn't scale.
It is a time consuming and error-prone way to test code. To the first point, taking the time to call functions and reload pages with different configurations can take up to a minute at a time. To the second, point out that it´s difficult to ensure you execute the same click sequences with the same settings in different configurations — e.g., checking behavior in Firefox vs Chrome. Tests are programs that automatically check the validity of your programs. Writing a bunch of tests for your code eliminates certain problems of scalability and it becomes clear as you do it.

### What do tests do?
Catch errors!

Two types of errors :
- Bugs, or code that "works incorrectly"; and
- Errors, sometimes called exceptions, caused by code that fails due to unhandled exceptional circumstances. Instances of Error objects are thrown when runtime errors occur.

### Types of tests in Javascript Stack
Unit tests: A single piece of code (usually an object or a function) is tested, isolated from other pieces
Integration tests: Multiple pieces are tested together, for example testing database access code against a test database
Acceptance tests (also called Functional tests): Automatic testing of the entire application, for example using a tool like Selenium to automatically run a browser.

Unit tests
You run unit tests constantly during the development process to ensure that everything is working, every time you make a change.

Integration tests
You use integration tests when you add new code to pre-existing code, to make sure that not only do all of the pieces work individually as expected, but also that they run together correctly without breaking.

End-to-end testing
Run your application from start to finish for all the user stories you can think of. This ensures that the program is ready to go live, and that the special details of deployment do not mess up the code you carefully tested on your local machine with unit tests and integration tests. You conduct end-to-end tests occasionally, maybe only a few times during a product's life-cycle, as they are very time consuming and expensive.

UI Tests/Functional Tests
Testing scenarios on the product itself, by controlling the browser or the website, regardless of the internal structure to ensure expected behavior.
Functional testing is also sometimes called E2E testing, or browser testing. They all refer to the same thing.

Test tools can be divided into the following functionalities. Use a combination.
Provide a testing structure (Mocha, Jasmine, Jest, Cucumber)
Provide assertions functions (Chai, Jasmine, Jest, Unexpected)
Generate, display, and watch test results (Mocha, Jasmine, Jest, Karma)
Generate and compare snapshots of component and data structures to make sure changes from previous runs are intended (Jest, Ava)
Provide mocks, spies, and stubs (Sinon, Jasmine, enzyme, Jest, testdouble)
Generate code coverage reports (Istanbul, Jest, Blanket)
Provide a browser or browser-like environment with a control on their scenarios execution (Protractor, Nightwatch, Phantom, Casper)
https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3

Tests are frequently used in three ways
During development, for developer feedback. Unit tests are particularly helpful here.
In the staging environment, to detect problems and stop the deploy process if something goes wrong. Typically the full suite of all test types are run at this stage.
In the production environment, a subset of production-safe functional tests known as smoke tests are run to ensure that none of the critical functionality was broken during the deploy process.
Each kind of test has a job to do
User experience tests (end user experience)
Developer API tests (developer experience)
Infrastructure tests (load tests, network integration tests, etc…)
https://www.sitepoint.com/javascript-testing-unit-functional-integration/

Tip:
Unit tests should be your main focus when testing JavaScript code. They are the easiest to write and maintain, and provide many benefits beyond reducing bugs. Integration and functional tests should be in a supporting role, for where unit tests are not suitable.

Continuous Integration

MORE TEST explanations
https://stackoverflow.com/questions/520064/what-is-unit-test-integration-test-smoke-test-regression-test

TDD or Test-Driven Development, and BDD or Behavior-Driven Development.
https://codeutopia.net/blog/2015/03/01/unit-testing-tdd-and-bdd/

JavaScript Testing: Unit vs Functional vs Integration Tests
https://www.sitepoint.com/javascript-testing-unit-functional-integration/

https://github.com/jsdom/jsdom

https://github.com/atinfo/awesome-test-automation/blob/master/javascript-test-automation.md




