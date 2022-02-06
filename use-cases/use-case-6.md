# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *view an employee's details* so that the *employee's promotion request can be supported*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee's details.  Database contains current employee details.

### Success End Condition

The employee's details are extracted from the database.

### Failed End Condition

The employee's details are not extracted from the database.

### Primary Actor

HR Advisor.

### Trigger

An employee requests a promotion.

## MAIN SUCCESS SCENARIO

1. An employee requests a promotion.
2. HR advisor captures the employee's name.
3. HR advisor extracts the employees details.
4. The employee's details are passed to their manager.

## EXTENSIONS

3. **Employee is not on the database**:
    1. HR advisor checks the details are correct.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0