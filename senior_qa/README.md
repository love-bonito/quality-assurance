# Senior QA Automation Engineer Challenge

As a QA Automation Engineer, one should be able to explore and understand application functionality, recommend automation strategy and automate different type of tests.

## First Challenge (UI Test Automation)

Create a free account here https://trello.com/. It is used for collaborative work across team members. You can create Boards, tasks lists and tasks.

On the first challenge, we need you to perform a UI automation to test new task creation

- Create a boilerplate automation project
- Open trello in browser
- Login with valid credentials
- Open a trello Board
- Create a card in first list of that board
- Verify that the card is successfully created

#### Considerations
- The test should be data independent. i.e. It should come from a data file and I should be able to execute it with different data set
- You can use any tool (preferably Nightwatchjs)

## Second Challenge (API Test Automation)

Trello also has a web api documented here https://developers.trello.com/reference#introduction.

In this challenge, we need you to perform an API automation to test new task creation

- Set up key and tokens
- Get board id
- Create a card in first list of that board
- Verify that the card is successfully created

#### Considerations
- The test should be data independent. i.e. It should come from a data file and I should be able to execute it with different data set
- You can use any javascript framework (preferably mochajs + supertest)

## Third Challenge (Test Data Generation)

In the first challenge, we did not create a board and a list in our scripts as pre-requisite. We need to create/reset any pre-requisite data To make sure our test run successfully even if the test data is corrupted/removed

- Configure the test so that in pre-hooks it creates/resets a board and a list as required

#### Considerations
- The user account does not need to be created in script as pre-requisite.
- For pre-requisite data setup, better to use api instead of UI

## Forth Challenge (headless execution through command line)

The tests should be executable headless from the command line. You can use docker for all the dependencies.

## Lastly

Document the project, **how to run the tests**.

The README file should have all the step to set up the project locally. Remember as less command for setting up the project much better.

After you have the documentation, create a repository in GitLab/Github/Bitbucket and send us the link of the repository

The time estimated for the project is between 1 and 5 hours if you feel that will take more you can cut corners, but that will affect the result of the test. Anyways you still have a complete week to finish the test after you received it.

We are going to give you feedback as fast as possible.

