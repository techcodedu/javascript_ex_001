# Exercise: Basic Philippine Payroll Computation

## Objective
Practice using variables and basic arithmetic operations in JavaScript by computing a simplified Philippine payroll.

## Task

- Prompt the user to input their daily rate.
- Prompt the user to input the number of days they worked in the month.
- Prompt the user to input the number of overtime hours they've worked.
- Use the provided constant values for the various deductions.

### Deduction Constants
- **SSS Contribution:** PHP 500
- **PhilHealth Contribution:** PHP 300
- **PAG-IBIG Contribution:** PHP 200

### Overtime Calculation
Overtime is computed as: 
`overtime hours * (daily rate / 8) * 1.5`
(assuming an 8-hour work day and 1.5 times the hourly rate for overtime).

### Total Payroll Calculation
Compute the total payroll as:
`Total Payroll = (days worked * daily rate) + overtime pay - total deductions`

Finally, display the computed payroll amount using an alert.
