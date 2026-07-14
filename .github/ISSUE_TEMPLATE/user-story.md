---
name: User Story
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** User
 **I need** a service that has counter 
 **So that** I can keep track of how many times something has been done.
   
 ### Details and Assumptions
Need a way to increment the counter
Need a way to get the current value
   
 ### Acceptance Criteria  
   
 ```gherkin
Given i have incremented the counter to 2
When i make a call to get the current value
Then i should return 2 as the current value
 ```
