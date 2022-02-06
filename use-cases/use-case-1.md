# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want to *produce a report on the salary of all employees* so that I can *support financial reporting of the organisation*.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current employee salary data.

### Success End Condition

A report is available for HR to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for the company.
2. HR advisor extracts current salary information of all employees.
3HR advisor provides report to finance.

## EXTENSIONS

3. **Salary information does not exist**:
    1. HR advisor informs finance no salary information available.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0