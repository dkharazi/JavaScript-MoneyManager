## Overview

Everyone wants to budget their money better. And with the growing number of money manager apps being released, it seems that the tech world has taken notice. Some of these apps are more popular than others because they offer a variety of in-depth analytical features. However, all of these apps seem to offer the same fundamental features involving adding income and subtracting salaries. As a result, I've created a sleek, simple app that fulfills the most necessary tasks that are supported by any money manger app.

## Solving the Problem

In order to create a modern-looking money manager app, I needed to first create a step-by-step plan to create an app that supports all of the primary features. Once I created a plan, I then needed to architect the necessary UI and server controllers. I've included the steps below for a reference.

  1. Create an even handler
  2. Get input values
  3. Add the new item to our data structure
  4. Add the new item to the UI
  5. Calculate the budget
  6. Update the UI
  
## Architecture

- `addItem:` Adds an item to the list of expenses or income behind the scenes.
- `calculateBudget:` Calculates the budget behind the scenes.
- `calculateTotal:` Calculates the total behind the scenes.
- `clearFields:` Clears any text from the fields from the UI when necessary.
- `ctrlAddItem:` Adds an item to the UI once a mouse or keyboard click has been received.
- `ctrlDeleteItem:` Deletes an item from the UI once a mouse click has been received.
- `displayBudget:` Displays the budget to the UI on startup.
- `getDOMstrings:` A helper method that saves all of the DOMS.
- `getBudget:` Calculates the total behind the scenes.
- `getInput:` Gets any input from the event listeners.
- `init:` Initializes the app.
- `setupEventListeners:` Sets up any event listeners.
- `updateBudget:` Updates the budget to the UI.
- `updatePercentages:` Updates the percentages to the UI.

<p align="center">
  <img width="800" height="500" src="/img/arch.png">
</p>

## Example Output

<p align="center">
  <img width="800" height="500" src="/img/example.png">
</p>


