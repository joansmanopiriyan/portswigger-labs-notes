# File Path Traversal – Non-Recursive Strip Bypass

## Vulnerability Type
Directory Traversal Filter Bypass

## Lab Objective
Exploit improper sanitization where traversal sequences are removed only once.

## Injection Point
Filename parameter

## Payload Used
....//....//....//etc/passwd

## Exploitation Steps
1. Observed traversal payload filtering
2. Identified non-recursive removal of ../ sequences
3. Used modified traversal payload
4. Successfully accessed system file

## Impact
Improper sanitization allows attackers to bypass protections and read sensitive files.

## Mitigation
Apply recursive validation and normalize file paths before processing.

## Key Learning Outcome
Learned how weak input filtering logic can be bypassed using modified traversal patterns.
