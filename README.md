# 🗄️ DATABASE MANAGEMENT SYSTEMS LAB

### `Academic Session : 2024–25`

```sql
SYSTEM STATUS : ONLINE
DATABASE ENGINE : ORACLE DBMS
LANGUAGE STACK : SQL | PL/SQL
CONNECTIVITY    : ODBC
LAB MODE        : PRACTICAL EXECUTION
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF99&center=true&vCenter=true&width=1000&lines=DATABASE+MANAGEMENT+SYSTEMS+LAB;ER+MODELING+%7C+SQL+%7C+PL%2FSQL;ORACLE+DATABASE+EXPERIMENTS;TRANSACTIONS+%7C+TRIGGERS+%7C+PROCEDURES" />

---

# 📡 DATABASE OVERVIEW

```text
┌──────────────────────────────────────────────┐
│           DBMS LAB SUMMARY 2024-25           │
├──────────────────────────────────────────────┤
│ Focus Area : Relational Databases            │
│ Platform   : Oracle DBMS                     │
│ Interface  : SQL*Plus / SQL Developer        │
│ Language   : SQL & PL/SQL                    │
│ Objective  : Database Design & Automation    │
└──────────────────────────────────────────────┘
```

---

# 🏗️ DATABASE SCHEMA OF LEARNING

```text
                    ┌─────────────┐
                    │    DBMS     │
                    └──────┬──────┘
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼
   ER MODELS           SQL QUERIES        PL/SQL
        │                  │                  │
        ▼                  ▼                  ▼
 RELATIONAL DB      DATA OPERATIONS    AUTOMATION
        │                  │                  │
        └──────────────┬───┴──────────────┬───┘
                       ▼                  ▼
                 TRIGGERS            ODBC CONNECTIVITY
```

---

# 🧩 PRACTICAL EXECUTION LOGS

## TABLE : PRACTICALS_PERFORMED

| ID | Experiment                      | Status      |
| -- | ------------------------------- | ----------- |
| 01 | ER & EER Diagram Design         | ✅ Completed |
| 02 | SQL DDL & DML Commands          | ✅ Completed |
| 03 | SQL Functions                   | ✅ Completed |
| 04 | SQL Operators                   | ✅ Completed |
| 05 | Subqueries & Joins              | ✅ Completed |
| 06 | PL/SQL Programming              | ✅ Completed |
| 07 | Binary Conversion Function      | ✅ Completed |
| 08 | Banking Fund Transfer Procedure | ✅ Completed |
| 09 | Database Triggers               | ✅ Completed |
| 10 | ODBC Database Connectivity      | ✅ Completed |

---

# 🔍 QUERY EXECUTION DETAILS

## 01. ER & EER MODELING

```sql
CREATE DATABASE Knowledge;
```

✔ Designed Entity Relationship Diagrams

✔ Created Enhanced ER Models

✔ Converted conceptual models into relational schemas

✔ Developed schema representations

---

## 02. SQL OPERATIONS

```sql
CREATE TABLE Student(
   Student_ID NUMBER PRIMARY KEY,
   Name VARCHAR2(50)
);

INSERT INTO Student VALUES(1,'Aishi');
UPDATE Student SET Name='Aishi De';
DELETE FROM Student WHERE Student_ID=1;
```

✔ Data Definition Language (DDL)

✔ Data Manipulation Language (DML)

✔ Table Management Operations

---

## 03. SQL FUNCTIONS

```sql
SELECT COUNT(*),
       AVG(Salary),
       MAX(Salary),
       MIN(Salary)
FROM Employee;
```

### Functions Explored

```text
Aggregate Functions
Numeric Functions
Date Functions
String Functions
Conversion Functions
```

---

## 04. SQL OPERATORS

```sql
SELECT *
FROM Employee
WHERE Salary BETWEEN 30000 AND 50000
AND Department='IT';
```

### Operators Used

```text
AND
OR
NOT
LIKE
BETWEEN
IN
```

---

## 05. SUBQUERIES & JOINS

```sql
SELECT E.Name,D.Department_Name
FROM Employee E
INNER JOIN Department D
ON E.Dept_ID=D.Dept_ID;
```

### Concepts Covered

```text
INNER JOIN
LEFT JOIN
RIGHT JOIN
Nested Queries
```

---

## 06. PL/SQL PROGRAMMING

```sql
DECLARE
   num NUMBER:=10;
BEGIN
   IF num>5 THEN
      DBMS_OUTPUT.PUT_LINE('Valid');
   END IF;
END;
/
```

### Topics Covered

```text
Variables
Conditions
Loops
Exception Handling
```

---

## 07. DECIMAL TO BINARY FUNCTION

```sql
CREATE OR REPLACE FUNCTION Decimal_To_Binary
RETURN VARCHAR2;
```

✔ User Defined Functions

✔ Number Conversion Logic

✔ Iterative Processing

---

## 08. BANK FUND TRANSFER PROCEDURE

```sql
CREATE OR REPLACE PROCEDURE Fund_Transfer
(
  Sender_ID NUMBER,
  Receiver_ID NUMBER,
  Amount NUMBER
)
```

### Features

```text
Balance Verification
Transaction Processing
Error Handling
Data Consistency
```

---

## 09. DATABASE TRIGGERS

```sql
CREATE OR REPLACE TRIGGER Audit_Trigger
BEFORE INSERT OR UPDATE
ON Employee;
```

### Trigger Operations

```text
Automatic Validation
Data Auditing
Business Rule Enforcement
Integrity Maintenance
```

---

## 10. ODBC CONNECTIVITY

```text
Application
      │
      ▼
    ODBC
      │
      ▼
Oracle Database
```

✔ Standardized Database Communication

✔ Cross Platform Connectivity

✔ Data Exchange Mechanisms

---

# 🎯 LEARNING OUTCOMES

```sql
SELECT Skills_Acquired
FROM DBMS_Lab;
```

### OUTPUT

```text
✓ Database Design & Modeling

✓ Relational Schema Development

✓ SQL Query Formulation

✓ Data Retrieval Techniques

✓ Joins & Subqueries

✓ PL/SQL Programming

✓ Stored Procedures

✓ Functions & Triggers

✓ Database Integrity Management

✓ ODBC Connectivity

✓ Real-World Database Development
```

---

# ⚙️ TECHNOLOGY STACK

<table align="center">
<tr>
<td align="center">🗄️ Oracle DB</td>
<td align="center">📜 SQL</td>
<td align="center">⚡ PL/SQL</td>
<td align="center">🔌 ODBC</td>
</tr>
</table>

---

# 📊 FINAL EXECUTION REPORT

```sql
SELECT Result
FROM DBMS_Lab
WHERE Academic_Year='2024-25';
```

### OUTPUT

```text
The DBMS Laboratory provided extensive practical
experience in database design, implementation,
query optimization, procedural programming,
trigger development, and database connectivity.

STATUS : SUCCESSFULLY COMPLETED

DATABASE KNOWLEDGE ACQUIRED : HIGH

READY FOR :
✓ Database Development
✓ Database Administration
✓ Enterprise Applications
✓ Backend System Design
```

---

<div align="center">

## 🟢 SESSION CLOSED

```sql
COMMIT;
```

### Database Knowledge Successfully Stored.

</div>
