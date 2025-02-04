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

Core Functionalities tested included :  

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



### Approach: 

**Broad Coverage**: Test all functions at a basic level for system stability. 

**Focused Exploration**: Deep dive into critical transactions like Withdrawal, Deposit and Transfer and ATM card validation.

### Test Case Development: 

**Common Paths**: Typical ATM operations (e.g., successful withdrawal, balance checks). 

**Exceptional Paths**: Invalid PIN entries, insufficient funds, canceled transactions. 

**Boundary Testing**: Max/min withdrawal limits, rapid transaction sequences. 

### Test Logistics


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
Clarity and conciseness: Ensuring that defect reports were understandable and free of ambiguity.
Reproducibility: Confirming that the reported defects could be replicated, with clear steps provided.
Severity and priority: Evaluating the impact of the defect and prioritizing it accordingly.
To meet these objectives, one team pair reported the bug while another evaluated the reported bugs. Peer reviews contributed to the quality of defect documentation.


# How the pair testing was managed and team work/effort was divided 
Pair testing was organized by assigning roles of "driver" and "observer" within each pair. The driver conducted the tests, while the observer documented findings and provided real-time feedback. We rotated roles to ensure balanced participation and knowledge sharing. Regular communication and coordination using Microsoft Team chats/meetings helped to ensure smooth collaboration and effective pair testing. 

# Difficulties encountered, challenges overcome, and lessons learned

We encountered challenges in maintaining consistent documentation during exploratory testing due to its unstructured nature. Overcoming this required adopting quick note-taking techniques and summarizing key findings immediately after testing sessions. We learned the importance of effective communication, adaptability, and critical thinking in identifying defects efficiently. 

# Comments/feedback on the lab and lab document itself

This lab provided valuable hands-on experience in both exploratory and manual functional testing. It highlighted the strengths and limitations of each approach. The lab document was clear and well-structured, though adding more examples of effective defect reports could further enhance understanding. Overall, the lab effectively reinforced theoretical concepts through practical application. 
