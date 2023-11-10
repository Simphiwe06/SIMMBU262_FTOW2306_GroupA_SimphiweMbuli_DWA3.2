# Gherkin User Stories

This repository captures user stories in Gherkin syntax, detailing the behavior of the "+" and "-" buttons in the application.

## User Stories for the "+" Button

1. **Scenario: Incrementing Count with the "+" Button**
Given: the initial count is 0
When: the user clicks the "+" button
Then: the count should increase by 1
      
2. **Scenario: Multiple Clicks on the "+" Button**
   
Given: the initial count is 2
When: the user clicks the "+" button three times
Then: the count should increase to 5

## User Stories for the "-" Button

1. **Scenario: Decrementing Count with the "-" Button**
Given: the initial count is 3
When: the user clicks the "-" button
Then: the count should decrease by 1

2. **Scenario: Multiple Clicks on the "-" Button**
Given: the initial count is 6
When: the user clicks the "-" button twice
Then: the count should decrease to 4
