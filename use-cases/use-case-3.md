# USE CASE: 3 Produce a Report on the Salary of Employees in managers department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee salary and department data.

### Success End Condition

A report is available for department manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department manager

### Trigger

A request for salary information is sent to Department manager.

## MAIN SUCCESS SCENARIO

1. Department manager requests salary information for their department.
2. Department manager captures department to get salary information for.
3. Department manager extracts current salary information of department.
4. Department manager provides report to finance.

## EXTENSIONS

3. **Department does not have employees**:
    1. Department manager informs finance no employees exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
