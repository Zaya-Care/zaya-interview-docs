# Backend pair programming exercise

## Summary
This document describes the tech part of the QA interview process that we need to follow.

## Phase 1 - Take Home Assessment
Build a simple REST API with a user and book resource. We want to add, find, update, and delete users and books via the API.

### Description
In this phase we want to assess the candidate's skills on Cypress, code quality, code readibility, and code architure in general.

### Requirements
- Code needs to be written using Cypress.
- After completing the exercise the candidate must create a public repository with the name {CANDIDATE_NAME}-qa-exercise and send the link to the repository to us.
- The repository must include a README.md file containing at least a section with instructions on how to run the code and another section on items that could've be improved if more time was given.

### Specs
- Create a new project and set up Cypress
- Create a scrapper that performs the following actions:
  - While in Desktop view 
  - Navigate to <https://www.simplyhired.com/>
  - Filter job posts with the following criterias:
    - Job type Full-time
    - Specific location (New York City)
    - Containing the skills JavaScript and React
    - Minimum Salary of $105,000
  - Order the results by Date
  - Return the top 5 job posts
  - While in Mobile view
  - Navigate to <https://www.simplyhired.com/>
  - Filter job posts with the following criterias:
    - Job type Contract
    - Specific location (New Jersey)
    - Containing the job title QA Engineer
    - Minimum Salary of $90,000
  - Order the results by Relevance
  - Return the top 5 job posts
- Create a repository named {CANDIDATE_NAME}-qa-exercise
- Create a README.md file with the instructions from the Requirements section above

## Phase 2 - Code walkthrough

### Description
In this phase we want the candidate to walk us through the code created in Phase 1 and explain the solution in details.

### Requirements
- Have the code from Phase 1 up and running prior to the interview call
- Be able to screen share to walk us through the code
- Explain the entire solution in details

