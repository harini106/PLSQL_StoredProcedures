# PL/SQL Stored Procedures

## Overview

This project demonstrates the implementation of **Stored Procedures** in PL/SQL using three banking scenarios.

The procedures automate common banking operations such as processing monthly interest, updating employee bonuses, and transferring funds between accounts.

---

## Project Structure

```
PLSQL_StoredProcedures/
│── ProcessMonthlyInterest.sql
│── UpdateEmployeeBonus.sql
│── TransferFunds.sql
└── README.md
```

---

## Scenario 1: Process Monthly Interest

### Objective

Apply a **1% monthly interest** to all savings accounts.

### Concepts Used

- Stored Procedure
- UPDATE Statement
- COMMIT
- DBMS_OUTPUT

---

## Scenario 2: Update Employee Bonus

### Objective

Increase employee salaries based on the department and bonus percentage provided as input.

### Concepts Used

- Stored Procedure with Parameters
- UPDATE Statement
- COMMIT
- DBMS_OUTPUT

---

## Scenario 3: Transfer Funds

### Objective

Transfer funds from one account to another after verifying that the source account has sufficient balance.

### Concepts Used

- Stored Procedure with Parameters
- SELECT INTO
- IF-ELSE Condition
- UPDATE Statement
- COMMIT
- DBMS_OUTPUT

---

## Prerequisites

- Oracle Database
- Oracle SQL Developer
- Accounts table
- Employees table

---

## How to Execute

Run the required SQL file in Oracle SQL Developer.

Example:

```sql
@ProcessMonthlyInterest.sql
```

Then execute the procedure:

```sql
BEGIN
    ProcessMonthlyInterest;
END;
/
```

Repeat similarly for the other procedures.

---

## Learning Outcomes

After completing this project, you will be able to:

- Create and execute stored procedures.
- Pass parameters to procedures.
- Perform database updates using PL/SQL.
- Use conditional logic within procedures.
- Automate common banking operations.

---

## Author

**Harini**
