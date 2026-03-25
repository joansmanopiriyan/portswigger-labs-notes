# File Path Traversal – URL Decode Bypass

## Vulnerability Type
Directory Traversal Encoding Bypass

## Lab Objective
Exploit URL decoding behavior to bypass traversal filters.

## Injection Point
Filename parameter

## Payload Used
..%252f..%252f..%252fetc/passwd

## Exploitation Steps
1. Observed traversal sequences were filtered
2. Used double URL encoding technique
3. Application decoded payload before validation
4. Successfully accessed restricted file

## Impact
Encoding-based bypass allows attackers to evade input filtering mechanisms.

## Mitigation
Normalize input before validation and restrict file access paths securely.

## Key Learning Outcome
Learned how encoding techniques bypass security filters during input processing.
