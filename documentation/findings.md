# Findings

## Scope
Controlled testing of DVWA, an intentionally vulnerable training application.

## Findings
- Input handling at DVWA Low Security was insufficient.
- Documented SQL Injection inputs were processed by the application.
- UNION-based testing allowed database metadata enumeration.
- Tables and columns could be identified.
- Usernames and password hashes were exposed in the lab.

## Impact
The exercise demonstrates how SQL Injection can lead to database-information and sensitive-data exposure when applications do not use secure query handling.

## Limitation
These observations apply to the documented DVWA laboratory configuration and should not be generalized to production systems.
