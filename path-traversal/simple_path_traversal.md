# File Path Traversal – Simple Case

## Vulnerability Type
Directory Traversal

## Lab Objective
Access sensitive system files outside the web root directory.

## Injection Point
Filename parameter in image retrieval request

## Payload Used
../../../etc/passwd

## Exploitation Steps
1. Observed filename parameter loading images
2. Replaced image filename with traversal payload
3. Navigated outside application directory
4. Retrieved contents of /etc/passwd file

## Impact
Attackers can access sensitive server files including configuration files and user account data.

## Mitigation
Validate user input and restrict file access to intended directories only.

## Key Learning Outcome
Learned how directory traversal sequences allow access to files outside the application directory.
