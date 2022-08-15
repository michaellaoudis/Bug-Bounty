# Bounty Report Template - appName
## Scope
- White-listed vulnerabilities, targets..
### Identified Domain(s)
- https://example.com
    - https://example.com/profile
## App Functionality
- Interesting features -> Flow, APIs..           


# **Impact**

## Issue Description
- A generic overview of the issue.

## Affected URL/Area
- The affected urls or area of the application where the issue exists.

## Risk Rating
- [CVSS v3.1 Calculator](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator)

## Impact
- What kind of attacker?
- Authentication used? Y/N
- Who else does it affect?

# **Proof of Concept**
Outline the steps required to execute the payload as an attacker.
- Request/Response
- Screenshots
### Sample SQLi Queries
| Injection | HTTP Response                    |
| ------------- | ------------------------------ |
| `UNION SELECT ORDER BY 3--`      | 200 **OK**       |
| `OR 7=7--`   | 200 **OK**     |
# **Remediation**

## Recommended Fix
- Remediation actions required to successfully fix issue

## References
Include additional reading for the client to further backup the issues explained or elaborate more on other potential issues chained to the one identified.
- [1] [Reference 1]()
- [2] [Reference 2]()
