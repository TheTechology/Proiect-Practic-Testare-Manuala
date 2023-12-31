# Proiect Practic Testare Manuala
| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 05.08.2023 | Test Plan for version 0.55 | Marian DUMITRU|   | Added more details for Test Implementation|
| 07.09.2023 | Test Plan for version 1.0 | Marian DUMITRU | Added more details for Test Implementation |

1. Introduction
     
      1.1 Project Objective
     
      1.2 Functionalities in scope
     
      1.3 Functionalities and tests out of scope
  2. Test Process
      
      2.1 Test Planning
     
      2.2 Test Analysis
     
      2.3 Test design
     
      2.4 Test implementation

      2.5 Test execution

      2.6 Test closure

      2.7 Test monitoring and control
# 1.Introduction
The Guru99 Bank project aims to provide a net banking facility to its customers.
This release will have limited features. Over a period of time , new and new functionalities will be added to the site.

## 1.1 Project Objective
We need to raise the trust in the quality of the project as high as possible before releasing it to customers.
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using an available application. 
Application under test: https://demo.guru99.com/V4/index.php 
Application documentation:  https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit

### 1.2 Functionalities in scope
Here we should write all the functionalities that are included in the release.
e.g .(example given) Add funds, Withdraw funds, Send money, Monthly funds report, Transactions of the account, Remaining funds, Security settings, Security Improvements

### 1.3 Functionalities and tests out of scope
The features out of scope: Monthly funds report, Transactions of the account, Remaining funds, Security settings, Security Improvements
Non-functional testing like stress, performance is beyond scope of this project.
No QA support for mobile applications developed. Only web applications will be tested.
Automation testing is beyond scope.

# 2.Test process

### 2.1 Test planning
#### Roles and responsibilities

| Role | Name | Tasks/Work |
|---|---|---|
| Senior Tester | Marian DUMITRU | will test: Add funds, Withdraw funds |
| Tester | Adelina Pop | will test: Sends money |

#### Entry criteria:

-	functional business specifications are defined
-	roles needed for the project are allocated
-	testing environment is up and running
-	smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testin
#### Exit criteria:

-	all test cases have been executed 
-	90% of tests are passed
-	no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
-	exploratory testing performed on the features: Add funds, Withdraw funds, Send money
-	update tests are 100% passed (update tests will not generate other new issues that impact the application)
Ioana Gornateanu7:11 PM
#### Risks:

-	user data (banking related data, funds, transactions, etc) might be impacted with update tests
-	stability risks (crashes, disconnects, etc)
-	IE browser might have performance issues
-	versions of IE older than 1.5923e have security vulnerabilities (we could mention what vulnerabilities are)
-	the web page pagination could be impacted when opened on mobile devices
-	stress conditions might impact the web application
-	new browser might not be supported

  # 3. Test deliverables

  ## 3.1 Test plan - link to test plan
  The Test Plan is designed to describe all the details of testing for the following features: Add funds, Withdraw funds, Send money from Guru99 application
The plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing.

## 3.2 Test conditions 
 we will use test environment
 - testing using new accounts and older account is necessary
The following test conditions could be found here [Test conditions]([https://github.com/BogdanScutariu/Proiect-Practic-Testare-Manuala/blob/main/Sesiune%20Teoretica.pptx](https://github.com/TheTechology/Proiect-Practic-Testare-Manuala/blob/main/Sesiune%20Teoretica.pptx)) 

## 3.3  Test cases
 The test cases with steps could be found here: *vom adauga link catre document cu test cases create si incarcate pe github. Test cases vor fi exportate din Jira. 

## 3.4 Daily/Weekly/Bi-weekly test summary report
 - link to daily test summary report


   




