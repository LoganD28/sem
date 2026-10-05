# USE CASE: 1 Produce a Report on the Salary of ALL Employees 

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to produce a report on the salary of all employees so that I can support financial reporting of the organisation.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee salary data.

### Success End Condition

A report containing salary information of all employees

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for employee salary information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for all employees.
2. HR advisor captures salary information.
3. HR advisor extracts current salary information of all employees.
4. HR advisor provides report to finance.

## EXTENSIONS

3. **No employee salary information is available**:
    1. HR advisor informs finance salary information isn't available.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
