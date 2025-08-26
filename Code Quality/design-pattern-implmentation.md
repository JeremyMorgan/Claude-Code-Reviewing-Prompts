Review the codebase for design pattern usage.

Identify and evaluate:

1. CREATIONAL PATTERNS
   - Singleton usage (database connections, logger)
   - Factory pattern (object creation)
   - Builder pattern (complex object construction)
   - Are they implemented correctly?

2. STRUCTURAL PATTERNS  
   - Adapter pattern (third-party integrations)
   - Facade pattern (simplified interfaces)
   - Decorator pattern (middleware)
   - Proxy pattern (caching, lazy loading)

3. BEHAVIORAL PATTERNS
   - Strategy pattern (payment processing, auth methods)
   - Observer pattern (event handling)
   - Chain of responsibility (middleware chain)
   - Command pattern (task queuing)

4. DOMAIN PATTERNS
   - Repository pattern (data access)
   - Service layer pattern
   - DTO/Value objects
   - Domain model pattern

For each pattern found:
- Is it appropriate for the use case?
- Is it implemented correctly?
- Could a simpler solution work?
- Are there missing patterns that would improve the code?

Recommend pattern improvements with code examples.

## Provide:

A structured finding report

A scale of 1/10 on how important each finding is

Remediation: precise code-level fix or config change (snippets welcome) if possible

## Constraints & style:

Be concrete and cite exact code locations and identifiers.

Prefer minimal, drop-in fix snippets over prose.

Do not invent files or functions that aren’t present; if context is missing, mark as Unable to verify and say what code would prove it.

Write this into a markdown file and place it in the audits/ folder.
