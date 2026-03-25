# Authentication Vulnerability – 2FA Simple Bypass

## Vulnerability Type
Two-Factor Authentication Bypass
 
## Lab Objective
Bypass the second authentication step and gain unauthorized access to another user account.

## Injection Point / Weak Control
Improper validation in 2FA verification workflow

## Payload / Technique Used
Direct navigation to authenticated endpoint without completing 2FA verification

## Exploitation Steps
1. Logged in using valid credentials
2. Observed application redirecting to 2FA verification step
3. Manually accessed authenticated endpoint before completing verification
4. Successfully bypassed 2FA protection

## Impact
Attackers can bypass multi-factor authentication and gain unauthorized access to protected user accounts.

## Mitigation
Ensure session authorization is granted only after successful completion of all authentication steps, including 2FA verification.

## Key Learning Outcome
Learned how improper session handling between authentication steps can allow attackers to bypass multi-factor authentication mechanisms.
