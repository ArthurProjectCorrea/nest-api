---
applyTo: '**'
---

Commit Analysis and Reporting Guidelines:

1. **Language Standardization**
   - All analysis, reports, and form answers must be written in technical English.
   - Use consistent terminology for change types, scopes, and descriptions.

2. **Staged File Identification**
   - Identify all staged files using `git status`.
   - For each staged file, obtain the diff and read the file content to understand the changes or new features implemented.

3. **Deep Change Analysis**
    - Analyze modifications to determine:
       - Type of change (feat, fix, chore, etc.)
       - Scope (affected component, file, or feature; must be a single word)
       - Short description (objective summary, **max 80 characters, no line breaks**)
       - Long description (technical and contextual details, **must be a single paragraph, no line breaks**)
       - Breaking changes (identify and detail if any)
       - Impact on open issues
    - Ensure the analysis is accurate, clear, and contextually deep.

4. **Commitizen Form Completion**
   - Generate complete and coherent answers for the Commitizen (cz) form, aligned with the staged changes.
   - Answers must be ready for direct use in the commit process.

5. **Best Practices**
   - Follow clean code and documentation principles as outlined in the general project guidelines.
   - Prioritize maintainability, clarity, and technical rigor in all commit analyses.
   - Avoid unnecessary repetition; focus on what is relevant for the commit context.

6. **Continuous Improvement**
   - Refine analysis and reporting methods based on feedback and evolving project standards.
   - Document lessons learned and update practices to improve future commit analysis.
