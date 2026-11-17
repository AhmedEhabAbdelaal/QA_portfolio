# Chapter 1 notes
• K1: Remember 
• K2: Understand 
• K3: Apply 
## Read more:
- Pareto principle: states that 80% of the effects come from 20% of causes or inputs, Defect clustering (Roughly 80% of software bugs are found in 20% of the program modules or components.)

- verification vs validation: 
    - verification: ensures that you are building the product right(does it meet the specification?), most of the time uses static testing and ensures the code against the requirements.
    - validation: ensures that you are the building the right product(does it meet user needs)?,most of the time uses dynamic testing to see even if the code matches the requirements and specs, the final SW do what the user wants.

- Test Basis & Testware:
    -  Test Basis: is the body of information and documentation used to determine what the system should do, and from which test cases and conditions are derived.
    - Testware: It defines the how testing is performed and documented.It contains all the work products, artifacts, utilities, and application software created during the testing lifecycle to plan, design, execute, and report on testing.

## keywords:
- Defect (faults, bugs): cause of the failure , can be removed by debugging - a non testing activity 

- Mistakes: Human error resulting to defects resulting to failures

- Root cause: fundamental reason for the occurrence of a certain problem. Root cause analysis is performed when a failure occurs or a defect is identified  

- Stakeholders:any person or group with an interest in the system, such as users, customers, developers, business owners and regulators. what they have (needs, expectations, requirements, willingness to cooperate, etc.)

- Risk register: a list of risks together with risk likelihood, risk impact and information about risk mitigation


## general notes: 

- testing is used ot verify and validate   i.e., checking whether the system meets specified requirements, it also 
involves validation, which means checking whether the system meets users’ and other stakeholders’ 
needs in its operational environment. 

- subsequent confirmation testing checks whether the fixes resolved the problem or not 

-  Subsequent regression testing can also 
be performed, to check whether the fixes are causing failures in other parts of the test object

- if a Defect in a code is executed it may lead to one. Some defects always fail, some fail only in special situations, and some never fail. 

- Some defects will always result in a failure if executed, while others will only result in a failure in specific 
circumstances, and some may never result in a failure.

- pesticide paradox: The same tests repeated over time stop finding new defects 

- traceability matrix: Link test conditions and test cases back to their basis (requirements)

## static vs dynamic testing :
    dynamic testing involves the execution of SW and observing runtime behavior while static testing evaluates SW artifacts like code, requirements and design without running the program



## Test Objectives: 
- Evaluate requirements, user stories, designs and code
- causing failure and finding defects
- Make thew required coverage for a test object
- verify whether specified req. have been fulfilled and a test      object  complies with legal and regulatory req.

** Test objectives can vary, depending upon the context, which includes the work product being tested, the 
test level, risks, the software development lifecycle (SDLC) being followed, and factors related to the 
business context, e.g., corporate structure, competitive considerations, or time to market.


## Testing vs Debugging:
-  Testing can trigger failures that are caused by defects in 
the software (dynamic testing) or can directly find defects in the test object (static testing).  

- Debugging is concerned with finding causes of 
this failure (defects), analyzing these causes, and eliminating them.

## Testing vs QA:
- testing is a product-oriented corrective approach that focus on the activates supporting the achievement of appropriate levels of quality.
- QA is a process-oriented preventive approach that focuses on the implementation and improvement of processes. it ensures that a process is followed correctly and it will generate a good product.  QA applies to both the development and testing processes.
- Test results are used by QA and testing. In testing they are used to fix defects, while in QA they provide 
feedback on how well the development and test processes are performing. 


## Testing principles:
1.  Testing shows the presence, not the absence of defects.
    - testing reduce the probability of undiscovered defect but that doesn't mean that testing prove the test object is fault free 

2. Exhaustive testing is impossible .
    - testing everything is not feasible so test techniques, test case prioritization, and risk-based testing, should be used to focus test efforts.

3. Early testing saves time and money.
    - early static and dynamic testing should be started early as possible 

4. Defects cluster together.
    - A small number of system components usually contain most of the defects discovered or are responsible for most of the operational failures

5. Tests wear out.
    - If the same tests are repeated many times, they become increasingly ineffective in detecting new defects

    -  in some cases, repeating the same tests can have a beneficial outcome, e.g., in automated regression testing

6. Testing is context dependent.
    - There is no single universally applicable approach to testing. Testing is done differently in different contexts

7. Absence-of-defects misconception.
    - system verification alone can't insure that the system will meet the user's req and expectation therefore beside verification validation should also be carried out 

## Test Activities and Tasks:

1. Test planning 
2. Test monitoring and test control
3. Test analysis
    - Test analysis answers the question “what to test?” in terms of measurable coverage criteria, Associated test conditions are defined and prioritized, taking the related risks and risk levels into account 
4. Test design 
    -  Test design answers the question “how to test?”
    - Elaborating the test conditions into test cases 
5. Test implementation 
6. Test execution
7. Test completion
    -  usually occurs at project milestones (e.g., release, end of iteration, test level completion). For any unresolved defects, change requests or product backlog items are created.

## Test process in context: 
- Test activities are an integral part of the development processes 
carried out within an organization. Therefore, the way testing is carries out depends on several factors. stakeholders , team members'skills, knowledge, level of experience. it also depends on business domain where the criticality of test object and market needs and regulations are met.Project constrains are also put into consideration (scope, time, budget, resources).
- These factors will have an impact on many test-related issues, including: test strategy, test techniques 
used, degree of test automation, required level of coverage, level of detail of testware, test reporting, etc

## Independence of testing  
The main benefit of independence of testing is that independent testers are likely to recognize different kinds of failures and defects compared to developers because of their different backgrounds, technical perspectives, and biases. Moreover, an independent tester can verify, challenge, or disprove assumptions made by stakeholders during specification and implementation of the system. For most projects, it 
is usually best to carry out testing with multiple levels of independence (e.g., developers performing component testing and component integration testing, test team performing system and system 
integration testing, and business representatives performing acceptance testing).



## Mock Questions on Ch1 

1. B Correct
2. C Correct
3. B Correct
4. B Correct
5. B Correct
6. B Correct
7. B Correct
8. C Correct
9. B Correct
10. B Wrong
11. D Correct
12. B Correct
13. A Correct
14. C Correct
15. D Wrong 
16. C Correct
17. B Correct
18. B Correct
19. B Correct
20. B Correct

* Mock exam grade: 18/20

## My mistakes 

10. i chose B, it's wrong since that masked defect is a defect that is hidden by another one 

15. i chose D, it's wrong since that test analysis is to identify test conditions from test basis while my choice is test execution
