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

1. Verify that login page should get open when we hit the URL of the login page. / Verify that the login screen should get open when we launch the app.
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

*Responsiveness check*

15. Verify the redirection on "create a page" Link.
16. verify that user should be able to login with "Enter" button.
17. Verify that user is able to navigate correctly backward with "shift + Tab" button.
18. Verify that user is able to input username.
19. Verify that user is able to enter password.
20. Verify that password should be masked/encrypted.
21. Verify that the password should be visible on tap of eye button and again become encrypted on double tap.
22. Verify the Min and max allowed character limit of username/email.
23. verify the min and max allowed character limit for password field.
24. Verify the redirection of the page links present in footer section.
25. verify that user should not be able to login with blank username and blank password.
26. Verify that correct error message should be displayed when user enter blank email and password.

     * Username and password cannot be blank.
     * Invalid email and password
     * Email you entered is not connected to any account

27. Verify that user should not be able to login with blank email and valid password.

     * Invalid credentials
     * Email and password combination is not correct
     * Email is  a mandatory field
     * Email id cannot be blank.
     * Authentication Error

28. Verify the error message when user enter blank email and valid password

<table>
   <tr>
      <td>Test case</td>
      <td>25</td>
      <td>27</td>
      <td>29</td>
      <td>31</td>
      <td>33</td>
   </tr>
   <tr>
      <td>Email</td>
      <td>Blank</td>
      <td>Blank</td>
      <td>Blank</td>
      <td>Valid</td>
      <td>Invalid</td>
   </tr>
   <tr>
      <td>Password</td>
      <td>Blank</td>
      <td>Valid</td>
      <td>Invalid</td>
      <td>Blank</td>
      <td>Blank</td>
   </tr>
   <tr>
      <td>Error</td>
      <td>26</td>
      <td>28</td>
      <td>30</td>
      <td>32</td>
      <td>34</td>
   </tr>
</table>


<table>
   <tr>
      <td>Test case</td>
      <td>35</td>
      <td>37</td>
      <td>39</td>
      <td>41</td>
      <td>Homepage</td>
   </tr>
   <tr>
      <td>Email</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>-</td>
   </tr>
   <tr>
      <td>Password</td>
      <td>false</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>-</td>
   </tr>
   <tr>
      <td>Error TC</td>
      <td>36</td>
      <td>38</td>
      <td>40</td>
      <td>42</td>
      <td>Login Successful</td>
   </tr>
</table>

43. Verify that user should not be able to login with old password once it is changed.
44. Verify that user should be able to login with new password.
45. verify that user cannot set already used passwords as new password.
46. user should not be able to set username , email, phone number as password.
47. Verify that password should match the expected criteria(one lowercase one uppercase 1 special character 8 digit long)
48. Verify the max no. of unsuccessful login attempt allowed (based on the requirements).
49. verify that captcha, OTP, 2FA or MFA(Multi factor authentication) is enabled or not.
50. verify that multiple sessions are allowed or not

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

### Testing Methodologies/Testing Techniques

### Boundary Value Analysis :

* In this type of testing technique we test the functionality at boundary values, We test at min, max, Inside and outside boundary values.

    AGE :[  ] 18--19---20--55
         18 - Min boundary
         55 - Max boundary
         19 - Inside boundary
         54 - Inside boundary
         17 - Outside boundary
         56 - Outside boundary


TC 1: 18 yes
TC 2: 100 N
TC 3: 55 Y
TC 4: 12 N
TC 5: -10N
TC 6: Male/Female
TC 7: -40 N
TC 8: -53 N
TC 9: Blank N
TC 10: male 19 N
TC 11: female 16 N
TC 12: Male 21 Y
TC 13: female 18 Y
TC 14: Thirty N
TC 15 60/2 N

Boundary Value Analysis

<table>
   <tr>
      <td>Invalid</td>
      <td>min</td>
      <td>valid</td>
      <td>Invalid</td>
      <td>max</td>
      <td></td>
   </tr>
   <tr>
      <td>min-1 min</td>
      <td>min-1</td>
      <td>max+1</td>
      <td>max+1 max</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td>17 18</td>
      <td>19</td>
      <td>54</td>
      <td>55 56</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td>TC1 TC2</td>
      <td>TC3</td>
      <td>TC4</td>
      <td>TC5 TC6</td>
      <td>-</td>
      <td>-</td>
   </tr>
</table>

Invalid min	valid	Invalid max
min-1	min,min+1,max-1,max	max+1
17	18,19,54,55	56
TC1	TC2,TC3,TC4,TC5	TC6


2. Equivalence class partitioning :

In this type of testing we divide the inputs into different groups which are known as classes, on the basis of their behavior.

AGE : 18(min)--55(max)

Invalid (min)  --> age<18          17,16,--infinite

valid   --> 17<age<56              18,19,--54,55

Invalid(max) --> age>55            56,57,--infinite

Example

100 sweet boxes

100
99
98
.
.
.
1

Boundary :1,2 ---- 99,100 (Approved)
ECP : group 1[1-30] Mon -->
      group 2[31-60] Tue --> (Approved)
      group 3[61-100] Wed -->

### Domains

1. banking domain
(https://netbanking.hdfcbank.com/)

2. E-commerce (Flipkart/Amazon)
3. Dating (Tinder/match)
4. real estate (Magicbricks /99acre.com)
5. CMS (Wordpress) homework - content management system
6. ERP - Enterprise resource planning
7. CRM - Customer relationship management homework
8. LMS - Learning management system  homework
9. HRMS homework
10. Social media homework
11. Gaming homework


Types of ecommerce (homework)

B2B
B2C
C2C(OLX)

ecommerce websites -> single seller
https://www.mi.com/  , https://www.boat-lifestyle.com/

Ecommerce Marketplace -> multiple seller
Amazon/Flipkart

Amazon --> Interface --> sellers (commission)

Top 5 E-comm marketplace websites

Open source E-comm Framework

Shopify
OpenCart
Prestashop
Wordpress (Woocommerce)
Adobe commerce (magento)

Dynamic Websites

Frontend
Backend

Components of E-commerce Websites

Header (Compare b/w amazon/flipkart/myntra)
Footer (Compare b/w amazon/flipkart/myntra)
Categories and subcategories(Compare b/w amazon/flipkart/myntra)
Homepage(Compare b/w amazon/flipkart/myntra)
Shopping cart page
Mini cart page
Wishlist
Registration  page/create account/signup page
Social signup page(Gmail/facebook/twitter)
Login page
profile
Checkout page
 
    * Shipping -> shipping address -> shipping methods
         1. E-cart logistic
         2. Blue Dart
         3. Delhivery
         4. Fedex
         5. DTDC
    * Payment -> Enter Billing address-> Payment Method
         1. Offline payment method -> OCD/Cheque
         2. Payments methods -> Paypal/Razorpay/Amazon pay/Mangopay/Stripe/Brainetree

10. Payment method
11. Shipping method


Components of E-commerce Websites

Homepage
header
Footer
Categories and sub categories
Cart
Wishlist
Compare page
Registration page/Create Account page/Signup page
Social signup
Login page
profile
Category page
Product page
Checkout
    1. Shipping  -> Enter shipping address -> select shipping method ->
        ekart logistic
        DTDC
        Dehlivery
        Fedex
        Ups
        USPS

2. payment -> Billing Address -> payment
       Gateway.
       paypal
       Amazon pay
       Razorpay
       Stripe
       Braintree
       MangoPay

HOMEWORk - search

 10 Shipping methods
 10 payment methods

Types of product

Simple product - product which you can touch and feel (Weight!=0)
Downloadable product(Weight=0)
Configurable product - cloths shirt size, color
Bundle of group
Virtual product (Weight=0)
Gift card(homework)

### Bug Reporting in GIT/ Jira/Trello


###  GIT 

open repo -> click on issues -> add title in precise way such that developer should understand easily -> add description.

Example :

 title :

    Web | Customer | Registration | All fields should be marked with asterisk (*)

 Description :

  #### Environment
 
  - Build : -> in the repo click on 1 commit then copy the id and paste it here
  - Php version : 7.1.14
  - version : 2.4.0 (footer of the webpage)
  - platform : iOS/Android/WEB
  - Browser : Chrome/Safari/Firefox
  - Chrome version : go to settings in chrome -> click on about Chrome -> look at version            like ex - Version 119.0.6045.105
  - Server : Local/Dev/Stagging/pre-prod/production
  - iOS version : 15
  - Device used: I pad pro

 #### Description

  - All required fields should be marked with asterisk (*)
  - if Asterisk is not marked then we can also mention that **All fields are mandatory**

  #### Steps to Reproduce

  1. navigate to url https://www.drishtilearningapp.com/
  2. Tap to login button in header.
  3. Click on 'Register now'
  4. Analyze the sign -up form

  #### Test data

  - URL : https://www.drishtilearningapp.com/
  
  #### Actual
   
   - All required fields are not marked with asterisk (*)
  
Attach a screenshot of that issue

Then assign that to the developer -> on your right hand side -> there is option called assignments -> click on that and select the user -> then apply labels select bug if it is a bug or many more depending on the issue 
 
when clicked on labels -> give label name as iOS or depending on the issue faced on the device/operating systems -> create label

also you can create label -> label name - High Priority -> choose color -> ex- red -> create label

Report :

To Lock :

  * TC05 -

GitHub repo -> issues -> new issue

title : 
       WEB | customer | registration | frontend error messages are not visible below name, mobile and password when user tries to register by only entering email.

description : 
 
  #### Environment
 
  - Build : -> in the repo click on 1 commit then copy the id and paste it here
  - Php version : 7.1.14
  - version : 2.4.0 (footer of the webpage)
  - platform : iOS/Android/WEB
  - Browser : Chrome/Safari/Firefox
  - Chrome version : go to settings in chrome -> click on about Chrome -> look at version like ex - Version 119.0.6045.105
  - Server : Local/Dev/Stagging/pre-prod/production
  - iOS version : 15
  - Device used: I pad pro

 #### Description

  - frontend error messages are not visible below name, mobile and password when user tries to register by only entering email.

#### Test steps

  1. Navigate to registration page
  2. Enter valid email keep other fields as blank
  3. Click on submit button 

#### Expected

 - Frontend validation message that name, mobile and password are required fields below respective fields.

#### Actual 

 - Validation message for mobile is coming below email field

Attach screen shot -> assign issue to the developer -> label as bug -> submit issue




