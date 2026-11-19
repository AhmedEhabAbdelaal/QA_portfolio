# Chapter 3 notes

# Read more
- tools of static analysis 
- static analysis 
- test charters
- maintainability 
- exit criteria 
# Keywords

- Anomaly --> it's a possible defect that has to be analyzed and discussed to take a decision for its status, ownership and required actions
- dynamic testing
- formal review
- informal review
- inspection
- review
- static analysis
- static testing
- technical review
- walkthrough

## Static Testing Basics

- the software under test isn't executed.
- the Code, system arch. and other work products are evaluated(reviewed)
maybe with the help of tools (static analysis)

- static testing can be applied in both verification and validation

- static analysis can identify problems prior to dynamic testing while taking less effort since no test cases is typically used.

- static analysis is often included within CI frameworks

- while static analysis is used to detect specific code defects it is also used to evaluate maintainability and security. 

- spelling checkers and readability tolls are used along with other tools of static analysis tools

## Work Products Examinable by Static Testing

- Any work product that is readable and understood can be subjected to static testing. However, work products need a structure to test them against.

- there are some Work products that are not appropriate for static testing that are not readable by humans  and can't be analyzed by tools(due to legal reasons)


## Value of static testing 

- Static testing can detect defect early in the SDLC which falls under the principle of early testing.

- Static testing can detect defects that dynamic testing can't detect such as unreachable code, design patterns not implemented as desired.

- Static testing provide a clear understanding of the user requirements so that the stakeholder ensured that their needs are met and that's why this type of testing is important in the early stages of the SDLC.

## Difference between static testing and dynamic testing

- they both complement each other, they both share the same objective but also differ in some ways:

    - they both can detect defects but some types of defect can only be detected using one of them while the other can't

    - static testing finds defect directly, while dynamic testing causes failures which leads to the defect causing it .

    - static testing can be done on non-executable work products, while dynamic can be done only to executable

    - static testing can measure quality of non-dependant on executing code (maintainability), while dynamic testing measures the quality of a dependant on executing code(performance efficiency)

- types of defect that is easier/cheaper to be found using static testing:
    - defect in requirements

    - design defects (inefficient database structures, poor modularization)

    - certain types of coding defects (variables with undefined values, undeclared variables, unreachable or duplicated code, excessive code complexity)

    - deviations from standards (lack of adherence to naming conventions in coding standards)

    - incorrect interface specifications (mismatched number, type or order of parameters)

    - specific types of security vulnerabilities (buffer overflows)

    - Gaps or inaccuracies in test basis coverage

## Benefits of Early and Frequent Stakeholder Feedback

- frequent feedbacks of the stakeholder is good for the whole project development in order to make sure the development team fully understands the requirements and dodge any deviation from their vision or any misunderstanding of the requirements where it results in costly rework, missed deadlines, blame games and even total project failure.


## Review process activities

- the ISO/IEC 20246 defines a generic review process that is structured but flexible that is tailored to any situation. if the size of work products too large then multiple reviews maybe needed.

- review process activities:
    - planning: defining the review scope, what quality characteristics to be evaluated , areas to focus on, exit criteria and timeframe for the review.

    - review initiation: it's goal is to make sure everything and everyone involved is prepared to start the review and has full access to the work product under review 

    - individual review: every reviewer performs an individual review to asses the quality of the work product under review to identify (anomalies, recommendations and questions) using one or more reviewing technique such as (checklist-based reviewing, scenario-based reviewing, etc..)

    - communication and analysis: the found anomalies are not necessarily a defect but in order to take action they should be analyzed and discussed in order to take the proper action. A follow-up review must be held in order to complete the final action for these anomalies and in order for the review process to be complete 

    - fixing and reporting: for every defect, a defect report is created so that the corrective actions can be followed up until the exit criteria is reached so the work product maybe accepted 

## Roles and Responsibilities in Reviews
- manager: decides what to be reviewed and provide the needed resources
- author: creates and fixes the product under review
- moderator: ensures the running of review meetings and time management



## Review types 

- review types ranging from informal review to formal reviews. it depends on on the SDLC and the maturity of the development process, complexity of the work product .

- selecting the right review type doesn't depend only on the objective but also the available resources, project needs, business domain and company culture

- types of reviews:
    - informal review: from its name, it doesn't require a defined process it just targets the finding of anomalies 

    - walkthrough: done by the author in order to evaluate the work product and gain the required knowledge and confidence about the work product and to educate the reviewers

    - technical review: done by technically able reviewer 

    - inspection: most formal type of reviews the full complete review process is executed. finding the maximum number of anomalies is the main objective of this review type 


## Success Factors for Reviews 

1. Defining clear objectives and measurable exit criteria

2. choosing the appropriate review type that fit best with the work product

3. performing review in small chunks in order not to lose focus 

4. provide feedback from reviews to authors so they can improve the work product

5. give the reviewers or the involved participants the time needed for the review

6. management support for the review process

7. facilitate meetings 

8. provide suitable training for members in order to fulfill their role




