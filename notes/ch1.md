# Chapter 1 notes
• K1: Remember 
• K2: Understand 
• K3: Apply 
## Read more:
- static vs dynamic testing 
- Pareto princible
- verfication vs validation
- Test Basis & Testware

## keywords:
- Defect (faults, bugs): cause of the failure , can be removed by debugging - a non testing activity 

- Mistakes: Human error reulting to defects resulting to failures

- Root cause: fundamental reason for the occurance of a certain problem. Root cause analysis is performed when a failure occures or a defect is identified  

- Stakeholders:any person or group with an interest in the system, such as users, customers, developers, business owners and regulators. what they have (needs, expectations, requirements, willingness to cooperate, etc.)

- Risk register: a list of risks together with risk likelihood, risk impact and information about risk mitigation


## general notes: 

- testing is used ot verify and validate   i.e., checking whether the system meets specified requirements, it also 
involves validation, which means checking whether the system meets users’ and other stakeholders’ 
needs in its operational environment. 

- subsequent confirmation testing checks whether the fixes resolved the problem or not 

-  Subsequent regression testing can also 
be performed, to check whether the fixes are causing failures in other parts of the test object

- if a Defect in a code is excuted it may lead to one. Some defects always fail, some fail only in special situations, and some never fail. 

- Some defects will always result in a failure if executed, while others will only result in a failure in specific 
circumstances, and some may never result in a failure. 

## static vs dynamic testing :
    dynamic testing envolvs the execution of SW while static doesn't



## Test Objectives: 
- Evaluate requirments, user stories, designs and code
- causing failure and finding defects
- Make thew required coverage for a test object
- verify whether specified req. have been fullfiled and a test      object  complies with legal and regulatory req.

** Test objectives can vary, depending upon the context, which includes the work product being tested, the 
test level, risks, the software development lifecycle (SDLC) being followed, and factors related to the 
business context, e.g., corporate structure, competitive considerations, or time to market.


## Testing vs Debugging:
-  Testing can trigger failures that are caused by defects in 
the software (dynamic testing) or can directly find defects in the test object (static testing).  

- Debugging is concerned with finding causes of 
this failure (defects), analyzing these causes, and eliminating them.

## Testing vs QA:
- testing is a product-orianted corrective apporach that foucs on the activites suppoorting the acheivment of appropriate levels of quality.
- QA is a process-orianted preventive approach that foucses on the implementation and improvement of processes. it insures that a process is followed correctly and it will generate a good product.  QA applies to both the development and testing processes.
- Test results are used by QA and testing. In testing they are used to fix defects, while in QA they provide 
feedback on how well the development and test processes are performing. 


## Testing principles:
1.  Testing shows the presence, not the absence of defects.
    - testing reduce the probablity of undicvoered defect but that doesn't mean that testing prove the test object is fault free 

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
    - system verification alone can't insure that the system will meet the user's req and expectation therfore beside verfication validation should also be carried out 

## Test Activities and Tasks:

1. Test planning 
2. Test monitoring and test control
3. Test analysis
    - Test analysis answers the question “what to test?” in terms of measurable coverage criteria, Associated test conditions are defined and prioritized, taking the related risks and risk levels into account 
4. Test desing 
    -  Test design answers the question “how to test?”
    - Elaborating the test conditions into test cases 
5. Test implementation 
6. Test execution
7. Test completion
    -  usually occurs at project milestones (e.g., release, end of iteration, test level completion). For any unresolved defects, change requests or product backlog items are created.

## Test process in context: 
- Test activities are an integral part of the development processes 
carried out within an organization. Therefore, the way testing is carries out depends on several facotrs. stakeholders , team members'skills, knowledge, level of experiance. it also depends on business domain where the criticality of test object and market needs and regulations are met.Project constrains are also put into consideration (scope, time, budget, resources).
- These factors will have an impact on many test-related issues, including: test strategy, test techniques 
used, degree of test automation, required level of coverage, level of detail of testware, test reporting, etc

## Independance of testing 
The main benefit of independence of testing is that independent testers are likely to recognize different kinds of failures and defects compared to developers because of their different backgrounds, technical perspectives, and biases. Moreover, an independent tester can verify, challenge, or disprove assumptions made by stakeholders during specification and implementation of the system. For most projects, it 
is usually best to carry out testing with multiple levels of independence (e.g., developers performing component testing and component integration testing, test team performing system and system 
integration testing, and business representatives performing acceptance testing).