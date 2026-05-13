# Copilot Instructions

## Security

- Validate input sanitization practices.
- Search for risks that might expose user data.
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

## Code Quality

- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.

## Purpose
Provide guidance for GitHub Copilot and Copilot Chat when working in this repository.

## Announcement Banner Feature
- Ensure the announcement banner is accessible (e.g., use `role="status"` or `role="alert"` on the banner div).
- Maintain sufficient color contrast for text and background.
- Keep banner text concise and informative.
- Place the banner at the top of the page, above the main header.

## General Guidelines
- Follow semantic HTML and accessibility best practices.
- Use clear, descriptive commit messages.
- Keep CSS changes modular and scoped to the relevant feature.
- Test UI changes in both light and dark modes if supported.
