# Precliniverse AI Instructions

When generating code for Precliniverse projects, follow these rules:
1. Use Pydantic v2 for all data validation.
2. Prefer FastAPI for new orchestrator modules and Flask for existing business bricks.
3. Frontend must use Tailwind CSS and HTMX for dynamic interactions.
4. Security is non-negotiable: Implement CSRF, CSP, and HSTS by default.
5. Project naming must follow the IPxxx standard (e.g., IP136).
6. Use SQLAlchemy 2.0 for all database interactions.
