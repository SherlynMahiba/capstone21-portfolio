# CAPSTONE 21 — GitHub Portfolio and Open-Source Contribution Guide

## Project question
How can AI help students create a professional GitHub presence and make their first open-source contribution?

## 1. Target audience
Second- and third-year Computer Science and Engineering (CSE) students who know basic programming but may be new to Git, GitHub collaboration, and open-source contributions.

## 2. Objectives
- Explain how to create a clear GitHub profile and portfolio.
- Identify the parts of a useful README.
- Demonstrate a safe beginner workflow for contributing to an open-source project.
- Use AI tools to draft and review documentation while verifying every important claim.
- Encourage respectful, small, well-scoped contributions.

## 3. Research summary
### README best practices
A useful README should tell visitors what the project does, why it is useful, how to install or run it, how to use it, how to test it, and how to contribute. Include prerequisites, examples, screenshots where useful, licence information, and links to relevant documentation. Keep instructions current and test commands before publishing.

### Git and GitHub workflow
A common contribution workflow is:
1. Read the repository README, CONTRIBUTING file, Code of Conduct, and licence.
2. Check open issues and discussions; ask before starting large changes.
3. Fork the repository (if the project uses forks) or create a branch if you have access.
4. Clone your fork and create a clearly named branch.
5. Make one focused change.
6. Run relevant tests and inspect the diff.
7. Commit with a clear message.
8. Push the branch and open a pull request using the project's template.
9. Respond politely to review feedback and update the branch.
10. Follow the maintainer's decision and close or revise the PR as requested.

### Beginner-friendly first contributions
Good first contributions include fixing a typo, improving unclear documentation, adding a missing usage example, correcting a broken link, or adding a small test. Confirm that the issue is still open and that the maintainers welcome the proposed change.

### How AI can help
AI can explain Git commands, suggest README sections, simplify documentation, identify unclear wording, propose test cases, and help interpret error messages. AI output may be inaccurate, outdated, insecure, or inconsistent with project conventions. The contributor remains responsible for checking source files, running commands, testing changes, and following maintainer instructions.

## 4. AI tools used / proposed
- ChatGPT: planning, explanations, draft documentation, checklists, quiz questions.
- Gemini: second opinion and comparison of README or workflow suggestions.
- NotebookLM: organize and question source documents supplied by the student.
- Gamma: turn the verified outline into presentation slides.
Only use free features available to you; feature limits may change.

## 5. Repository quality checklist
- [ ] Repository name is meaningful.
- [ ] Description explains the project's purpose.
- [ ] README has overview, features, setup, usage, tests, contribution, and licence sections as applicable.
- [ ] Setup commands were tested on a clean environment.
- [ ] Example output matches actual behaviour.
- [ ] Links work.
- [ ] File and folder names are consistent.
- [ ] Secrets, tokens, passwords, and personal data are not committed.
- [ ] Dependencies and versions are documented.
- [ ] Licence is present and appropriate; do not add a licence without checking ownership and project policy.
- [ ] CONTRIBUTING and Code of Conduct are followed where present.
- [ ] Issues and pull requests are respectful and specific.

## 6. Three-repository improvement plan
The assignment requires improving three repositories. Select repositories you own or are permitted to edit. For each one, record its URL, baseline condition, changes, and verification evidence.

| Repository | Baseline to inspect | Possible improvement | Evidence to save |
|---|---|---|---|
| Repository 1 | README, setup, usage, links | Clarify overview and setup steps | Before/after README, tested commands |
| Repository 2 | Folder structure, examples, tests | Add usage example and test instructions | Screenshot, test output |
| Repository 3 | Contribution instructions, licence | Add contribution guidance or fix broken docs | Diff, link check |

Do not claim that a repository was changed unless you actually made and verified the change. Do not modify repositories without permission.

## 7. First-contribution guide
1. Choose a project that matches your interests and skill level.
2. Read README, CONTRIBUTING, Code of Conduct, and licence.
3. Search issues for labels such as `good first issue` or `documentation`.
4. Read the issue and comments. Ask whether the task is available if unclear.
5. Fork the repository if required.
6. Clone your fork: `git clone <your-fork-url>`
7. Enter the folder: `cd <repository-folder>`
8. Create a branch: `git switch -c docs/fix-readme-typo`
9. Make a small, focused change.
10. Review it: `git diff`
11. Run the project's documented tests or checks.
12. Commit: `git add .` then `git commit -m "docs: clarify setup instructions"`
13. Push: `git push -u origin docs/fix-readme-typo`
14. Open a pull request and explain what changed, why, and how you tested it.
15. Respond respectfully to review comments. Never use AI to submit changes you do not understand.

## 8. GitHub Pages portfolio
A starter website is included in `portfolio/index.html`. Replace all bracketed placeholders with your own accurate details. Publish only information you are comfortable making public. To publish: create a repository named `<your-username>.github.io`, add `index.html` at the root, commit and push, then enable GitHub Pages in repository Settings if needed. Confirm the live site works.

## 9. GitHub Actions automation
A sample workflow is included in `.github/workflows/readme-check.yml`. It runs when a pull request or push changes README files and checks that a README exists and contains basic sections. Adjust it to match the repository's conventions. Test it in a repository you own or have permission to use.

## 10. Ten-question quiz
1. What is the main purpose of a README?  
   **Answer:** To explain the project's purpose, setup, usage, and other important information.
2. What does `git clone` do?  
   **Answer:** Copies a remote repository to your local computer.
3. Why create a branch?  
   **Answer:** To isolate a change from the main development line.
4. What is a fork?  
   **Answer:** A personal copy of another GitHub repository under your account.
5. What should you read before contributing?  
   **Answer:** README, CONTRIBUTING instructions, Code of Conduct, licence, and relevant issue discussion.
6. What is a pull request?  
   **Answer:** A proposal to merge changes from one branch or fork into another branch.
7. Why run tests before opening a pull request?  
   **Answer:** To check that the change works and has not caused known regressions.
8. Should AI-generated code or text be accepted without checking?  
   **Answer:** No. Verify it, understand it, and follow the project's policies.
9. What is a software licence?  
   **Answer:** A legal document describing permissions and conditions for using, modifying, and distributing software.
10. What is a good first contribution?  
    **Answer:** A small, clearly scoped task such as fixing documentation or a typo, after confirming maintainers welcome it.

## 11. Responsible AI, ethics, and licences
- Treat AI suggestions as drafts, not authority.
- Verify technical claims against project documentation and actual behaviour.
- Do not paste passwords, API keys, private code, or personal data into AI tools.
- Respect copyright and the repository's licence. A public repository is not automatically free of licence conditions.
- Follow the Code of Conduct and contribution instructions.
- Be transparent when project policy requires disclosure of AI assistance.
- Do not flood maintainers with low-quality or unrequested AI-generated pull requests.
- Never claim tests passed unless they were run and passed.

## 12. Verification report
For every AI-generated suggestion, record: prompt, tool, output summary, source used to verify it, test performed, result, and decision (accepted/edited/rejected). Verify Git commands against Git documentation and project-specific instructions. Check all links and run the documented setup/tests. Replace this paragraph with actual test evidence before submission.

## 13. Before/after analysis
Use this table only after inspecting real repositories.

| Measure | Before | After | Evidence |
|---|---|---|---|
| README completeness | [record actual baseline] | [record actual result] | README diff |
| Setup instructions | [record actual baseline] | [record actual result] | Tested setup |
| Usage examples | [record actual baseline] | [record actual result] | Example run |
| Contribution guidance | [record actual baseline] | [record actual result] | CONTRIBUTING file |
| Link correctness | [record actual baseline] | [record actual result] | Link check |

## 14. Prompt library
1. "Review this README for clarity and missing sections. Do not invent project features. List questions where information is missing."
2. "Rewrite these setup instructions for a beginner. Preserve every command exactly unless you explain a proposed change."
3. "Explain this Git error in simple language and suggest safe diagnostic steps. Do not assume my branch or remote names."
4. "Create a repository quality checklist based only on the supplied README and CONTRIBUTING file."
5. "Suggest five beginner-friendly documentation improvements. Explain how I can verify each one."
6. "Review this pull request description for clarity, respectful tone, and a clear testing summary."
7. "Generate quiz questions from the supplied project guide and include an answer key."
8. "Check this workflow file for likely syntax or logic issues. Distinguish confirmed errors from suggestions."
9. "Identify claims in this draft that need verification and suggest authoritative documentation to consult."
10. "Compare this before/after README and report only changes visible in the supplied text."

## 15. Final demo script
1. Introduce the problem and target audience.
2. Show the repository quality checklist.
3. Demonstrate one real README improvement with before/after evidence.
4. Explain the first-contribution workflow.
5. Show the portfolio website.
6. Show the GitHub Actions run and its result.
7. Explain how AI suggestions were verified and what was rejected.
8. Conclude with lessons learned and limitations.

## 16. Conclusion
AI can lower the learning barrier for GitHub and open-source contribution by helping students understand workflows and improve documentation. It cannot replace permission, technical understanding, testing, source verification, or respectful collaboration. A successful first contribution is small, useful, verified, and aligned with maintainer guidance.
