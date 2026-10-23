# EMI Calculator (Java)

## Description
A simple Java console application that calculates the Equated Monthly Installment (EMI) for a loan based on the loan amount, annual interest rate, and repayment period.

This project demonstrates basic Java programming concepts, including user input, variables, mathematical calculations, and console output.

## Features
- Accepts the loan amount in USD.
- Accepts the annual interest rate as a percentage.
- Accepts the loan repayment period in years.
- Converts the repayment period into months.
- Calculates the monthly loan payment (EMI).
- Displays the calculated EMI in the console.

## Technologies Used
- Java
- Java `Scanner` class
- Java `Math.pow()` method

## How to Run
1. Download or clone the repository.
2. Open the project in Eclipse, IntelliJ IDEA, or another Java IDE.
3. Ensure `EMICalculator.java` is located in the `day4` package.
4. Run the `EMICalculator` class.
5. Enter the requested loan information.

## Example
**Input:**
```text
Enter loan amount in USD
10000
Enter annual interest rate (in %)
5
Enter loan tenure in years
3
```

**Output:**
```text
Your monthly EMI is: 299.70897104665573
```

## EMI Formula

EMI = P × r × (1 + r)^n / ((1 + r)^n − 1)

Where:
- **P** = Principal loan amount
- **r** = Monthly interest rate
- **n** = Total number of monthly payments

## Java Concepts Practiced
- Variables and data types (`double`, `int`)
- User input using `Scanner`
- Arithmetic operations
- Mathematical calculations using `Math.pow()`
- Printing output using `System.out.println()`
- Converting annual interest rates into monthly rates

## Limitations
- The program assumes a fixed interest rate throughout the loan.
- It does not validate incorrect or negative inputs.
- A 0% interest rate is not handled correctly by the current formula.
- The output is not formatted to two decimal places.

## Future Improvements
- Add input validation.
- Support loans with 0% interest.
- Format EMI results as USD currency.
- Display the total amount paid and total interest.
- Add automated unit tests to verify calculations.

## Author
Brook Hassel

*Created as part of hands-on Java programming practice.*
