# Password Reset Broken Logic

## Vulnerability Type
Broken Password Reset Workflow

## Lab Objective
Exploit logic flaw in password reset functionality to change another user's password.

## Injection Point / Weak Control
Password reset request parameter manipulation

## Payload / Technique Used
Modified password reset request targeting another user account

## Exploitation Steps
1. Initiated password reset request
2. Intercepted reset request using proxy
3. Modified username parameter
4. Submitted modified request
5. Successfully reset another user's password

## Impact
Attackers can take control of other user accounts by abusing flawed password reset logic.

## Mitigation
Validate reset tokens securely and bind them to specific user accounts.

## Key Learning Outcome
Learned how insecure password reset implementations can result in account takeover vulnerabilities.
