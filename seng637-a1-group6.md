>   **SENG 637 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 6      |
|-----------------|
| Student 1 Daniel                |   
| Student 2 Laxmi             |   
| Student 3 Oreoluwa              |   
| Student 4 Vitalis                |   


**Table of Contents**


[1 Introduction](#introduction)

[2 High-level description of the exploratory testing plan](#high-level-description-of-the-exploratory-testing-plan)

[3 Comparison of exploratory and manual functional testing](#comparison-of-exploratory-and-manual-functional-testing)

[4 Notes and discussion of the peer reviews of defect reports](#notes-and-discussion-of-the-peer-reviews-of-defect-reports)

[5. How the Pair Testing Was Managed and Team Work/Effort Was Divided](#how-the-pair-testing-was-managed-and-team-workeffort-was-divided)

[6. Difficulties Encountered, Challenges Overcome, and Lessons Learned](#difficulties-encountered-challenges-overcome-and-lessons-learned)

[7. Comments/Feedback on the Lab and Lab Document Itself](#commentsfeedback-on-the-lab-and-lab-document-itself)



# Introduction

In this lab we explored the fundamentals of software with a focus on exploratory, manual and regression. The Software Under Test (SUT) is an ATM simulation system.  This lab report outlines the test plan followed, tests performed, test types and some discussions and bug report.

Before this lab, exploratory testing was understood as using the application to understand its functionalities and testing various scenarios without predefined test cases. Manual functional testing was identified as the process where testers manually execute and directly test different functionalities in a software application to verify their proper operation. 


# High-level description of the exploratory testing plan

### Types of Tests

Three types of testing was used to test the SUT, they include:

 - Exploratory testing
 - Manual Function testing
 - Regression testing


### Testing Scope
Our exploratory test plan involved identifying key functional areas of the SUT, potential errors/issues, usability concerns, and performance bottlenecks. Focus was on uncovering unexpected behaviors through dynamic exploration. 

**Core Functionalities tested included** :  

 - ATM System Power On/Of 
 
 - ATM card validation 

 - Withdrawal

 - Transfer between accounts,  

 - Deposit,  

 - Balance Enquiry, and  

 - Transaction Cancellation 

 - Log management 

 - Receipt  

 - Error Handling 

#### Manual Testing
The manual testing phase was scripted and followed a structured approach using the test script provided in Appendix C. This ensured consistency in test execution across different functionalities, allowing for systematic verification of the system’s behavior. The test cases covered both normal operations and edge cases, focusing on critical aspects such as invalid card entries, incorrect PIN attempts, and exceeding withdrawal limits.
#### Regression Testing**
After initial testing and bug fixes, regression testing was conducted on SUT V.1.1 to ensure that resolving existing defects did not introduce new issues into the system. This involved re-executing previously tested functionalities to verify stability and confirm that all features continued to operate as expected. A key aspect of this phase was rechecking the bugs documented during both exploratory testing and scripted manual testing, ensuring that they had been successfully addressed.
### Approach: 

**Broad Coverage**: All core ATM functionalities were tested at a fundamental level to assess system stability, ensuring that no immediate failures or critical errors surfaced during normal operations.

**Focused Exploration**: In-depth testing was conducted on critical transactions, including withdrawals, deposits, transfers, and ATM card validation. These were analyzed for correctness given their importance in real-world ATM usage.
### Test Case Development: 

**Common Paths**: Covered standard ATM operations such as successful card validation, withdrawals, deposits, and balance inquiries, ensuring that the system functions correctly in typical user scenarios.

**Exceptional Paths**: Tested scenarios where users might encounter errors, including invalid PIN entries, insufficient funds, expired or blocked cards, and canceled transactions, to verify the system's handling of incorrect inputs and failure states.

**Boundary Testing**: Examined extreme conditions such as maximum and minimum withdrawal limits, rapid successive transactions, and account balance edge cases to identify potential vulnerabilities or performance issues.

### Test Logistics
#### Exploratory Testing Phase
To gain familiarity with the ATM simulation system, each team member individually followed steps 1–12 from the "Familiarization with the ATM System" subsection in the Instructions section. This phase allowed us to understand the overall functionality of the system before conducting structured testing.
#### Bug Documentation
During exploratory testing, each team member documented any bugs they encountered while interacting with the system’s core functionalities. This process not only helped us identify defects early but also allowed us to familiarize ourselves with our chosen bug-tracking tool, Jira. Documenting these findings ensured that all identified issues were systematically tracked and later verified during regression testing.
#### Manual Functional Testing
For the manual functional testing phase, two team members were assigned 20 test cases each from the test suite provided in Appendix C to drive the testing. Meanwhile, the remaining two team members tracked the execution process and documented any additional bugs found that were not identified during exploratory testing. The tests were executed sequentially from test case 1 through test case 40, ensuring comprehensive coverage of the ATM system’s core operations.
#### Regression Testing
In the final phase, each team member tested version 1.1 of the SUT, reviewing and updating the existing bug reports. The manual functional tests were repeated, with one team member executing test cases 1–20, while another executed test cases 21–40. Any newly discovered bugs were documented and reported by the team member who identified them. This ensured that all previous defects were verified, while also checking for any unintended regressions introduced by system updates.
 

### Key Metrics: 

 - Severity of identified issues. 

 - Coverage of key ATM functionalities. 

# Comparison of exploratory and manual functional testing


The exploratory testing process was dynamic and adaptive, enabling us to gain insights into the application during testing. Conversely, manual functional testing utilized a structured methodology with predefined test cases. While manual testing provided thorough coverage of requirements, exploratory testing's flexible approach facilitated the identification of unforeseen defects.


### Comparison from Several Perspectives:
 - Benefits: Exploratory testing promotes creativity, adaptability, and rapid discovery of defects, especially in complex or unfamiliar systems. Manual functional testing ensures systematic coverage, traceability, and repeatability, making it reliable for regression testing.
 - Trade-offs: Exploratory testing may result in inconsistent documentation and varying test coverage depending on the tester's expertise. Manual functional testing can be time-consuming and less effective at identifying edge-case defects due to its rigid structure.
 - Effectiveness: Exploratory testing excels at identifying hidden, unexpected issues and is highly effective when testers have domain knowledge. Manual functional testing effectively verifies that software meets specified requirements and detects known defect patterns.
 - Efficiency: Exploratory testing allows for faster identification of defects without the overhead of writing detailed test cases, but it may require more effort for thorough documentation afterward. Manual functional testing can be slower due to test case preparation and execution but provides clear, repeatable results for audits and compliance.


# Notes and discussion of the peer reviews of defect reports

During peer reviews, attention was given to:
 - Clarity and conciseness: Ensuring that defect reports were understandable and free of ambiguity.
 - Reproducibility: Confirming that the reported defects could be replicated, with clear steps provided.
 - Severity and priority: Evaluating the impact of the defect and prioritizing it accordingly.

**Peer Review Process**:

 - Each pair created defect reports based on their testing sessions.

 - Another pair reviewed these reports for accuracy, completeness, and clarity.

 - Feedback was provided directly, focusing on improving the reproducibility of defects and enhancing report quality.


# How the pair testing was managed and team work/effort was divided 
Pair testing was organized by assigning roles of "driver" and "observer" within each pair. The driver conducted the tests, while the observer documented findings and provided real-time feedback. We rotated roles to ensure balanced participation and knowledge sharing. Regular communication and coordination using Microsoft Team chats/meetings helped to ensure smooth collaboration and effective pair testing. See Test logistics for more detials

# Difficulties encountered, challenges overcome, and lessons learned

**Difficulties Encountered**:

 - Maintaining consistent documentation during exploratory testing due to its unstructured nature.

 - Reproducing intermittent bugs identified during dynamic testing sessions.

**Challenges Overcome**:

Adopted quick note-taking techniques to capture real-time observations.

Summarized key findings immediately after each session to maintain clarity.

**Lessons Learned**:

Importance of effective communication in pair testing.

Adaptability and critical thinking are crucial for identifying defects efficiently.

Structured documentation practices enhance the value of exploratory tes

# Comments/feedback on the lab and lab document itself

This lab provided valuable hands-on experience in both exploratory and manual functional testing. It highlighted the strengths and limitations of each approach. The lab document was clear and well-structured, though adding more examples of effective defect reports could further enhance understanding. Overall, the lab effectively reinforced theoretical concepts through practical application. 
