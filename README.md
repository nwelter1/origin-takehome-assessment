# Frontend Take-Home Assessment

**IMPORTANT**: you can choose any technology stack to implement this assignment. We (Origin) will consider exclusively the quality of your project (technology and product-wise) to evaluate your work.

This assessment was originally made by a finance comany called Origin. Below is their reasoning for giving you this assessment:

"One key to financial well-being is planning & saving for your goals. Users can have many saving goals (e.g. go to college or throw a wedding party) and it is our job to help them accomplish it.

You will build a piece of our savings feature by creating the savings plan simulation screen."

### The Saving Goal Plan Simulation Screen

![Saving Goal Plan Mockup Desktop](https://github.com/OriginFinancial/frontend-take-home-assignment/blob/master/mockups/saving-goal-plan-desk.png)

You will build a screen where the user will simulate saving towards the "Buy a house" savings goal.
In it, the users choose (i) the value they want to save and (ii) the date they plan to reach the goal.

When the users change the value of any of the inputs, the monthly deposit value is calculated and displayed to them.

# Development Instructions

### Evaluation
Be aware that the company will mainly take into consideration the following evaluation criteria:
* How close your page is to the mockups, both on mobile & desktop;
* How clean and organized your code is;
* If you implemented the business rules correctly.

### Assets
You can find the layout mockups here on their Figma project:
[Layout mockups](https://www.figma.com/file/Axdg0WSJURcxp8Arq3gg9x/Take-Home-Assignment-v2)

Once you have opened the link you must sign up and log in so you can have access to the colors, fonts, margins and assets information.

#### Money input

The money input component should:

- Allow only numbers
- Display the value formatted as money (e.g 3500.45 should be 3,500.45)
- We recommend you name this input as "amount"

#### Date input

The date input component should:

- Allow only future months
- When clicking on the arrow buttons it should go up and down month by month
- On focused, the users should be able to move the months by typing the Left and Right arrow key on the keyboard
- We recommend you name this input as "reachDate"

#### Confirm button

You don't need to add any action on the confirmation button
