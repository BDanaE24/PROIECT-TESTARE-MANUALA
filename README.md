# PROIECT-PRACTIC-TESTARE-MANUALA

# Version History

|Date|Description|Author|Comments|
|---|---|---|---|
| 05.05.2023 | Test Plan for version 0.55 | Matei Oltean ||
| 07.07.2023 | Test plan for version 1.0 | Adelina Pop | Added more detailsfor Test Implementation |

# 1 Introduction

1.1 Project objective

1.2 Functionalities in scope

1.3 Functionalities and tests out of scope
  
# 2. Test Process

2.1 Test Planning

2.2 Test Analysis

2.3 Test design

2.4 Test implementation

2.5 Test execution

2.6 Test closure

2.7 Test monitoring and control

# 3. Test deliverables

3.1. Test Plan

3.2. Test Condition

3.3. Test Cases

3.4. Daily Test Summary Reports

3.5 Traceability Matrix

3.6 Test Cases Result

3.7 Bugs Report

3.8 Test Completion Report

# 1. Introduction

The Guru99 Bank project aims to provide a net banking facility to its customers.
This release will have limited features. Over a period of time, new and new functionalities will be added to the site.

## 1.1 Project objective

We need to raise the trust in the quality of the project as high as possible before releasing it to customers.
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using an available application.

Application under test: https://demo.guru99.com/V4/index.php

Application documentation: https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit

## 1.2 Functionalities in scope

Here we should write all the functionalities that are included in the release.
e.g.(example given) Add funds, Withdraw funds, Send money, Monthly funds report, Transactions of the account, Remaining funds, Security settings, Security Improvements

- The features in scope for testing: Add funds, Withdraw funds, Send money
- Testing types used: functional testing, GUI testing

## 1.3 Functionalities tests out of scope

- The features out of scope: Monthly funds report, Transactions of the account, Remaining funds, Security Improvements
- Non-functional testing like stress, performance is beyond scope off this project.
- No QA support for mobile applications developed. Only web applications will be tested.
- Automation testing is beyond scope.

# 2. Test process

## 2.1 Test planning

#### Roles and responsibilities

|Role|Name|Tasks/Work|
|---|---|---|
| Senior Tester | Matei Oltean | Will test: Add funds, Withdraw funds |
| Tester | Adelina Pop| Will test: Send money |

#### Entry criteria:

-	functional business specifications are defined
-	roles needed for the project are allocated
-	testing environment is up and running
-	smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)

#### Exit criteria:

-	all test cases have been executed 
-	90% of tests are passed
-	no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
-	exploratory testing performed on the features: Add funds, Withdraw funds, Send money
-	update tests are 100% passed (update tests will not generate other new issues that impact the application)

#### Risks:

-	user data (banking related data, funds, transactions, etc) might be impacted with update tests
-	stability risks (crashes, disconnects, etc)
-	IE browser might have performance issues
-	versions of IE older than 1.5923e have security vulnerabilities (we could mention what vulnerabilities are)
-	the web page pagination could be impacted when opened on mobile devices
-	stress conditions might impact the web application
-	new browser might not be supported

 ## 2.2 Test analysis

- The testing process will be done based on the requirements for features:
  ###### Add funds, Withdraw funds, Send money
- We plan on running a ful regresion test on the current version

## 2.3 Test design

- All the test cases are written and reviewed
- Funcional test cases winn be created in Zephyr Squad using Jira as Test Management tool
- GUI test cases will be created in Zephyr Squad using Jira as Test Management tool

## 2.4 Test implementation

- all the data is available and reviewed (test data=email exanples, password examples, different type of currency, different types of credit cards)
- this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
- Cycle summary was created and test cases wer added to the cycle summary
- Test enviromnment is up and running: https://demo.guru99.com/V4/index.php

## 2.5 Test execution

- The tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera and Brave browsers
- Test cases will be executed on the created Test Cycle Sumary
- Bugs will be reported based on the failed tests

## 2.6 Test closure

- At least 90% of tests are passed
- No Critical issues have Open status
- Exploratory testing have been performed

## 2.7 Test monitoring and control

- Various periodic reports (daily/weekly/bi-weekly) will be generated to reflect the current status of the testing process.

# 3. Test deliverables

## 3.1 Test plan - link to test plan

- The Test Plan is designet to describe all the details of testing for yhe following features: Add funds, Withdraw funds, Send money from Guru99 application
- The plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing prosess, the risks associated with the plan, the resources and schedule required to complete testing.

## 3.2 Test conditions

- we will use test environment
- testing using new accounts and older account is necessary
- The following test conditions could be found here:* vom adauga link catre document cu test cases create si incarcate pe Github. Test cases vor fi exportate din Jira [Test conditions](https://github.com/BDanaE24/PROIECT-PRACTIC-TESTARE-MANUALA/commit/0702f5170c1483fb1b8459627a775b33e3b92603)

## 3.3 Test condition

- The test cases with steps could be found here: *vom adauga link catre document cu test cases create pe github. Test cases vor fi exportate in jira

## 3.4 Dayly/Weekly/Bi-weekly test summary report

**- link to daily test summary report (number of tests ran today, % of them failed, passed, re-tested, etc)** vom adauga link catre screeshot cu test summary report incarcat pe github SUA incarcam imaginea cu raportul direct pe github. Raportul va fi generat din Jira pe masura ce executam test caseurile.
![TEO](WhatsApp Image 2023-07-14 at 16.48.31.jpeg)

## 3.5 Traceability matrix

**- Link to traceability matrix** vom incarca pe github un screenshot din Jira

## 3.6 Test case results

- The test cases result could be found here: *vom adauga link catre document cu test cases executate pe github. Test cases result vor fi exportate din Jira.

## 3.7 The bugs 
- The bug reported could be found here: * vom adauga link catre document cu defectele raportate in Jira pt test Case-urile failed

## 3.8 Test completion report

**- link to test completion report (Test cases ran, hou many TC are passed and how many are failed)**

*vom adauga screenshot cu test completion report din Jira la sfarsitul testarii (toate test case-urile au fost executate)*

## 3.9 Schedule

**- we have 10 days of testing**

**- we have 30 functional and GUI tests**

**- in order to finish the regression run we would need to run an ~ of 3 tests/day**

 ![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")







