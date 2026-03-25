# User Role Controlled by Request Parameter

## Vulnerability Type
Privilege Escalation via Parameter Manipulation

## Lab Objective
Modify role parameter to gain administrative privileges.

## Injection Point / Weak Control
role parameter in HTTP request

## Payload / Technique Used
role=admin

## Exploitation Steps
1. Intercepted request using proxy
2. Modified role parameter value
3. Sent modified request to server
4. Application granted elevated privileges

## Impact
Attackers can escalate privileges and perform unauthorized administrative actions.

## Mitigation
Avoid trusting client-controlled parameters for authorization decisions.

## Key Learning Outcome
Learned how privilege escalation occurs when authorization logic depends on user-controlled input.
