# Paylocity: Bug Challenge

## Reports:

[UI Defect Report](./reports/ui_defects.md)


[API Defect Report](./reports/api_defects.md)


[Three Detailed Defects (with steps to reproduce)](./reports/detailed_defects.md)


## Acceptance Criteria
### Scenario 1: Add Employee
    GIVEN an Employer
    AND I am on the Benefits Dashboard page
    WHEN I select Add Employee
    THEN I should be able to enter employee details
    AND the employee should save
    AND I should see the employee in the table
    AND the benefit cost calculations are correct

### Scenario 2: Edit Employee
    GIVEN an Employer
    AND I am on the Benefits Dashboard page
    WHEN I select the Action Edit
    THEN I can edit employee details
    AND the data should change in the table

### Scenario 3: Delete Employee
    GIVEN an Employer
    AND I am on the Benefits Dashboard page
    WHEN I click the Action X
    THEN the employee should be deleted

## Assumptions:
 - All employees are paid $2000 per paycheck before deductions
 - There are 26 paychecks in a year
 - The cost of benefits is $1000/year for each employee
 - Each dependent incurs a cost of $500/year


 Report prepared by [Jim Gray](https://github.com/JimGray9999)