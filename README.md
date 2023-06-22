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
Jira:
![Test Cases and Test Conditions.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Test%20Cases%20and%20Test%20Conditions.1.png)
![Test Cases and Test Conditions.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Test%20Cases%20and%20Test%20Conditions.2.png)

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
   ![Test Execution Report](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Test%20Execution%20Report.png)

### 3.	Test deliverables

#### 3.1.  Test plan
This test plan will include test cases that will analyze the Job chapter of the OrangeHRM Website, the Job and Organization subsections, as well as API testing for SimpleBooks

#### 3.2.  Test conditions and tast cases
- [Job and Organization functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Job%20and%20Organization%20functionality.pdf)
- [Verify Job functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Job%20functionality.pdf)
- [The items in the Job submenu are present](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/The%20items%20in%20the%20Job%20submenu%20are%20present.pdf)
- [Verify Job Titles functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Job%20Titles%20functionality.pdf)
- [Check the presence of the fields from the Add Job Titles page, present in Figure 1.4](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Check%20the%20presence%20of%20the%20fields%20from%20the%20Add%20Job%20Titles%20page%2C%20present%20in%20Figure%201.4.pdf)
- [Add new Job Title](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Add%20new%20Job%20Title.pdf)
- [Verify if you can add a new job title without completing the required fields](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20new%20job%20title%20without%20completing%20the%20required%20fields.pdf)
- [Verify if you can enter multiple job titles](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20enter%20multiple%20job%20titles.pdf)
- [Check the details of job titles](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Check%20the%20details%20of%20job%20titles.pdf)
- [Verify if you can delete one Job Title or multiple at the same time](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20Job%20Title%20or%20multiple%20at%20the%20same%20time.pdf)
- [Verify if you can edit a job title after it has been added](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20edit%20a%20job%20title%20after%20it%20has%20been%20added.pdf)
- [Verify Pay Grade functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Pay%20Grade%20functionality.pdf)
- [Verify if you can add an Pay Grade](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20an%20Pay%20Grade.pdf)
- [Verify if you can define the pay grade.](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20define%20the%20pay%20grade..pdf)
- [Verify if the minimum and maximum salary can't be 0](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20the%20minimum%20and%20maximum%20salary%20can't%20be%200.pdf)
- [Verify if the minimum and maximum salary can have the same value](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20the%20minimum%20and%20maximum%20salary%20can%20have%20the%20same%20value.pdf)
- [Verify if you can assign multiple currencies](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20assign%20multiple%20currencies.pdf)
- [Verify if in the maximum salary field you can add a lower value than in the minimum salary field](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20in%20the%20maximum%20salary%20field%20you%20can%20add%20a%20lower%20value%20than%20in%20the%20minimum%20salary%20field.pdf)
- [Verify if you can add characters other than numbers in the salary fields](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20characters%20other%20than%20numbers%20in%20the%20salary%20fields.pdf)
- [Check that you can view and edit the Pay Grade details after it has been added](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Check%20that%20you%20can%20view%20and%20edit%20the%20Pay%20Grade%20details%20after%20it%20has%20been%20added.pdf)
- [Verify if you can delete one Pay Grade or multiple at the same time](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20Pay%20Grade%20or%20multiple%20at%20the%20same%20time.pdf)
- [Verify Employment Status functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Employment%20Status%20functionality.pdf)
- [Verify if you can add an Employment Status](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20an%20Employment%20Status.pdf)
- [Verify if you can edit an Employment Status after it has been added](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20edit%20an%20Employment%20Status%20after%20it%20has%20been%20added.pdf)
- [Verify if you can delete one Employment Status or multiple at the same time](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20Employment%20Status%20or%20multiple%20at%20the%20same%20time.pdf)
- [Verify if you can add an Employment Status by writing special characters in the name field](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20an%20Employment%20Status%20by%20writing%20special%20characters%20in%20the%20name%20field.pdf)
- [Verify Job Categories functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Job%20Categories%20functionality.pdf)
- [Verify if you can add a Job Category](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20Job%20Category.pdf)
- [Verify if you can see the Job Category details after it has been added](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20see%20the%20Job%20Category%20details%20after%20it%20has%20been%20added.pdf)
- [Verify if you can add multiple entries of Job Categories](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20multiple%20entries%20of%20Job%20Categories.pdf)
- [Verify if you can delete one Job Category or multiple at the same time.](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20Job%20Category%20or%20multiple%20at%20the%20same%20time..pdf)
- [Verify Work Shifts functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Work%20Shifts%20functionality.pdf)
- [Verify if you can add a Work Shifts and the list of work shifts appears](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20Work%20Shifts%20and%20the%20list%20of%20work%20shifts%20appears.pdf)
- [Check the presence of the fields from the Add Work Shift page](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Check%20the%20presence%20of%20the%20fields%20from%20the%20Add%20Work%20Shift%20page.pdf)
- [Verify if you can assign employees to the particular shift](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20assign%20employees%20to%20the%20particular%20shift.pdf)
- [Verify if you can delete one Work Shifts or multiple at the same time](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20Work%20Shifts%20or%20multiple%20at%20the%20same%20time.pdf)
- [Verify Organization functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Organization%20functionality.pdf)
- [Verify General Information functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20General%20Information%20functionality.pdf)
- [Verify if you can add information in the General Information category](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20information%20in%20the%20General%20Information%20category.pdf)
- [Verify the presence of the fields in the General Information category present in Figure 2.6](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20the%20presence%20of%20the%20fields%20in%20the%20General%20Information%20category%20present%20in%20Figure%202.6.pdf)
- [Verify if you can save the information without completing the required fields](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20save%20the%20information%20without%20completing%20the%20required%20fields.pdf)
- [Verify if you can complete the "Phone" field by adding a single digit or a number greater than 10 digits](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20complete%20the%20Phone%20field%20by%20adding%20a%20single%20digit%20or%20a%20number%20greater%20than%2010%20digits.pdf)
- [Verify if you can fill in the "Email" field with random letters without @](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20fill%20in%20the%20Email%20field%20with%20random%20letters%20without%20%40.pdf)
- [Verify Location functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Location%20functionality.pdf)
- [Verify if you can add a location and it is listed](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20location%20and%20it%20is%20listed.pdf)
- [Verify the presence of the fields in the "Add Location" category present in Figure 2.7](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20the%20presence%20of%20the%20fields%20in%20the%20Add%20Location%20category%20present%20in%20Figure%202.7.pdf)
- [Verify if you can add a location without filling in the required fields](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20location%20without%20filling%20in%20the%20required%20fields.pdf)
- [Verify if you can complete the "Phone" field by adding a single digit or a number greater than 10 digits](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20complete%20the%20Phone%20field%20by%20adding%20a%20single%20digit%20or%20a%20number%20greater%20than%2010%20digits.1.pdf)
- [Verify if you can view location details after this was added and if you can edit them](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20view%20location%20details%20after%20this%20was%20added%20and%20if%20you%20can%20edit%20them.pdf)
- [Verify if you can delete one location or multiple at the same time](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20one%20location%20or%20multiple%20at%20the%20same%20time.pdf)
- [Verify Structure functionality](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20Structure%20functionality.pdf)
- [Verify if you can add a sub-unit to the company structure](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20sub-unit%20to%20the%20company%20structure.pdf)
- [Verify the presence of the fields in the "Add Sub-Unit " page, present in Figure 3.0](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20the%20presence%20of%20the%20fields%20in%20the%20Add%20Sub-Unit%20%20page%2C%20present%20in%20Figure%203.0.pdf)
- [Verify if you can add a Sub-Unit to the company structure without filling in the required fields](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20a%20Sub-Unit%20to%20the%20company%20structure%20without%20filling%20in%20the%20required%20fields.pdf)
- [Verify if you can add other subunits to the relevant fields to indicate the hierarchical levels of the company and create a pyramidal structure of the organization.](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20add%20other%20subunits%20to%20the%20relevant%20fields%20to%20indicate%20the%20hierarchical%20levels%20of%20the%20company%20and%20create%20a%20pyramidal%20structure%20of%20the%20organization..pdf)
- [Verify if you can collapse/expand the sub-units](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20collapseexpand%20the%20sub-units.pdf)
- [Verify if you can delete Sub-Units](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Verify%20if%20you%20can%20delete%20Sub-Units.pdf)

#### 3.3  Daily test summary report 
- 24.04.2023
  ![24.04.2023.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-24.04.2023.1.png)
  ![24.04.2023.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-24.04.2023.2.png)
  ![24.04.2023.3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-24.04.2023.3.png)
- 25.04.2023
  ![25.04.2023.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-25.04.2023.1.png)
  ![24.04.2023.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-25.04.2023.2.png)
  ![24.04.2023.3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-25.04.2023.3.png)
  ![24.04.2023.4](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Daily-25.04.2023.4.png)

#### 3.4	  Test case results
- [Test cases results](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Test%20case%20results.xlsx)
![Test case results 1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.1.png)
![Test case results 2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.2.png)
![Test case results 3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.3.png)
![Test case results 4](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.4.png)
![Test case results 5](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.5.png)
![Test case results 6](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.6.png)
![Test case results 7](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Results.7.png)

#### 3.5	  Bugs report

- The details of the job title do not appear when click on its name.These are already present on the right side of the job title name:
![Bug1.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug1.1.png)
![Bug1.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug1.2.png)

- The minimum and maximum salary can be 0:
![Bug2.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug2.1.png)
![Bug2.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug2.2.png)

- The same value can't be entered in the minimum salary and maximum salary fields:
![Bug3.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug3.1.png)
![Bug3.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug3.2.png)

- You can't edit an Employment Status by clicking on its name:
![Bug4.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug4.1.png)
![Bug4.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug4.2.png)

- There are no details about Job Category:
![Bug5.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug5.1.png)
![Bug5.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug5.2.png)
![Bug5.3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug5.3.png)

- The "Available Employees" field on the Add Work Shift page isn't present:
![Bug6.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug6.1.png)
![Bug6.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug6.2.png)

- There wasn't "Employees Available" box and "Employees Allocated" box to be able to assign employees:
![Bug7.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug7.1.png)
![Bug7.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug7.2.png)

- The "Phone" field can be completed by adding a single digit or a number greater than 10 digits:
![Bug8.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug8.1.png)
![Bug8.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug8.2.png)
![Bug8.3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug8.3.png)

- You can complete the "Phone" field by adding a single digit or a number greater than 10 digits:
![Bug9.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug9.1.png)
![Bug9.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug9.2.png)
![Bug9.3](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug9.3.png)

- A subunit can't be added to the company structure on the path mentioned in the busniess requirements:
![Bug10.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug10.1.png)
![Bug10.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug10.2.png)

- A subunit can't be deleted as specified in the business requirements:
![Bug11.1](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug11.1.png)
![Bug11.2](https://github.com/SabinaGabor/Proiect-Final-TM/blob/main/Bug11.2.png)

