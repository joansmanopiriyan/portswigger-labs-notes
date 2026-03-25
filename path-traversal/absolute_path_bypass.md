# File Path Traversal – Absolute Path Bypass

## Vulnerability Type
Directory Traversal Filter Bypass

## Lab Objective
Bypass traversal sequence filtering using absolute file paths.

## Injection Point
Filename parameter

## Payload Used
/etc/passwd

## Exploitation Steps
1. Attempted standard traversal payload
2. Application blocked traversal sequences
3. Tested absolute file path instead
4. Successfully retrieved system file

## Impact
Attackers can bypass input filtering mechanisms and access restricted files directly.

## Mitigation
Restrict file access using allowlists instead of blocking traversal sequences.

## Key Learning Outcome
Learned how absolute paths bypass poorly implemented traversal protections.
