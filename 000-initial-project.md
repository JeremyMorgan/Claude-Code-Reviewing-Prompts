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

Create a security audit report with initial risk assessment.