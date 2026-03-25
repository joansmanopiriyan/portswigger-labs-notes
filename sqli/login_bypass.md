# SQL Injection – Authentication Bypass

## Vulnerability Type
SQL Injection in login authentication

## Lab Objective
Bypass login functionality without valid credentials.

## Injection Point
Username input field in login form

## Payload Used
administrator'--

## Exploitation Steps
1. Identified login form accepting user input
2. Injected SQL comment sequence after administrator username
3. Password validation logic ignored
4. Successfully logged in as administrator

## Impact
Allows attackers to gain unauthorized administrative access.

## Mitigation
Use parameterized queries and proper input validation.

## Key Learning Outcome
Learned how SQL comments terminate query conditions to bypass authentication checks.
