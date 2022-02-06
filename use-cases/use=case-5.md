# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *add a new employee's details* so that I can *ensure the new employee is paid*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee's details.  Database contains current employee details.

### Success End Condition

The employee's details are added to the database.  The employee gets paid

### Failed End Condition

The employee's details are not added to the database.  The employee does not get paid.

### Primary Actor

HR Advisor.

### Trigger

HR are informed that a new employee has joined the company.

## MAIN SUCCESS SCENARIO

1. HR are informed a new employee has joined the company.
2. HR advisor captures the employee's details.
3. HR advisor inputs the employee's details to the database.
4. The employee's details are added to the database.

## EXTENSIONS

3. **Employee is already on the database**:
   1. HR advisor checks the details are correct.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0