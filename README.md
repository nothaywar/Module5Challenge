# Module5Challenge
This repository contains Python scripts for financial planning tools related to personal finance and retirement planning. The tools utilize Alapca API and libraries to collect data and perform Monte Carlo simulations for financial analysis.

## Functions
Here is a short explanation to my functions.
- `check_health`: this function is used to validate the saving health of an individual by comparing their total savings to an ideal emergency fund. (required input:your total saving)
    - If the total_savings is greater than the emergency_fund, it prints a congratulatory message indicating that the individual has enough money in their emergency fund.
    - If the total_savings is equal to the emergency_fund, it prints a congratulatory message indicating that the individual has reached their financial goal of an emergency fund.
    - If the total_savings is less than the emergency_fund, it calculates the shortfall by subtracting the total_savings from the emergency_fund. It then prints a message indicating the shortfall amount, expressing how much the individual is away from reaching their emergency fund goal.

- `get_health`: this function calculates the expected portfolio return at the 95% lower and upper confidence intervals based on an initial investment. (required inputs: initial investment, table of summary, and an optional parameter number of year with a default value of 30.)


