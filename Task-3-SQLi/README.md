# Task 3: SQL Injection on DVWA (Low Security)

## Objective
To demonstrate an SQL Injection vulnerability using Damn Vulnerable Web Application (DVWA).

## Tool Used
- DVWA (Damn Vulnerable Web Application)

## Environment
- OS: Kali Linux
- Web Server: Apache
- Database: MySQL / MariaDB

## Attack Description
SQL Injection occurs when user input is directly included in an SQL query without validation.

## Payload Used
1' OR '1'='1

## Result
- Authentication logic bypassed
- All user records retrieved

## Security Impact
- Unauthorized data access
- Potential database compromise

## Mitigation
- Input validation
- Prepared statements
- Parameterized queries
## Demo video
https://drive.google.com/file/d/1fIWloFkggczIHs7Nwtqa3zmuDOcSwti4/view?usp=drive_link

## Conclusion
This task demonstrates how improper input handling can lead to critical security vulnerabilities.
