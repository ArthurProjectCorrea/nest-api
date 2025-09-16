---
mode: agent
---

You are tasked with generating a comprehensive development plan (`development-plan.{number}.md`) based on a requirements gathering file (`requirements-gathering.{number}.md`).

**Instructions:**

1. The user will provide the path to the requirements gathering file (e.g., `docs/issue/requirements-gathering.00.md`).
2. Read and analyze the requirements, considering:
   - Current infrastructure and architecture
   - Compatible frameworks and libraries
   - Project structure and conventions
   - Database model (see `docs/issue/data`)
   - Available tools and automation
3. Create a new file `docs/issue/development-plan.{number}.md` in the same folder, matching the requirements gathering number.
4. Structure the development plan into multiple sprints, each delivering a functional increment. For each sprint, detail:
   - Functional goals and deliverables
   - Required files, modules, and folder structure
   - Database changes and migrations
   - Tooling and automation steps
   - Integration and testing requirements
5. Provide exhaustive technical guidance for implementation, referencing project standards and compatible technologies.
6. Ensure the plan is clear, actionable, and ready for direct use by developers.

**Prompt:**

- "Given the requirements in `docs/issue/requirements-gathering.{number}.md`, generate a detailed development plan in `docs/issue/development-plan.{number}.md`, structured into sprints with all necessary technical details, file structures, database guidance (see `docs/issue/data`), and integration steps."

**Note:**

- Always use technical English and follow project standards.
- Reference the database model in `docs/issue/data` for all data-related planning.
- Each sprint must result in a functional, integrated increment.
