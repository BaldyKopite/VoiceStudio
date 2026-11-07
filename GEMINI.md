# Superpowers Project Rules

Always enforce Superpowers as the first and last step of every conversation and task:

## 1. First Step: Skill Invocation & Methodology (`using-superpowers`)
- **Invoke Skills Before Action:** Check and activate the appropriate Superpowers skill before executing tasks, writing code, or making assumptions:
  - **New Features / Architecture:** Use `brainstorming` before entering planning or implementation.
  - **Planning:** Use `writing-plans` once specifications and design are aligned.
  - **Debugging / Issues:** Use `systematic-debugging` to trace and reproduce root causes before modifying files.
  - **Implementation:** Use `test-driven-development` (write failing tests before implementation code).
  - **Complex Tasks:** Use `writing-plans` and `subagent-driven-development`.
  - **Code Review:** Use `requesting-code-review` and `receiving-code-review`.
  - **Branch Integration:** Use `finishing-a-development-branch`.
- **Task Tracking:** For multi-step tasks, create and maintain an explicit task checklist, updating progress systematically.

## 2. Final Step: Verification Before Completion (`verification-before-completion`)
- **The Iron Law:** NO COMPLETION CLAIMS WITHOUT FRESH VERIFICATION EVIDENCE.
- Before claiming work is finished, resolved, or passing:
  1. Determine the exact command or test that proves the change works.
  2. Run the full command fresh and inspect the output and exit status.
  3. Confirm the output verifies the claim with tangible evidence.
  4. Only after providing the evidence, mark the task as complete.
