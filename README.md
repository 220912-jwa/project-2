# project-2
Project 2 Guidelines and Requirements  
> Project 2 is a group project in which the group decides on a full-stack application to design, create, and test

## Presentation
You and your team will present your project to the cohort on Wednesday November 2, 2022.

## General Requirements
1. Must be a full-stack web application
2. Development process must be Agile/Scrum utilizing Jira as a management tool for development and testing.
3. Application code must be on GitHub so that all team members can contribute
    - Create a repository in our GitHub Organization
    - naming convention -> `p2-team-<team number>` or `p2-<team name>`
4. Some reasonably complex data should be persisted (at least 3 tables with relations)
5. Must follow TDD and BDD Methodologies  
    - Cucumber Feature Files should be written first (at least 5 Feature Files)
    - Unit Tests are written first (at least 15 to start)
    - After these initial tests are written, coding implementations can be worked on. (More tests can be added as you work)
6. Test Documentation is used to guide development, including (but not limited to):
    - Test Plan
    - Requirement Traceability Matrix
    - Test Cases
    - Test Reporting
7. Types of Testing to complete: 
    - Unit Testing (JUnit and Mockito)
    - API Testing (Postman)
    - e2e Testing (Selenium and Cucumber)

## Technical Requirements
1. Back end must be as RESTful as possible (following REST constraints)
2. Back end uses the following technologies: Java 8+ with JDBC and Javalin
3. Front end is created with HTML, CSS/Bootstrap, and JavaScript
4. Back end is deployed on an AWS EC2 (Optional)
5. Front end is deployed on AWS S3 (Optional)
6. Database is PostgreSQL on AWS RDS


## Application Development and Testing Flow
> The below is a suggested work flow of how to design, build, and test your application.

### Planning
- **Identify System Requirements**
    - what application are you building
    - what features are we implementing

- **Proposed system is designed**
    - skeleton design of application is developed

- **Requirement Definition**
    - Document functional requirements (don't worry about non-functional requirements for this project)
    - Define acceptance criteria for requirements

- **Test Planning**
    - Determine types of tests to be performed (e.g. Unit testing, testing, api testing, e2e testing...)
    - Specify testing priorities and focus (e.g. what's going to be tested when and how?)

**At the end of this planning stage, you should have a completed Test Plan and Requirements Traceability Matrix**

### Test Case Development
- **Develop Test Cases**
    - using your RTM, create a Test Case Document that includes id, steps, preconditions, test data, expected results, etc. 
- **Write Feature Files**
    - Remember that multiple scenarios can be written in each feature file, but different features should have their own feature file
- **Begin writing Unit Tests**

**At the end of this Test Case Development stage, you should have a Test Case Document ready for Test Execution and some Test Scripts created**

### Development
- **Start implementing your system**
    - begin coding the features you've laid out
    - use the Unit Tests you created before to guide your development
    - use Jira and your Sprint Scrumban board to track your progress

- **Test / Integrate**
    - Test the new features you've created using your unit tests. 
    - And make sure they are compatible with the rest of the program as you move along in development (e.g. utilize your unit tests, postman, or anything you have prepared to do some regression testing)

## Reporting
- **Test Executions**
    - track your executions and report your findings
        - you can use built-in features of the testing tools we are using to report - and/or Jira
    - this includes any defects, bugs, or issues 
        - document these in a Defet Report
    - Update your RTM as you progress through your project


## Other things to keep in mind:
To reiterate the flow of Agile/Scrum for your Scrumban Board in your Jira Project:
- Product Backlog: all of the user stories for the application
- Sprint Backlog: all of the stories to be completed for the current sprint  
    - for Project 2 the Product Backlog and Sprint Backlog will be the same
- In Progress: the stories currently being worked on; this should be ONE per developer (aside from setup tasks like building database schema, models, etc.)  
- Testing: the stories currently being tested by the person who worked on the story; if a developer has a story here, they should not have one in the other sections (unless it's complete).  
- Peer Review: the stories which are being tested and whose code quality is being reviewed by another group member (a developer who did not work on the story)
- Complete: the stories which have been completed, tested, and reviewed; once a story gets here, the developer working on it can begin a new story

## Example Apps (that you can totally use as ideas)
- E-Commerce Site (Products, Cart, Checkout)
- 

## Day 1 / Setup / Kick-Off
> This will be Thursday afternoon for us
- Brainstorm with your group -> come up with 3-5 rough ideas for a full-stack web application
- Meet with Dan to present your ideas and we'll decide on THE idea that you'll move forward with. 
- Together as a team, write a description of your chosen application along with your functional requirements/user stories (broken up into 2 categories: MVP and Stretch Goals).
- Submit (via GitHub as a README.md) your description and user stories to Dan for a final review
