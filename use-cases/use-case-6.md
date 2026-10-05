# USE CASE: 6 Produce a Report on employees details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to view and employee's details so that the employee's promotion request can be supported.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee information.

### Success End Condition

The employees details are available for HR to support promotion request.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

An employees promotion request is sent to HR.

## MAIN SUCCESS SCENARIO

1. HR advisor receives an employee promotion request.
2. HR advisor identify employee.
3. HR advisor extracts employee information.
4. HR advisor view employee details to support promotion request.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor is informed that employee doesn't exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
