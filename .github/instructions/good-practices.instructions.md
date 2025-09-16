---
applyTo: '**'
---

General coding and documentation practices:

1. **Language Standardization**
   - Always write **in technical English** by default: variable names, function names, comments, documentation, commit messages, and user-facing text.
   - Only use another language if explicitly requested.
   - Ensure consistent terminology across the entire project.

2. **Code Quality & Readability**
   - Follow clean code principles: SOLID, DRY (Don’t Repeat Yourself), KISS (Keep It Simple, Stupid), and separation of concerns.
   - Use meaningful, descriptive, and consistent names for variables, functions, classes, and files.
   - Keep functions and modules small, cohesive, and focused on a single responsibility.
   - Prefer explicitness over clever tricks; clarity is more important than brevity.

3. **Documentation**
   - Document every feature, module, and architectural decision.
   - Keep project documentation up-to-date (`README.md`, architecture files, usage guides).
   - Write comments only when the intent of code is not obvious, focusing on **why** rather than **what**.
   - Provide examples where necessary to reduce ambiguity.

4. **Error Prevention & Robustness**
   - Always validate inputs and handle edge cases.
   - Use defensive programming techniques where appropriate to avoid unexpected crashes.
   - Write code with scalability and maintainability in mind, not just quick fixes.
   - Avoid magic numbers and hard-coded values; use constants or configuration files.

5. **Testing & Verification**
   - Ensure all critical logic has automated tests (unit, integration, or end-to-end depending on the layer).
   - Write tests in English, with descriptive test case names.
   - Adopt a test-first or test-aware mindset to mitigate regressions.
   - Run tests consistently before merging changes.

6. **Version Control & Collaboration**
   - Commit often, with clear and descriptive commit messages in English.
   - Follow a consistent branching strategy (e.g., Gitflow, trunk-based).
   - Keep commits small, isolated, and logically grouped.
   - Review and refactor code regularly to maintain quality.

7. **Security & Reliability**
   - Never commit secrets, credentials, or sensitive data.
   - Follow security best practices for the stack in use.
   - Validate all external inputs (APIs, user input, files).
   - Keep dependencies up-to-date and review them for vulnerabilities.

8. **Performance & Scalability**
   - Avoid premature optimization; focus on correctness and clarity first.
   - When performance is necessary, measure and profile before optimizing.
   - Design with scalability in mind to support growth and future changes.

9. **Consistency & Standardization**
   - Use linters, formatters, and automated tools to enforce style consistency.
   - Centralize configuration and environment management (e.g., `.env`, config files).
   - Apply the same conventions across the entire codebase to reduce cognitive overhead.

10. **Continuous Improvement**
    - Always question whether the current solution is the most maintainable and clear.
    - Refactor when necessary, but avoid unnecessary changes.
    - Learn from mistakes and update practices accordingly.
    - Document lessons learned in the project’s knowledge base for future reference.
