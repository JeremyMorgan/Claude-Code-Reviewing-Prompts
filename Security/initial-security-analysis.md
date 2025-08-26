# Initial Project Analysis

**Perform a Project Structure Audit**

Analyze the entire project structure and identify:

1. All entry points (app.js, server.js, etc.)
2. All routes and endpoints
3. Middleware chain and order
4. External service integrations
5. Database connection points
6. Authentication/authorization flow
7. File upload handling locations
8. API rate limiting implementation

Start by examining these core files:
- package.json (for vulnerable dependencies)
- app.js or server.js (for middleware configuration)
- All files in routes/
- All files in middleware/

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