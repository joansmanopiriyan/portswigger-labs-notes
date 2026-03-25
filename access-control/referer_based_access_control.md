# Referer-Based Access Control Bypass

## Vulnerability Type
Improper Access Control Based on Referer Header

## Lab Objective
Bypass access restriction enforced using Referer header validation.

## Injection Point / Weak Control
Referer HTTP header

## Payload / Technique Used
Modified Referer header manually

## Exploitation Steps
1. Intercepted restricted request
2. Modified Referer header value
3. Resent request
4. Access granted successfully

## Impact
Attackers can bypass authorization by spoofing HTTP headers.

## Mitigation
Avoid using client-controlled headers for access control decisions.

## Key Learning Outcome
Learned why Referer header validation is unreliable for enforcing authorization.
