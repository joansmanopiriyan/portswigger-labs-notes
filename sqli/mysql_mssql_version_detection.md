# SQL Injection – Database Version Detection (MySQL / MSSQL)

## Vulnerability Type
SQL Injection for database fingerprinting

## Lab Objective
Determine backend database version.

## Injection Point
Product filter parameter

## Payload Used
' UNION SELECT @@version--

## Exploitation Steps
1. Confirmed injectable parameter
2. Used UNION-based injection
3. Retrieved database version string
4. Verified backend DBMS type

## Impact
Version disclosure helps attackers identify known vulnerabilities.

## Mitigation
Use parameterized queries and suppress verbose database responses.

## Key Learning Outcome
Learned how DBMS-specific variables expose version details.
