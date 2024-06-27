<h1>Testing Project for **Booking.com desktop app**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **Booking.com desktop app**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describes the functional specifications of the "**Login Functionality**", "**Search Functionality**", "**Filter Functionality**" and "**Account settings**" module, for which the final project is performed upon.
**![Screenshot 2024-06-16 010445](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/47c502d2-a63d-436e-bd3d-5868714b6084)**

Here you can find the release that was created for this project:

**![Screenshot 2024-06-23 175132](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/cc00959a-1e70-4bb5-945b-ce4bf5bd05c1)**

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for the modules from the Booking desktop application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Project manager: Mark Dyson</li> 
  <li>Product owner: Booking</li>
  <li>Software developer: Kate Smith</li>
  <li>QA Engineer: Goja Adina</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

<ul>
  <li>All test environments are set up</li>
  <li>Test data is prepoared</li>
  <li>Test cases are reviewed and approved</li>
  <li>All necessary tools are installed and accessible</li>
  <li>Test team members have received necessary training on tools and the application under test</li>
</ul>

<h4> 1.1.3 Exit criteria defined </h4>

<ul>
  <li>All planed tests are executed</li>
  <li>Critical and high-priority defects are resolved</li>
  <li>Test summary report is completed</li>
  <li>All fixed defects have been retested and verified</li>
</ul>

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

<ul>
  <li>The user should be able to sign up when all the mandatory fields are completed - Positive functional testing</li>
  <li>The user should be able to sign in after the mandatory fields are completed with valid data - Positive functional testing</li>
  <li>The user should not be able to login if he fill the password field with invalid data - Negative functional testing</li>
  <li>Verify search functionality with valid inputs - Positive functional testing</li>
  <li>Search with invalid destination - Negative functional testing</li>
  <li>Sort Search results by price - Positive functional testing</li>
  <li>Verify that search results update when modifying the number of nights- Positive functional testing</li>
  <li>Verify that users can filter hotel search results by price range - Positive functional testing</li>
  <li>Verify that you can combine multiple filters - Positive functional testing</li>
  <li>The user should not be able to have under 16 years old - Negative functional testing</li>
</ul>


<h5>Tests not in scope: </h5>

<ul>
  <li>Mobile Application Testing</li>
  <li>Testing the internal functionalities of third-party systems (e.g., payment gateways, email servers) beyond their integration with the Booking Desktop Application</li>
  <li>Performance tuning of the database server (e.g., indexing, query optimization) is not covered, although the application’s interaction with the database is included</li>
  <li>Testing for language translations, locale-specific features, and internationalization is not within the current scope</li>
  <li>Testing the application under extreme load conditions beyond typical operational capacity is excluded</li>
</ul>

<h4>1.1.5 Risks detected</h4>

<ul>
  <li>Delays in Test Environment Setup: Testing cannot begin on schedule, leading to delays in the overall project timeline</li>
  <li>Unavailability of Key Personnel: Loss of critical knowledge and expertise, leading to delays and potential quality issues</li>
  <li>Changes in Requirements: Scope creep leading to additional testing efforts and potential delays</li>
  <li>Insufficient Test Coverage: Critical defects may go undetected, leading to post-release issues</li>
  <li>Incomplete or Incorrect Test Data: Tests may not accurately reflect real-world scenarios, leading to missed defects</li>
  <li>Lack of Documentation: Incomplete or outdated documentation can lead to misunderstandings and testing gaps</li>
</ul>

<h5>Project risks:</h5>

<ul>
  <li>Uncontrolled changes or continuous addition of new features can delay the project timeline and increase costs</li>
  <li>Insufficient resources (e.g., personnel, tools) can lead to delays and affect the quality of deliverables</li>
  <li>Setting unrealistic deadlines can lead to rushed work, increased stress, and potential quality issues</li>
  <li>Insufficient testing can lead to undetected defects, resulting in a poor user experience and potential rework</li>
  <li>Poor project management can lead to delays, budget overruns, and quality issues.</li>
</ul>

<h5> Product risks: </h5>

<ul>
  <li>Poor user experience can lead to user dissatisfaction, reduced adoption, and increased support calls</li>
  <li>Slow response times or application crashes under load can frustrate users and lead to abandonment</li>
  <li>Inaccurate or corrupt data can lead to incorrect bookings, financial losses, and loss of user trust</li>
  <li>Users may resist changes or new features, leading to lower adoption rates</li>
</ul>

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>
  
The monitoring and control stage is essential in project management to ensure that the project stays on track and that its objectives are achieved efficiently and effectively. The main reasons for this stage include ensuring compliance, identifying and managing risks, managing resources, monitoring progress, improving communication and controlling changes.
<h5>Test status report:</h5>

![Screenshot 2024-06-23 191219](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/d73cb0aa-189e-4edf-af53-21b259f373a6)

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b></b>. <br><br>

The following test conditions were found: <br>

![Screenshot 2024-06-23 191622](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/e8e0e57b-efa2-4385-b93a-8527d170c75d)

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here 
[Jira.csv](https://github.com/user-attachments/files/15945452/Jira.csv)

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:
<ul>
  <li>The test plan, including the scope, objectives, strategy, and schedule, must be reviewed and approved by all relevant stakeholders.
</li>
  <li>Detailed functional and non-functional requirements must be documented, reviewed, and approved.</li>
  <li>All test environments (development, staging, and production-like) must be fully configured and stable.</li>
  <li>Necessary hardware, software, network configurations, and permissions must be in place.</li>
  <li>Test data should mimic real-world scenarios as closely as possible.</li>
  <li>All test cases should be written, reviewed, and approved, covering functional, non-functional, and edge scenarios.</li>
  <li>A robust defect tracking system (e.g., JIRA, Bugzilla) should be set up and accessible to the entire team.</li>
</ul>


<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **Booking.com Cycle Summary**

Bugs have been created based on the failed tests. The complete bug reports can be found here: https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/blob/main/BugReport.doc


The following is a summary of the bugs that have been found
![Screenshot 2024-06-23 204405](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/2ddfc957-a97f-4f45-abd5-b591290fc2c7)


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 
![Screenshot 2024-06-23 204642](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/8b03e371-57eb-4afa-83a2-fda1fdd5db57)


Test execution chart was generated and can be found below. 
![Screenshot 2024-06-23 204856](https://github.com/AdinaGoja/Manual_Testing_Project_For_Booking.md/assets/161244199/9768d721-eea7-4e27-84c5-4366aceabbb2)


The final report shows that a number of 2 tests have failed of a total of 10.

A number of **2** total bugs were found, from which the priority is: **none** are high and **none** are medium.

<h3>General conclusion of testing</h3>
Overview of tests:
<ul>
  <li>Total tests created: 10</li>
  <li>Total tests executed: 10</li>
  <li>Test execution coverage: 100%</li>
  <li>Bugs found: 2. None of the founded bugs have an impact on the product launching, both of them can be fixed after the app is launched</li>
</ul>

About 80% of requirements in scope were covered, some functionalities haven`t been tested, like book a hotel or Manage your bookings.

Lessons learned: 
<ul>
  <li>Early Involvement of Test Team: Involve the testing team early in the project lifecycle to ensure all requirements are testable and to identify potential issues sooner.</li>
  <li>Comprehensive Test Planning: Allocate sufficient time for test planning and preparation to cover all functionalities comprehensively.</li>
  <li>Continuous Integration and Testing: Implement continuous integration and continuous testing practices to identify issues early and often.</li>
  <li>Effective Communication: Maintain clear and regular communication between development, testing, and business teams to ensure alignment on project goals and status.</li>
</ul>


