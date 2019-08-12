<p align="center">
 <img src="_images-angular-unit-testing-jasmine-karma/1-angualr-jasmine-karma-logo-1.png" alt="Angular Jasmine Karma Logo" title="Angular Unit Testing with Jasmine Karma" width="400" />
</p>

Angular Unit Testing with Jasmine and Karma
=====================

Welcome
---------------------

About the Course/Tutorial
---------------------

Hello Everyone! Welcome to the `Angular Unit Testing Tutorial with Jasmine and Karma`. Let us dive into a topic which lots of developers/technical professionals are struggling and afraid of - `Testing our code`. In this section, we will learn how to write an automated test for Angular Applications. 

In this course/tutorial, will take you from the basics/ground and gives you a solid foundation to write automated tests for your Angular apps. Whether you're an absolute beginner or have some familiarity with automated testing, this course/tutorial will give you all the necessary building block skills to write automated tests for your Angular apps. 

Who is this for? 
---------------------

This Course/Tutorial is ideal for:
- Freshers and aspiring UI (JavaScript/Angular) developers
- Absolute beginner Angular developers (Front-End developer)
- Experienced Technical developers
- Developers upgrading from AngularJS 1.x to Angular 2 or above
- Full Stack Developers
- Technical/Team Leads
- Architects, Technical Project Managers, QAs

This course/Tutorial is for anyone and everyone, Almost everyone! Fresher/Newcomer as well as experienced UI/frontend/Web Developers who are interested in boost skills and further career in Angular world - by learning new latest dynamic tools/utilities which helps to Test Angular application code to become a hi-tech developer.

Why learn Angular Unit Testing with Jasmine & Karma
---------------------
- Writing Unit/Integration Test cases and testing code is an art, it helps to produce a product with fewer bugs and better quality
- Tests are the best way to prevent software defects
- In the long run for large applications, manual testing ends up with extreme pain and time-consuming. With automated testing, you spend less time fixing bugs and testing code
- Automated testing is a practice that has been adopted by various organizations and a lot of successful software development teams so Unit Testing becomes a popular skill to learn, know and use

Course/Tutorial achievement
---------------------

Course/Tutorial Goal
---------------------

After completing/attending this Course/Tutorial, participants should be able to: 
1. Write Unit and Integration test cases for Angular application using Jasmine
2. Write clean and maintainable tests for your Angular apps
2. Feel comfortable writing Angular tests for testing Functions, Logics, Events, multiple types of Components, Attributes-Directives, Dependencies, Routers- Navigation, and services
3. Know and get familiar with Angular testing best practices

Prerequisites for current course / What you need to know
---------------------
The primary focus for this tutorial is testing Angular Applications and code so it is must to know Angular (version 2 and above) and TypeScript. It is advisable to view course/tutorial on Angular - [Angular step by step](https://github.com/dinanathsj29/angular7-step-by-step) and Typescript [Typescript tutorial for all](https://github.com/dinanathsj29/typescript-tutorial) before dive deeper with Angular testing.

Topics included/covered
=====================
1. [Introduction to Automated testing](#1-introduction-to-automated-testing)
    - 1.1. [Common questions in mind of developers](#11-common-questions-in-mind-of-developers)
    - 1.2. [Developers thoughts](#12-developers-thoughts)
    - 1.3. [What is automated testing?](#13-what-is-automated-testing)
    - 1.4. [Is it a replacement for manual testing?](#14-is-it-a-replacement-for-manual-testing)
    - 1.5. [Codebase to develope](#15-codebase-to-develope)
    - 1.6. [Why Test?](#16-why-test)
    - 1.7. [Benefits/Advantages of Automated Testing](#17-benefits-advantages-of-automated-testing)
    - 1.8. [Do I need Automated testing?](#18-do-i-need-automated-testing)
    - 1.9. [First code or write the test?](#19-first-code-or-write-the-test)
    - 1.10. [What to test?](#110-what-to-test)

2. [Different types of tests](#2-different-types-of-tests)
    - 2.1. [Unit Test](#21-unit-test)
    - 2.2. [Integration Test](#22-integration-test)
    - 2.3. [End-to-End or End-2-End or E2E Test](#23-end-to-end-test)
    - 2.4. [The testing pyramid](#24-the-testing-pyramid)
    
1 Introduction to Automated testing
=====================

1.1. Common questions in mind of developers
---------------------

- What is automated testing?
- Is it a replacement for manual testing?
- Do I need Automated testing?
- Do I write Test first (TDD - Test Driven Development) or application code first?
- What to test?

1.2. Developers thoughts
---------------------

`Testing our code is an important and integral part of any project` but the majority of developer/technical professionals doesn't follow it, because:
- Testing looks complex
- Its time consuming
- Developers are not clear about Testing
- Don't know how to work with Testing
- No clear idea/picture what to test 

1.3. What is automated testing?
---------------------

> **Automated testing** 
- Testing is the process of checking the code/functionality manually or in an automated fashion
- Automated testing is `process/practice of writing code to test our code`, then run tests in an automated fashion
- Automated testing is performed by writing test cases/scripts

1.4. Is it a replacement for manual testing
---------------------
1.4. Development and Testing Life cycle
---------------------

Both Manual Testing & Automated Testing have their own advantages and disadvantages. 
- For smaller applications, Manual Testing is beneficial at the same time 
- Large enterprise applications Automated Testing play an important role 
- Some project/software application (in which requirements changes frequently, R & D Projects) Manual Testing is the best option
- Also in some project/software application combination of both Manual Testing & Automated Testing works and fit fine (complex things checked manually and dynamic things can be automated tested)

### Manual Testing Process Life cycle
1. **<u>Code</u>** - We Develop some code/features
2. **<u>Results</u>** - We have some expected results in mind
3. **<u>Test</u>** - We Test/check applicaton
 - If all looks good/works fine - `success confirmation` - develope other next piece code/feature
 - If any error/not happy with code - `Failure` - Modify/Fix and test again

### Automated Testing Process Life cycle
1. **<u>Code</u>** - We Develop some code/features
2. **<u>Results</u>** - We have some expected results in mind
3. **<u>Test</u>** - We can Automate and Simply Tests 
 - We can test some part manually
 - At the same time write test cases/automate some task to avoid manual and time-consuming interaction
 - Automate testing helps to get breaking changes/last-minute code shocking changes at the initial level itself

Whenever we develop any application we need to test it. Sometimes the test is performed manually by developer/QA team member or at a time we prefer writing an Automated Unit Test.

Test-Driven Development is a single powerful tool to prevent bugs, defects from within our application. By putting some efforts on Testing we get better quality software with fewer bugs which is more maintainable in the long term.

### Manual testing process/steps
1. Launch application in the browser
2. Login to application
3. Go to the target page
4. Follow proper steps and do some clicks here there to test & check, code or functionality developed
5. Test/check positive and negative both scenarios for particular functionality/function

`All the way manual testing is pretty time consuming, to follow all the steps/cycle discussed above, we may need a couple of minutes.`

### Automated testing process/steps
`We can write code, directly call the function with different positive and negative input values, and test functionality/function in a fraction of the moment.`

1.5. Codebase to develope
---------------------

With Automated testing, we have to `write Production Code as well as Unit Test Code`, so it `takes significantly more time` as compared to normal development time.

<p>
 <figure>
 &nbsp;&nbsp;&nbsp; <img src="_images-angular-unit-testing-jasmine-karma/1.5.1-codebase-to-develop.png" alt="Codebase to develop" title="Codebase to develop" width="800" />
 <figcaption>&nbsp;&nbsp;&nbsp; Image - Codebase to develop (Production + Test Code)</figcaption>
 </figure>
</p>

### Production/Development Cost

Its fact that implementing the feature with unit test/testing will take more time than development without unit test/testing.

<p>
 <figure>
 &nbsp;&nbsp;&nbsp; <img src="_images-angular-unit-testing-jasmine-karma/1.5.2-production-development-cost.png" alt="Production development cost" title="Production development cost" width="800" />
 <figcaption>&nbsp;&nbsp;&nbsp; Image - Production development cost</figcaption>
 </figure>
</p>

### Manual Testing Cost VS Automated Testing Cost

#### Manual Testing Cost
- In any application at the initial development level, Manual Testing takes less time
- As the application grows with more and more features, functionality and complexity, time is taken by Manual Testing increases exponentially-significantly
- In the longer run, many new team members are not aware of exact functionality and requirements to test as an actual old developer who developed the features are no more working with the company

#### Automated Testing Cost
- At the initial development level, Automated Testing takes more time
- In longer time over the years as and when the application grows with features and complexity, Automated Testing time decreases and it is far lesser than Manual Testing
- Now a days many companies avoid manual testing and automate everything and prefer test automation

<p>
 <figure>
 &nbsp;&nbsp;&nbsp; <img src="_images-angular-unit-testing-jasmine-karma/1.5.3-manual-automated-testing-cost.png" alt="Manual vs Automated testing cost" title="Manual vs Automated testing cost" width="800" />
 <figcaption>&nbsp;&nbsp;&nbsp; Image - Manual vs Automated testing cost</figcaption>
 </figure>
</p>

1.6. Why Test
---------------------
Testing is important and done to:
- Get an error if code break
- Avoid last-minute shocking/breaking code changes
- Tests are the best way to prevent software defects
- Avoid any invalid/bad/unwanted code 
- Think about possible issues and bugs in code/application
- Integrate into build workflow (If all test cases succeed than merge code and deployed automatically)
- Save time in the longer run
- Break up complex code dependencies and make our code easier
- Improve code/better code quality

1.7. Benefits-Advantages of Automated Testing
---------------------
- It helps to catch defects/bugs before releasing your application/product/software
- With Automated Testing, we produce software with fewer bugs and of better quality and more reliable
- Tests prevent software defects
- It will help you become a better developer
- It will enforce you to write better and more reliable code
- Helps in regression testing (Testing complete application in chunks, make sure old functionalities are working fine)
- Reveals mistakes in Design/Development (If some features are difficult/complex to write test cases - simplify functionality and logic)
- In the longer run, Automated Unit Testing acts as documentation fo application functionality

1.8. Do I need Automated testing
---------------------
1.8. Real-time testing scenarios
---------------------
1.8. What world think about testing
---------------------

### Be Linguistics and Pragmatic:
- Automated testing has lots of advantages-benefits but it is not good-fit for each project and every team
- Needed disciplined code and programmer in team else we need to spend more time and money to fix broken code which may result in loss
- In the Real world, we have constrained for TIME and MONEY - our job is to build + deliver real working software by solving problems and deliver values to the world
- Depends on the Project Budget, Development Time and Resources we can decide to go for Automated Testing or not

### Automated Testing may not good for:
- A startup who have limited budget and time
- Startup companies who are not sure about product future 
- Companies who develop research-based/experimental products (R & D projects)
- Software/application in which requirements changes frequently

1.9. First code or write the test
---------------------
1.9. Do I write Test first (TDD - Test Driven Development) or application code first?
---------------------
Its all depends on TIME, MONEY and need/requirements - usually, developers and companies first prefers to do application development then go for (TDD - Test Driven Development) and or BDD (Behavior Driven Development).

1.10. What to test
---------------------
We can write Angular tests cases for testing Functions, Logics, Events, multiple types of Components, Attributes-Directives, Dependencies, Routers- Navigation, and services. 

2 Different types of tests
=====================
There are different ways/types to test our application code. In Angular context, there are following types of test: `isolated and shallow unit testing, integration tests between components and UI/E2E tests, which can be functional and visual regression testing`. In general, we have 3 types of tests as given below:
1. Unit Test
2. Integration Test
3. End-to-end Test

Let's go through each testing type in detail and write the right tests for ensuring the application/testing work as expected.

2.1. Unit Test
---------------------

- Testing a function in isolation (testing one function, test individual components of the system) 
- Test an individual component `in isolation, without external resources` (e.g. file system, server, database, API endpoints, etc.)
- In Angular terms/context `testing only component class` file without any template/view, with fake services and fake routers
- **<u>Coverage</u>** - Small Unit/chunk of code to test
- **<u>Complexity</u>** - Easier to write
- **<u>Time/Duration</u>** - Super Fast, takes less time
- **<u>Frequency</u>** - Write more/as much as you can (Hundreds)
- **<u>Funtionality Testing Confidence</u>** - Does not test the functionality of the application in detail, not give us much confidence about functionality

<p>
 <figure>
 &nbsp;&nbsp;&nbsp; <img src="_images-angular-unit-testing-jasmine-karma/2.1.1-unit-test.png" alt="Unit Testing" title="Unit Testing" width="800" />
 <figcaption>&nbsp;&nbsp;&nbsp; Image - Unit Testing</figcaption>
 </figure>
</p>

2.2. Integration Test
---------------------
- If any Unit testing depends on external resources like databases, networks, and APIs, then it is not a unit test, it's an Integration Test
- Testing a Component with Template interaction, dependencies (testing a function that calls and depends on another function)
- In Angular terms/context `testing component along with template (component + template)`, with fake services and fake routers
- **<u>Coverage</u>** - Test a component `with external resources` (e.g. file system, server, database, API endpoints etc.)
- **<u>Complexity</u>** - Little complex as we need to deal with dependency injection
- **<u>Time/Duration</u>** - Little time consuming
- **<u>Frequency</u>** - Write a good couple of (Tens)
- **<u>Funtionality Testing Confidence</u>** - Give us much confidence about functionality

<p>
 <figure>
 &nbsp;&nbsp;&nbsp; <img src="_images-angular-unit-testing-jasmine-karma/2.1.2-integration-test.png" alt="Integration Testing" title="Integration Testing" width="800" />
 <figcaption>&nbsp;&nbsp;&nbsp; Image - Integration Testing</figcaption>
 </figure>
</p>

2.3. End to End Test
---------------------
2.3. End-to-End or End-2-End or E2E Test
---------------------
- Test an entire application as a whole including function, user interaction, service api calls and complete functionality
- `Testing and checking application from launching in browser till individual functinality, Full flow (validating a DOM after a click)`
- **<u>Coverage</u>** - Test whole app functionality, get more confidence about functinality
- **<u>Complexity</u>** - Complex
- **<u>Time/Duration</u>** - Pretty time consuming, Tests are very slow
- **<u>Frequency</u>** - Write a few (1,2 or so)
- **<u>Funtionality Testing Confidence</u>** - Very fragile (can get broken easily) if any changes in template or component

2.4. The testing pyramid
---------------------
The testing thumb-rule/testing pyramid says that: `75-80 % of the tests should be unit tests, 15-20 % is integration tests and 5 % is End-2-End UI tests`, overall depends on companies to companies, requirements to requirements.

> **Note**: Write more Unit and Integration Test and few/less End-to-End tests only for key functionalities

