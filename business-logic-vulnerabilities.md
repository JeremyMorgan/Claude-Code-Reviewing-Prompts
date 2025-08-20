## Business Logic Vulnerabilities

Analyze business logic for security flaws:

Critical business operations:
[paste payment, transfer, or sensitive operations code]

Check for:
1. Race conditions
   - Concurrent request handling
   - Double-spending prevention
   - Inventory management

2. Price manipulation
   - Client-side price validation only
   - Discount/coupon abuse
   - Currency manipulation

3. Workflow bypass
   - Skipping validation steps
   - Status manipulation
   - Approval process bypass

4. Time-based vulnerabilities
   - TOCTOU (Time of Check, Time of Use)
   - Expiration bypass
   - Timezone manipulation

5. Integer overflow/underflow
   - Calculation errors
   - Negative value handling

Create a business logic threat model.

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
