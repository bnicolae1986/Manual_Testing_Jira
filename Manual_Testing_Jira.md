# Testing Project for Didactic.ro

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: didactic.ro 

Tools used: Jira, Zephyr Squad. 

## Functional specifications:

The stories below were created in Jira and describe the functional specifications of the "pagina mea" module, for which the final project is performed upon.

![story1](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/7381f75e-d173-4718-b69a-c5b454f5883a)

![story2](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/34205985-e880-43ee-a207-bc0f834b0614)

![story3](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/d856a5c6-9caa-4fb4-b7ac-0265b9711a1d)

Here you can find the release that was created for this project:

![release](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/5f449b0e-438d-43fd-aad1-67198cb532e9)

## Testing process

The test process was performed based on the standard test process as described below.

### 1.1 Test planning

The Test Plan is designed to describe all details of testing for the "pagina mea" module from the didactic.ro application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here. 

#### 1.1.1. Roles asigned to the project and persons allocated

  * Project manager - Ana Dumitrescu
  * Product owner - Daniela Suciu
  * Software developer - Mihai Soficaru
  * QA Engineer - Bogdan Nicolae

#### 1.1.2 Entry criteria defined

* The roles are alocated to the team members.
* The requirements are defined and approved.
* The test strategy is developed.
* The project risks are identified and mitigated.
* The test plan is created and approved.
* The test data is prepared.
* Test environment has been set-up and all other necessary resources such as tools and devices are available.
* The test cases are developed and approved.

#### 1.1.3 Exit criteria defined

* All the test cases have been alocated.
* All the test cases have been executed.
* Desired and sufficient coverage of the requirements and functionalities under the test.
* 90% of the faults have been corrected and closed.
* Regression testing is completed.
* No high priority or severity or critical bug has been left out.
* The project risks are identified and mitigated.
* The closing report has been generated and sent to the stakeholders.

#### 1.1.4 Test scope
Tests in scope:
In the scope of the testing is the "pagina mea" module in the didactic.ro aplication, wich will also include "abonamente", "despre mine", "diplome si adeverinte" sections.
The types and techniques that will be used are:
* Functional testing
* Usability testing
* Equivalence partitioning
* Boundary value analysis
* Decision table
* Positive / Negative testing

Any other types or techniques that will be necessary will be applied accordingly.

Tests not in scope:
* Sanity testing.
* State transition testing.

#### 1.1.5 Risks detected
Project risks:
* Improper assessment of required manpower resources.
* Lack of technical knowledge on specific areas of the product.
* Unclear business requirements.
* Continually changing requirements.
* Improper communication among team members.
* Improper communication with enterprise stakeholders.
* The project scope is expanded to include initially unanticipated expenses.
* Inaccurate estimation, have cause unanticipated expenses.

Product risks:
* Delivery of a product that contains defects that lead to failure
* The inability of the product to meet the requirements.
* The inability of the product to meet the customer's expectations.
* Poor functionality of the application.
* Poor performance of the application.
* Poor usability of the application.
* Poor reliability of the application.

![matrix git](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/79b7a6f2-b4a3-4401-9e9e-c6ab04e8cbd3)

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control

Test monitoring has been done to help stakeholders stay informed about the testing efforts and the quality of the software being developed. It provides visibility into whether the testing is on track, whether the quality goals are being met, and whether any corrective actions are required to ensure successful project outcomes. 

* Feedback has been provided to the stakeholders regarding the progress of sprint test cycles.
* Test results achieved so far are provided the the stakeholders.
* The test coverage metrics is provided.
* The test execution metrics is provided. The number of test cases that have passed, failed, or are unexecuted, are mentioned.
* Defect Metrics is provided.

  ![test metrics](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/b4624be8-3083-453d-bb7d-4c93833d65ef)

  ![tests](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/213e19cb-23d9-44e8-8314-d5e6ad01a4ef)

Feedback from the stakeholders has been provided, and the following actions have been decided.
 * The test schedules and deadlines have been reorganised.
 * The test cases and test conditions have been modified to better suit the business requirements.

### 1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

![teste](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/5d4dd1a6-c377-42f4-9929-e51834b3959b)

### 1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. 

The test cases can be accessed here:

[ZFJ-issue-export-02-19-2024-BNTMTA15.xlsx](https://github.com/bnicolae1986/Manual_Testing_Jira/files/14330684/ZFJ-issue-export-02-19-2024-BNTMTA15.xlsx)

### 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

#### Testing Environments:
* Properly configured testing environment settings (hardware, software, network).
* Relevant test data and test datasets covering various scenarios.

#### Source Code:
* Complete and integrated implementation of the source code.
* Ensure there are no obvious errors or significant issues before starting testing.

#### Testing Tools:
* Ensure that required testing tools are installed and properly configured.
* Check compatibility of tools with the testing environment and the application itself.

#### Reference Data:
* Identify reference data or expected values for the tested functionalities.
* Prepare test scenarios covering a variety of situations.

#### Test Execution Plan:
* Schedule and plan the execution of tests in a well-structured and efficient manner.
* Prioritize critical tests and identify dependencies between different tests.

#### Reporting and Monitoring:
* Set up a system for reporting test results.
* Prepare tools for monitoring progress and identifying potential issues.

#### Testing Environment Maintenance:
* Ensure the testing environment remains stable and consistent throughout test execution.
* Update configurations if necessary based on testing needs.

#### Backup and Recovery:
* Create backups of essential data before starting tests to avoid the loss of important information.

### 1.6. Test Execution

Test cases are executed on the created test Cycle summary: Didactic.ro version 1.0

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/bnicolae1986/Manual_Testing_Jira/blob/main/Jira.doc)


The following is a summary of the bugs that have been found:
- When the like button is clicked, the counter does not modify by plus one.
  - severity: low impact
  - priority: low
- The comment text box does not become active when clicked, text can not be entered.
  - severity: low impact
  - priority: low
- The activation process is not succesfull, even though the activation code is valid.
  - severity: significant impac
  - priority: highest
- When the edit button is clicked, the comment text box does not open and is not editable.
  - severity: minor impact
  - priority: mediul
- The "propune" submeniu is incorrectly displayed, it is offset to the right from the button position.
  - severity: low impact
  - priority: low

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 
![Matrix](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/9d16c69e-f4a6-4543-8fd6-0d19c05570d5)

Test execution chart was generated and can be found below.

![dashboard](https://github.com/bnicolae1986/Manual_Testing_Jira/assets/156198321/0a998d18-8f72-4e1c-9418-fe42ebd4534e)

The final report shows that a number of four tests have failed of a total of sixteen tests.

A number of five total bugs were found, from which the priority is: one is high, one is medium and 3 are low priority.

A total of sixteen tests have been created and executed, the stories have been covered to 95%. One bug that was found has a significant impact on the the product launch into production. The other have low or medium impact. The recommendation is that the bug with the significant impact, must be fixed before the product is launched.
