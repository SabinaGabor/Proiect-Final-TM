# Proiect-Final-Testare-Manuală
# OrangeHRM
## Test Plan

### Revision History
| 22.03.2023 | V1.0    | Gabor Sabina    |  Draft plan |
| --- | --- | --- | --- |
| 14.04.2023 | V1.0   | Gabor Sabina   | Create test cases |
| 23.04.2023 | v1.0| Gabor Sabina | Test results for test cases |

1. Introduction

   1.1. Project objective
 
   1.2. Functionalities in scope

   1.3. Functionalities and tests out of scope

2.	Test process

    2.1.	Test planning
  
    2.2. Test analysis
  
    2.3. Test design
  
    2.4.	Test implementation
   
    2.5. Test execution
   
    2.6. Test closure

3.	Test deliverables

    3.1. Test plan
   
    3.2. Test conditions
   
    3.3. Test Cases
   
    3.4.	Daily test summary reports
   
    3.5.	Traceability matrix
   
    3.6. Test case results
   
    3.7. Bugs report
   
    3.8. Test completion report
 
 
 ### 1. Introduction 
 
 This test plan describes the strategies, process, the way to organize the test cases and methodologies used to plan, execute and manage testing process for OrangeHRM browser application.

#### 1.1. Project Objective

The scope of the final project for the ITF Manual & Automation Testing Course is to apply all the knowledge gained during the course and to apply them in practice using a live application.

- [Application under test](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login )

- [Application documentation](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf  )

Tools used:

- Jira
- Postman
- MySQL

#### 1.2. Functionalities in scope

All features of Job and Organization from Admin Module which were defined in software requirement specs need to be: functional testing, GUI testing, API testing  

#### 1.3. Functionalities and tests out of scope

- All OrangeHRM features except Job and Organization from Admin Module
- Non-functional testing like stress, performance is beyond scope of this project.
- No QA support for mobile application developed. Only web application will be tested.
- Automation testing is beyond scope.


### 2. Test process

#### 2.1. Test planning

#### Roles and responsibilities

| QA Engineer  | Gabor Sabina |
| ------------- | ------------- |
| Product Owner  | Popa Iulian  |
| Project Manager  | Georgescu Marian  |
| Softuware Developer | Florea Andrei  |
| Senior QA Engineer | Ionescu Laura  |

#### Entry criteria
- functional specifications defined 
- roles needed for the project are allocated 
- initial project risks were detected and mitigated 

#### Exit criteria
- all test cases have been executed 
-	the number of unresolved bugs is insignificant or have low priority 
-	all resolved bugs have been re-tested and closed by QA team 
-	deadline was reached 
-	no detected major risks remained un-mitigated 

#### Risks
Project risks:
-	lack of experience of the QA team 
-	only one QA in the QA team 
-	unavailability of the test environment 
-	short deadline of Zephyr Squad and Jira tools 

Product risks: 
- validation constraints on the fields might be too restrictive to the end user.

#### 2.2. Test analysis 
-	Analyze business requirements to make sure that we have all the details for creating the test conditions 
-	Write test conditions that will be tested in out test process

#### 2.3. Test design
-	Functional test cases will be created in Zephyr Squad 
-	GUI test cases will be created in Zephyr Squad
-	API test cases will be created in Postman 
-	The test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis. 

#### 2.4. Test implementation
Verify that the following elements are ready before the test execution phase: 
-	test environment is up and running: [Application link](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
-	access to the test environment is given: username Admin, pass: admin123
-	Cycle summary was created 
-	the test cases were added to the cycle summary 
-	Postman collections were created 

#### 2.5. Test execution
-	Test cases are executed on the created Cycle summary 
-	Bugs were created based on the failed test cases. 
-	API test cases were executed 
-	Full regression pack was executed 

#### 2.6. Test closure
-	As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team. 
-	All test cases have been executed 
-	The number of unresolved bugs is insignificant or have low priority 
-	All resolved bugs have been re-tested and closed by QA team 
-	Deadline was reached 
-	No detected major risks remained un-mitigated 

#### 2.7. Test monitoring and control
-	Generate periodic reports to check the project status: status for the test cases executed, status for the converge of the business requirements, etc 
-  [Test Execution Report](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Test%20Execution%20Report.pdf)

### 3.	Test deliverables

#### 3.1.  Test plan


#### 3.2.  Test conditions




