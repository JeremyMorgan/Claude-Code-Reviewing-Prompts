Evaluate our code for readability and naming.

Review:

1. NAMING CONVENTIONS
   - Variables: descriptive vs cryptic (e.g., 'u' vs 'user')
   - Functions: verb-based, clear intent
   - Classes: noun-based, single responsibility
   - Constants: UPPER_CASE consistency
   - Private methods: underscore convention

2. NAMING CONSISTENCY
   - camelCase vs snake_case mixing
   - Abbreviation consistency
   - Domain terminology usage
   - British vs American spelling

3. CODE READABILITY
   - Self-documenting code
   - Need for comments (too many = code smell)
   - Magic numbers/strings
   - Complex boolean expressions
   - Ternary operator abuse

4. FUNCTION SIGNATURES
   - Parameter count (>3 is a smell)
   - Boolean parameters (avoid)
   - Optional parameter handling
   - Return type clarity

Create a naming convention guide based on findings.

## Provide:

A structured finding report

A scale of 1/10 on how important each finding is

Remediation: precise code-level fix or config change (snippets welcome) if possible

## Constraints & style:

Be concrete and cite exact code locations and identifiers.

Prefer minimal, drop-in fix snippets over prose.

Do not invent files or functions that aren’t present; if context is missing, mark as Unable to verify and say what code would prove it.

Write this into a markdown file and place it in the audits/ folder.