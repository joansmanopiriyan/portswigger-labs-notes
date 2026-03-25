# Blind SQL Injection – Time Delay Technique

## Vulnerability Type
Blind SQL Injection

## Lab Objective
Confirm SQL injection vulnerability using time delays.

## Injection Point
Tracking cookie parameter

## Payload Used
'|| pg_sleep(10)--

## Exploitation Steps
1. Identified injectable cookie parameter
2. Injected time-delay payload
3. Observed delayed server response
4. Confirmed blind SQL injection vulnerability

## Impact
Blind SQL injection allows attackers to extract database information without visible output.

## Mitigation
Use prepared statements and validate user-controlled inputs.

## Key Learning Outcome
Learned how timing-based responses confirm injection vulnerabilities without direct query results.
