---
applyTo: 'docs/issue/development-plan.*.md'
---

# Development Plan Instructions

## Purpose

This instructor guides the process of generating a detailed development plan (`development-plan.{number}.md`) based on a requirements gathering file (`requirements-gathering.{number}.md`). The plan must be tailored to the current project infrastructure, compatible frameworks, and available tools, and must be structured for incremental delivery through multiple sprints.

## Workflow

1. **Input**: The user will specify the path to a requirements gathering file (e.g., `docs/issue/requirements-gathering.00.md`).
2. **Analysis**: Read and analyze the requirements gathering file, considering:
   - Existing infrastructure and architecture
   - Compatible frameworks and libraries
   - Project structure and conventions
   - Database model (reference `docs/issue/data` for schema guidance)
   - Available tools and automation (CI/CD, linting, testing, etc.)
3. **Development Plan Generation**:
   - Create a new file `docs/issue/development-plan.{number}.md` (matching the requirements gathering number)
   - Structure the plan into multiple sprints, each delivering functional increments
   - For each sprint, specify:
     - Functional goals and deliverables
     - Required files, modules, and folder structure
     - Database changes and migrations
     - Tooling and automation steps
     - Integration and testing requirements
   - Provide detailed technical guidance for implementation, referencing project standards and compatible technologies
   - Ensure the plan is exhaustive, covering all aspects: code, documentation, configuration, database, and deployment
4. **Output**: The generated development plan must be ready for direct use by developers, with clear, actionable steps and technical rigor.

## Best Practices

- Use technical English and consistent terminology
- Align with project coding, documentation, and workflow standards
- Reference the database model in `docs/issue/data` for all data-related planning
- Ensure each sprint results in a functional, integrated increment
- Document all decisions, file structures, and tool usage
- Maintain clarity, completeness, and maintainability throughout the plan

## Continuous Improvement

- Refine the development plan process based on feedback and evolving project needs
- Update instructions to reflect new tools, frameworks, or architectural changes
