# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *update an employee's details* so that *employee's details are kept up-to-date*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee.  Database contains current employee details.

### Success End Condition

The employee's details are updated.

### Failed End Condition

The employee's details are not updated.

### Primary Actor

HR Advisor.

### Trigger

HR are advised of changes in an employee's details.

## MAIN SUCCESS SCENARIO

1. Employee advises HR of a change in details.
2. HR extracts the current details of the employee.
3. HR updates the employee's details where they have changed.
4. The employee's updated details are stored.

## EXTENSIONS

3. **Employee's details are not on the database**:
    1. HR advisor adds employee to the database.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0