# qa
# Introduction
Included are my deliverables for the Documentation Project and the Automation Project, links to my test document for the process of uploading video to the schedule entry and my CasperJS file for the Hudl QA Project survey automation task.  I will describe in detail, the thought process and details of each item.

# Documentation Project
## Test document template
In this section I will review and explain in detail each components, 1) Test Plan, 2) Test Results, 3) Test Cases, and 4) a detailed description of the functional process (Video Upload OPL) of the template.
* Link to Test document template (a shared Google spreadsheet)
* https://docs.google.com/spreadsheets/d/1GJKnsDFRDCOhPYSyqpSbN2A_Ieqvg5US-KiBykOyxWw/edit?usp=sharing

###Test Plan
Details in the Test Plan include a listing of the administrative information of the testing. These are items that detail the scope of the testing, the functional requirements, the tester, the developer, any additional members that require updates, the timeline and other specific information that is needed to facilitate with testing.  

The focus of this Test plan is to upload videos through the hudl.com website and not through the Hudl Mercury tool.

###Test Results
In here, I provided a summary of the results of the Test cases that lists how many cycles of testing was completed, the start and end dates, any defects, and the developer that the defects were reported to.  In addition, because a QA analyst has a voice in every part of the product, details about the process and user experiences can be captured and detailed here so that it can be shared with the developer during testing reviews.

Provide is an example summary of the mocked up cycle testing. In addition, I have included a user experience comment for the Game Video section.

###Test Cases
Provided here is a list of the test cases to run, the list includes what is being tested and what the expected results will be.  Here, I detail the type of test (authorization, functionality, compatibility, error handling, performance, etc.) as well as a section for Test case status.  If a test script fails, a defect number can be assigned and the severity calculated (Critical, High, Medium, Low). Severity is determined by the team and by the impact to the user and this will help facilitate a developer in prioritizing the defect.

I mocked up two cycle tests which included 2 defects during cycle 1 and in cycle 2, only a smaller subset of the test scripts required additional testing and all passed successfully.

###Video Upload OPL
It is very important to have a detailed step-by-step process of the functional process that is being tested. This detailed process will help the Quality Analyst target the testing to the desired features that require testing. A QA analyst work with the designers and developers to ensure that the process is acceptable based on the requirements and design.

# Automation Project
## CasperJS automate QA Project survey file
* Link to CasperJS automate QA Project survey file
* https://github.com/sumaoang/qa/blob/master/CasperJS_survey_automate

Website to be automated: https://hudl.wufoo.com/forms/qa-project/

The flow of my automated test is as follows
* Validate that page 1 loads successfully by confirming that the elements on Page 1 that I will fill are available
* Fill the fields and validate that they filled successfully
* Click on the Next Page button
* Validate that page 2 loads successfully by confirming that the elements on Page 2 that I will fill are available
* Fill the fields and validate that they filled successfully
* Click on the Submit button

Two additional tests that I intended to include are validating that the state dropdown box filled correct and testing of the previous page button.  Having no prior experience with CasperJS and having to learn during the process, I was not able to figure out the correct syntax to execute these two tests.  

Given more time and access to more resource both online and individuals with more experience, I will be able to resolve the syntax issues.
