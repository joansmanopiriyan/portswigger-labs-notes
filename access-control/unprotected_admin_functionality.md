# Unprotected Admin Functionality

## Vulnerability Type
Missing Access Control

## Lab Objective
Access administrator panel without authentication restrictions.

## Injection Point / Weak Control
Direct access to administrative endpoint

## Payload / Technique Used
Manual browsing to /admin endpoint

## Exploitation Steps
1. Identified hidden admin panel endpoint
2. Accessed endpoint directly through browser
3. Application allowed unrestricted administrator access

## Impact
Attackers can access privileged administrative functionality without authorization.

## Mitigation
Restrict administrative endpoints using authentication and role-based authorization checks.

## Key Learning Outcome
Learned that security through obscurity (hidden URLs) does not replace proper authorization controls.
