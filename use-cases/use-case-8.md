# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *delete an employee's details* so that *the company is compliant with data retention legislation*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee.  Database contains current employee details.

### Success End Condition

The employee's details are deleted.

### Failed End Condition

The employee's details are not deleted.

### Primary Actor

HR Advisor.

### Trigger

An employee leaves the company.

## MAIN SUCCESS SCENARIO

1. Management advise HR that the employee has left.
2. HR deletes the employee's details.
3. The company maintains compliance with data retention legislation.

## EXTENSIONS

3. **Employee not on database*:
   1. HR advisor informs management the employee's details have not been found.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0