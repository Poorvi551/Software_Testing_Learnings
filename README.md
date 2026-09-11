# Software_Testing_Learnings
Software Testing Learnings - code factory

## Software Development Life Cycle (SDLC) 

1. Requirement Gathering/Elicitation

   - BRS -> Business Requirement specification
   - CRS -> Client Requirement specification
   - URS -> User Requirement specification
   Service based company -> Business analyst brings requirements,
   Product based company -> Market Research brings requirements.
   
1. Feasibility Study(TELOS)

    - T --> Technical (Python/PHP)(Web Design / AI)
    - E --> Economical (Budget)
    - L --> Legal (Allowed by cyber law of INDIA)
    - O --> Operational (e.g. project - Time machine/Flying Bikes)
    - S --> Schedule -> Time (Facebook) 1 month

  2. Analysis

     - SRS -> Software requirement specification document
     - FRS -> Functional requirement specification

  4. Design (High level Design or Low level Design)
     
  5. Coding (Developers (SDE))
     
  6. Testing (Tester or QA STE)
      
  7. Deployment & Maintainance

## Software Testing Life Cycle

1. Requirement Analysis
2. Test Planning
3. Test Case Development
4. Environment Setup
5. Test Case Execution
6. Test Cycle Closure

### 1. Requirement Analysis

* QA Team will get to know about the workflow/vision of the software.
* QA will go through the requirement document and will have discussion with B.A and dev team about the scope of software.
* QA will understand the functional and non functional testable requirements.
* Automation/manual testing
* Preparation of RTM (Requirement Traceability Matrix)
  
#### Exit Criteria/Output/deliverables

  *Automation feasibility Report 
  * RTM
    
### 2. Test planning

* Test planning is done by QA Manager,
* He will plan the test strategy.
    1. Roles and responsibilites
    2. Team size and training
    3. Test tool selection
    4. Time and cost estimation

* exit criteria/output/Deliverables :

   1. Test Planning doc
   2. Test Schedule Doc
      
### 3. Test Case Development 

* QA will start writing down the test cases/scripts.
* Test data is also prepared
  
* Exit criteria/output/Deliverables :

   - Test cases/Script
   - test data

### 4. Environment Setup

* Hardware and software prerequisites for caring out this testing.
* Usually testing env is given by developer team.
* Exit criteria/output/Deliverables :

  - Smoke test result - (to check whether the software is testable or not) initial phase of testing
  - Environment setup ready.

### 5. Test Case Execution

* QA will execute the prepared test cases.
* Failed test cases are reported back to developer.
* Retesting
* Mapping of Result into RTM.

* Exit criteria/output/Deliverables :

   - Defect report
   - Mapped RTM with result

### 6. Test Cycle Closure

* Discussion on time and cost during this testing cycle.
* Arrangement of defects according to their priority and severity.
* Preparation of closure report.

* Exit criteria/output/Deliverables :

   - Test cycle closure report

## Test Cases

### Test cases on Login Page of FACEBOOK

1. Verify that login page should get open when we hit the URL of the login page./Verify that the login screen should get open when we launch the app.
2. Verify that logo of the facebook should be present.
3. Verify the color, shape, size, font and position of the logo.
4. Verify that tagline is present or not.
5. Verify the font color, position of the tagline.
6. Verify there should be no spelling, Grammar and punctuation error in Tagline.
7. Verify that all required labels, input fields, buttons, links and text should be present.
8. Verify that all required labels, input fields, buttons, links and text should be clearly visible.
9. Verify that all buttons, text, input field and links should be properly aligned (There should be no overlapping).
10. Verify the size of all buttons ,links, text and input fields.
11. Verify that the functionality should work in different Browser (Cross Browser testing).
12. Verify that tooltip is present or not.
13. Verify that placeholder is present or not.
14. Verify that that the login is responsive according to different screen size.(Responsive testing).

### Developers tools

1. ctrl + shift + i
2. Right click -> click inspect
3. three dots -> more tools -> Dev Tools (When there is a  disability of above two options)
4. Toggle device when inspected beside element

## Defect/Bug Life Cycle 

1. Defected -> Deviation from an expected functionality

* New -> Whenever any defect is encountered by QA for the very first time then QA log that defect and mark the status as NEW
 (Log -> can be done on any either excel or Jira or testlink or any other tools based on the organisation)

2. Assigned -> QA manager will approve the defect and assign it to developer team for fixing.

3. InProgress/Open -> Developer will analyze the defect and works on its fix.

   * Rejected(Not a Bug):

Example : Shaadi.com

   Age(18 yrs -- 80 yrs)
   Prakhar --> 20 -> Error -> Your age is not valid

DEFECT #1 - User is not able to register when age is 20.
Age -> 18 Gender male --> 20 (for males 21 is the marriage age so developer will reject the defect)

Those defects which are invalid one such type of defects are marked as rejected.
 
   * Duplicate : When the defect is raised twice or more the developer marks it as Duplicate and start working on original one.

   * Deferred : When the raised issue is of low importance and low priority such types of issues are marked as deferred and these issues are fixed in upcoming version or release.

4.  Fixed -> When developer makes necessary changes in code then he marks the status as fixed.

5. Retest -> QA will retest the defect whether it got fixed or not.

6. Closed -> If the issue no longer exists the QA marks the status as closed.

7. Reopen -> If the raised issue still exists the QA marks it Reopen and assign back to developer.






