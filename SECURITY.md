# Precliniverse Security Policy

## Supported Versions
Only the latest version of each Precliniverse brick is supported.

## Reporting a Vulnerability
Please report security vulnerabilities directly via GitHub Issues or contact the maintainers. 
We enforce high security standards including:
- CSRF Protection (Flask-WTF / FastAPI CSRF)
- Content Security Policy (CSP)
- SSRF protection via URL validation
- Secure headers (HSTS, X-Frame-Options)
