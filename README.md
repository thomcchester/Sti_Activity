# Group based STI activity

This was a just a small little group exercise. It is just a single js file that automatically calctuylates employee STI (short term incentive...bonus) for a company.


**Each array currently is configured in this way**:
The first item holds the employees name.
The second item has their employee number.
The third item is their annual salary.
The fourth item is their review rating.


Given the arrays we created a function that consumes one employee array, and returns another array that contains:
- The first item should also contain the employees name.
- The second item should contain the percentage of STI the employee is to receive.
- The third item should be the adjusted annual compensation (base annual + STI)
- The fourth item should be the employees total bonus rounded to the nearest dollar.

To calculate an individuals STI:
- Those who have a rating of a 2 or below should not receive a bonus.
- Those who have a rating of a 3 should receive a base bonus of 4% of their base annual income.
- Those who have a rating of a 4 should receive a base bonus of 6% of their base annual income.
- Those who have a rating of a 5 should receive a base bonus of 10% of their base annual income.
- If they have 4 employee numbers, this means they have been with the company for longer than 15 years,
and should receive an additional 5%.
- However, if their annual income is greater than $65,000, they should have their bonus adjusted down 1%.
- No bonus can be above 13% total.


Finally it iterates over the `employees` array and input each index of the array to out first function, and  then it `console.log`s the results of each iteration.
