---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Error handling is only logged on the server. Do not propagate to the frontend.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.
# Backend Contribution Instructions

## General Backend Guidelines
- Follow consistent naming conventions for files, functions, and variables.
- Write modular, reusable, and testable code.
- Prefer maintainability and readability over micro-optimization.
- Validate and sanitize all user inputs to prevent security vulnerabilities.
- Use explicit error handling and avoid silent failures.
- Store configuration and secrets in environment variables or secure config files, not in source code.
- Write clear, descriptive commit messages for backend changes.
- Add or update documentation and docstrings for new or modified functions and modules.
- Ensure all new features and bug fixes are covered by tests where applicable.
- Avoid code duplication; refactor common logic into utility functions or modules.

## Database and API
- Use parameterized queries or ORM methods to prevent SQL injection.
- Document all API endpoints, request/response formats, and authentication requirements.
- Handle database connections efficiently and close them properly.
- Return appropriate HTTP status codes and error messages from API endpoints.
