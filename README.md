## Software Delivery Cycle

A software development life cycle (SDLC) model is a conceptual framework describing all activities in a software development project from planning to maintenance.


•	SDLC encompasses: planning, implementation, testing, documentation, deployment and maintenance.

•	Models shifted from traditional staged SDLC processes, to agile, and then to Devops.

•	Agile and Devops as practices merged traditional staging in new and interesting ways

•	The cloud brought the arrival of web-delivered resources into the picture.

•	Although SDLC is now much changed, the concept remains largely the same.

Phase 1: Planning

In the planning phase, project goals are determined and a high-level plan for the intended project is established. 
1.	      Identification of the system for development
2.	      Feasibility assessment
3.	      Creation of project plan

Phase 2: Analysis

In the analysis phase, end user business requirements are analyzed and project goals converted into the defined system functions that the organization intends to develop. 
1.	      Gathering business requirement
2.	      Creating process diagrams
3.	      Performing a detailed analysis

Phase 3: Design

In the design phase, we describe the desired features and operations of the system. This phase includes business rules, pseudo-code, screen layouts, and other necessary documentation. The two primary activities involved in the design phase are as follows:
1.	      Designing of IT infrastructure
2.	      Designing of system model

Phase 4: Development

In the development phase, all the documents from the previous phase are transformed into the actual system. The two primary activities involved in the development phase are as follows:
1.	      Development of IT infrastructure
2.	      Development of database and code

Phase 5: Testing

In the testing phase, all the pieces of code are integrated and deployed in the testing environment. Testers then follow Software Testing Life Cycle activities to check the system for errors, bugs, and defects to verify the system’s functionalities work as expected or not, often. The two primary activities involved in the testing phase are as follows:
1.	   Writing test cases
2.	   Execution of test cases

Phase 6: Deployment

During this next phase, the system is deployed to a real-life (the client’s) environment where the actual user begins to operate the system. All data and components are then placed in the production environment. This phase is also called referred to as ‘delivery.’

Phase 7: Maintenance

In the maintenance phase, any necessary enhancements, corrections, and changes will be made to make sure the system continues to work, and stay updated to meet the business goals. It is necessary to maintain and upgrade the system from time to time so it can adapt to future needs. The three primary activities involved in the maintenance phase are as follows:
1.	      Support the system users
2.	      System maintenance
3.	      System changes and adjustment



## Test Driven Development
Test Driven Development (TDD) in simple terms, test cases for each functionality are created and tested first and if the test fails then the new code is written in order to pass the test and making code simple and bug-free.

Basically, TDD is use to write and correct the failed tests before writing new code (before development). This helps to avoid duplication of code as we write a small amount of code at a time in order to pass tests. (Tests are nothing but requirement conditions that we need to test to fulfill them).

How to perform TDD test: 
1.	Add a test.
2.	Run all tests and see if any new test fails.
3.	Write some code.
4.	Run tests and Refactor code.
5.	Repeat.



## Continuous Integration

Continuous Integration (CI) is the process of automating the build and testing of code every time a team member commits changes to version control. CI encourages developers to share their code and unit tests by merging their changes into a shared version control repository after every small task completion.

Teams use build definitions to ensure that every commit to the master branch triggers the automated build and testing processes.  Implementing CI this way ensures bugs are caught earlier in the development cycle, which makes them less expensive to fix.  Automated tests run for every build to ensure builds maintain a consistent quality



## Continuous Delivery

Continuous Delivery is basically ensuring your codebase is ready to deploy safely at any point in time. Deployments include all changes associated with new features, bug fixes and features in the early stages of development which can be enabled using feature flags for target users to test in their production environments.

Continuous delivery is the next step in the process where the tested code from continuous integration is automatically deployed in various environments by a manual trigger.


## Configuration Management
Configuration management (CM) focuses on establishing and maintaining consistency of a product's performance, and its functional and physical attributes with its requirements, design, and operational information throughout its life.

A configuration management tool can improve the organization's change-impact analysis, reducing the outages caused by production changes. Without configuration management in place, it is nearly impossible to understand the impact of any changes to an environment.

Configuration management combines valid service models, CI interdependency mapping and correlations made between CIs and requests for changes to help restore services faster during an outage.


## Containerization

Containerization is the process of packaging an application along with its required libraries, frameworks, and configuration files together so that it can be run in various computing environments efficiently. In simpler terms, containerization is the encapsulation of an application and its required environment.


## Cloud Scalability, and Reliability

Scalability is the capability of a process, network, software or appliance to grow and manage increased demands. Through scalability you can scale up your data storage capacity or scale it down to meet the demands of your growing business.

Reliability is the most important feature of any application, because if the application is not reliable, users will eventually leave, and the other features won't matter.

•	An application must have measurable reliability goals, and deviations must be promptly corrected.

•	The application must be architected for scalability, high availability, and automated change management.

•	The application must be self-healing where possible, and it must be instrumented for observability.

•	The operational procedures used to run the application must impose minimal manual work and cognitive load on operators, while ensuring rapid mitigation of failures.

