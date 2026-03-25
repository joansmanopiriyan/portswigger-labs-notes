# Insecure Direct Object Reference (IDOR)

## Vulnerability Type
Broken Object-Level Authorization

## Lab Objective
Access another user’s data by modifying object identifier.

## Injection Point / Weak Control
User ID parameter in request

## Payload / Technique Used
Modified user ID value

## Exploitation Steps
1. Observed user ID parameter in request
2. Changed identifier value manually
3. Accessed another user's data successfully

## Impact
Attackers can view or modify other users’ sensitive information.

## Mitigation
Implement server-side authorization checks for each object access request.

## Key Learning Outcome
Learned how insecure object references expose sensitive data between users.
