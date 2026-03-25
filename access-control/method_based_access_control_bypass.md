# Method-Based Access Control Bypass

## Vulnerability Type
HTTP Method Manipulation

## Lab Objective
Bypass access restrictions by changing HTTP request method.

## Injection Point / Weak Control
HTTP request method (GET → POST)

## Payload / Technique Used
Changed request method in proxy tool

## Exploitation Steps
1. Identified restricted functionality
2. Modified HTTP method from GET to POST
3. Resent request
4. Server accepted unauthorized action

## Impact
Attackers can bypass authorization checks by altering HTTP methods.

## Mitigation
Apply consistent authorization checks across all HTTP methods.

## Key Learning Outcome
Learned that access control must be enforced independently of request method.
