# Chapter 2 notes
• K1: Remember 
• K2: Understand 
• K3: Apply 

## Read more:
- waterfall model --> sequential development model
- V-model --> sequential development model
- spiral model -->iterative development model
- incremental development models
- Agile SW dev
- regression testing 
- TDD vs ATDD (no difference ?)
- Given/When/Then format
- CI/CD
- test harness
- integration strategy like bottom-up, top-down or big-bang
## Keywords:

- acceptance testing:
- black-box testing 
- component integration testing 
- component testing 
- confirmation testing
- functional testing
- integration testing
- maintenance testing 
- non-functional testing 
- regression testing
- shift left
- system integration testing
- system testing 
- test level 
- test object 
- test type
- white-box testing 
##  detailed software development methods and Agile practices:
- acceptance test-driven development (ATDD)
- behavior-driven development (BDD)
- domain-driven design (DDD)
- extreme programming (XP)
- feature-driven development (FDD)
- test-driven development (TDD) --> Tests are written first, then the code is written to satisfy the tests

* TDD, ATDD and BDD are similar development approaches, where tests are defined as a means of directing development. in other words the tests are defined before hte code is written


## Impact of the Software Development Lifecycle on Testing:
* the type of SDLC impacts tesing in all of the following:
1. Scope and timing of test activities 
2. Level of detail of test documentation
3. Choice of test techniques and test approach 
4. Extent of test automation 
5. Role and responsibilities of a tester 

## Software Development Lifecycle and Good Testing Practices:
* no matter the SDLC model there is a coresponding testing activity to insure quality control no matter what, test analysis and design phase begins in parallel with SDLC development phase 

## Shift left
* it means early testing even beofre code implementation but it donesn't mean there will be no testing in the end 


## Retrospectives(revision sessions) and process improvement 
* it's a revision and disscusion sesison where testers and most of team members (dev team and arches) talk about what has been done and how to improve or change anything in it .

* this session benefits the process in increasing testing effectivness , team harmony specialy between dev team and testing team 


## Test level and test types 

- Test levels answer: what part of the system am I testing, and at which stage? (one function, a few parts together, the whole system, or the customer’s view)

- Test types answer: what am I checking about it? (does it work, is it fast, can I see the code, did the fix break something)


## Test levels 

1. Component testing (known as Unit testing)
2. Component integration testing (known as unit integration testing)
    - tests how the components communicate and interact with each other 
    - it also depends on the integration strategy (bottom-up,top-down,  big-bang)

3. System testing 
    - test the enire system end-to-end 

4. System integration testing 
    - it tests how each system behave with other systems and external services 

5. Acceptance testing 
    - it test the system from user's prespictive (UAT) which validate the system and its readiness 

* To avoid overlapping of test activities distinguish test levels as follows 
    • Test object  (what does a certain fucntion expected to do)
• Test objectives (checking the functional completeness, correctness)
• Test basis 
• Defects and failures 
• Approach and responsibilities 



## Test types 
- all of the following types can be applied to all test levels

1. Functional testing 
    -  evaluates the functions that a component or system should perform.
2. Non-Functional testing  
    - tests how well the system behaves regarding the following:
        • Performance efficiency 
        • Compatibility 
        • Usability (also known as interaction capability) 
        • Reliability 
        • Security 
        • Maintainability 
        • Portability (also known as flexibility)  
        • Safety
    - non- fucntional components depends on the functional ones so usually this kind of testing is excuted with the functional tests (early in the SDLC, because if a certain defect is revealed late in the SDLC it can introduce major issues)

3. Black-box testing 
    - documentation based testing (no source code is tested rather than testing the system's behavior against the requriments)

4. White-box testing 
    - internal structure based testing (code, arch, work-flows is provided), this kind of testing reveales the underlying defects within the system/code base


## Confirmation testing and Regrission testing 

- these 2 types of tests are used when a change or modification happend when adding or fixing a feature 

1. Confirmation testing 
    - executes all previous failed tests to ensure they don't fail again
    - adding new tests to cover the changes that was done in order to fix the defect 

2. Regression testing 
    - type of testing that is excuted preferably after any change to make sure this change didn't affect any other component in the system, an Impact analysis is done prior the test is held also to see how deep the regression test must be held (it depends on the level of connection and dependancy of the changed componenet with other system components)


## Maintainance testing

- this type is done depending on the objective, if it is corrective or adabtive to change or to improve system performance , also it depends whether the maintainance is planned with a relase or unplanned (hot fixes) also like regression testing an impact analysis must be held before the maintaincnce to make sure how the maintaince affect other system components (the degree of risk, the size of existing system and the size of the change) . regression tests must be done too as a maintaince is considred a change in the system so to make sure that this system change didn't affect other system components

- types of maintainance testing :
    1. modifications
    2. upgrades or migration of the current operational env.
    3. Retirment to test the data archiving work properly if there is data retention needed after the system reirement 

    

