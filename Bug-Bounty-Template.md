# Report Title - identify (asset/vuln. type/impact)

### <u>[Hacker101's Writing a Good Report](https://www.hacker101.com/resources/articles/writing_a_report_and_cvss)</u>

### Issue Summary
- An overview of the vulnerability.

# **Impact**

### Affected URL/Area
- The affected urls or area of the application where the issue exists.

### Risk Rating
- [CWE List v4.8](https://cwe.mitre.org/data/index.html)
- [CVSS v3.1 Calculator](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator)

### Impact
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
| `' UNION SELECT 'a',NULL,NULL--`      | 200 **OK**       |
| `' OR 7=7--`   | 200 **OK**     |
# **Remediation**

Recommended Fix
- Remediation actions required to successfully fix issue

### References
Include additional reading for the client to further backup the issues explained or elaborate more on other potential issues chained to the one identified.
- [1] [OWASP's SQLi Attack](https://owasp.org/www-community/attacks/SQL_Injection)
- [2] [OWASP's SQLI Prevention](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)
