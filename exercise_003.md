# Exercise: Basic Philippine Payroll Computation

## Objective:
Practice using variables and basic arithmetic operations in JavaScript by computing a simplified Philippine payroll.

## Task:

1. Prompt the user to input their daily rate.
2. Prompt the user to input the number of days they worked in the month.
3. Prompt the user to input the number of overtime hours they've worked.
4. Use the provided constant values for the various deductions.

### Deduction Constants:
- **SSS Contribution:** PHP 500
- **PhilHealth Contribution:** PHP 300
- **PAG-IBIG Contribution:** PHP 200

Overtime is computed as:
\[ \text{overtime hours} \times \left( \frac{\text{daily rate}}{8} \right) \times 1.5 \]
(assuming an 8-hour work day and 1.5 times the hourly rate for overtime).

Compute the total payroll as:
\[ \text{Total Payroll} = (\text{days worked} \times \text{daily rate}) + \text{overtime pay} - \text{total deductions} \]

Display the computed payroll amount using an alert.
