# SQL Injection – Database Version Detection (Oracle)

## Vulnerability Type
SQL Injection for database fingerprinting

## Lab Objective
Identify backend database type and version.

## Injection Point
Product category parameter

## Payload Used
' UNION SELECT banner, NULL FROM v$version--

## Exploitation Steps
1. Confirmed SQL injection using test payload
2. Attempted UNION-based query
3. Extracted version information from Oracle system table
4. Identified backend database successfully

## Impact
Database fingerprinting enables attackers to craft targeted exploitation strategies.

## Mitigation
Restrict database error output and implement parameterized queries.

## Key Learning Outcome
Learned how attackers enumerate backend database details during reconnaissance.
