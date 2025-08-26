## Comprehensive Security Report

Based on our complete security audit, generate a comprehensive security report:

## Executive Summary
- Overall security posture (Critical/High/Medium/Low)
- Number of vulnerabilities by severity
- Immediate actions required

## Critical Vulnerabilities (Fix Immediately)
[List with CVE references if applicable]

## High Priority Issues (Fix within 1 week)
[Detailed list with code locations]

## Medium Priority Issues (Fix within 1 month)
[List with recommendations]

## Low Priority Issues (Fix in next release)
[List of improvements]

## Security Recommendations
1. Implementation priorities
2. Security tools to adopt
3. Process improvements
4. Training needs

## Compliance Checklist
- OWASP Top 10 coverage
- PCI DSS (if handling payments)
- GDPR (if handling EU data)
- SOC 2 requirements

## Code Examples
Provide secure code examples for each vulnerability type found.

## Testing Guide
Include curl commands or test scripts to verify each fix.


---

## Provide:

A structured finding report with the following for each issue:

Title, Severity (Critical/High/Medium/Low), CWE (if applicable), Evidence (file, function, line ranges), and a short Why it matters.

Exploitability notes and, where safe, a minimal PoC or reproduction steps (no real secrets).

Remediation: precise code-level fix or config change (snippets welcome), plus defense-in-depth guidance.

A summary risk score (0–10) and top 3–5 prioritized fixes that reduce risk fastest.

A checklist diff: which items from the “Check for” list are Pass/Fail/Not Applicable.

## Constraints & style:

Be concrete and cite exact code locations and identifiers.

Prefer minimal, drop-in fix snippets over prose.

Do not invent files or functions that aren’t present; if context is missing, mark as Unable to verify and say what code would prove it.

Write this into a markdown file and place it in the audits/ folder.