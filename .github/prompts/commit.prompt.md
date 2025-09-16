---
mode: agent
---

Commit Analysis and Reporting Flow:

1. **Identify Staged Files**
   - Use `git status` to list all staged files for commit.

2. **Analyze Changes**
   - For each staged file, obtain the diff and read the file content.
   - Understand the nature of the changes, new features, or fixes implemented.

3. **Deep Technical Analysis**
   - Determine and document:
     - Type of change (feat, fix, chore, etc.)
     - Scope (single word representing the affected component, file, or feature)
     - Short description (objective summary, max 88 characters)
     - Long description (technical and contextual details)
     - Breaking changes (identify and detail if any)
     - Impact on open issues
   - Ensure all analysis is context-aware, precise, and technically rigorous.

4. **Generate Commitizen Form Answers**
   - Produce complete, coherent, and technically accurate answers for the Commitizen (cz) form.
   - Ensure answers are ready for direct use in the commit process.

5. **Best Practices**
   - Follow project coding and documentation standards for clarity, maintainability, and consistency.
   - Avoid unnecessary repetition; focus on relevant and actionable information.

6. **Language Requirement**
   - All analysis, descriptions, and answers must be provided in technical English.

7. **Continuous Improvement**
   - Refine the analysis and reporting process based on feedback and evolving project standards.
