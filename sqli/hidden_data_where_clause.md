# SQL Injection – WHERE Clause (Retrieving Hidden Data)

## Vulnerability Type
SQL Injection in WHERE clause

## Lab Objective
Retrieve hidden products not normally visible in the application by modifying the SQL query logic.

## Injection Point
Category filter parameter in product listing request

## Payload Used
' OR 1=1--

## Exploitation Steps
1. Observed category parameter in product filter request
2. Injected payload into category parameter
3. Application returned additional hidden products
4. Confirmed query logic manipulation

## Impact
Attackers can bypass application filtering logic and retrieve unauthorized data from database queries.

## Mitigation
Use parameterized queries (prepared statements) instead of dynamic SQL query construction.

## Key Learning Outcome
Learned how SQL injection modifies conditional filtering logic inside WHERE clauses.
