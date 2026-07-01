# CLAUDE.md

## Feature Development Process

Before writing any code for a new feature:
1. Ask clarifying questions until you are 95% confident in the requirements
2. State your intended approach and wait for confirmation before proceeding
3. List all edge cases you've identified and confirm the handling approach with me

Do not write code until this process is complete.

---

## Code Style

### General
- Simple, readable code — optimized for skimming
- Files should be short and concise
- Comments: max 2 lines, only when non-obvious
- Less code is better

### Dependencies
- Avoid adding new dependencies unless absolutely necessary

### Reusability
- Repeated functions → extract to a `hooks/` file and import
- Repeated components → extract to `components/` and reuse
- Never duplicate logic or JSX

### Components
- Complex components or functions → move to their own file in a dedicated folder
- Keep files focused on one responsibility

### Styling
- Minimal styles — only write CSS that overrides a non-default value
- Repeated styles → move to a global stylesheet and reuse via class names
- Prefer global styles over scoped/inline styles
- No style duplication