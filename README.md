## Overview

Everyone wants to budget their money better, and with the growing number of money manager apps being released, it seems that the tech world has taken notice. Some of these apps are more popular than others, since they offer a variety of in-depth analytical features. However, all of these apps offer the same fundamental features involving adding income and subtracting salaries. As a result, I've created a sleek, simple app that fulfills the most important features supported by any money manger app.

## Solving the Problem

In order to create a modern-looking money manager app, I needed to first create a step-by-step plan to create an app that supports all of the primary features. Once I created a plan, I then needed to architect the necessary UI and server controllers. I've included the steps below for a reference.

  1. Create an even handler
  2. Get input values
  3. Add the new item to our data structure
  4. Add the new item to the UI
  5. Calculate the budget
  6. Update the UI

## Example Output

Whether you need something that actually pays your bills for you or simply lets you know when your bank account is running dry, the solution is on this list. Bonus: Many of these tools are free.

## Architecture

Budget Controller:
- addItem
- calculateBudget
- calculateTotal
- getBudget

App Controller:
- ctrlAddItem (click/keypress)
- updateBudget
- updatePercentages
- ctrlDeleteItem (click)

- init
- setupEventListeners

UI Controller:
- getInput
- addListItem
- clearFields
- displayBudget

- getDOMstrings


