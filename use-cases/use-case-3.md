# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As a *department manager* I want to *produce a report on the salary of employees in my department* so that I can *support financial reporting for my department*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the department.  Database contains current employee salary data.

### Success End Condition

A report is available for the manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department manager.

### Trigger

A request for finance information is sent to the department manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a department.
2. Department manager extracts salary information for the department.
3. Department manager provides report to finance.

## EXTENSIONS

3. **Salary information is not available**:
    1. Department manager informs finance the data is not available.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0