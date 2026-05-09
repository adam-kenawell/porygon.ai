# Test Driven Development (TDD)

## Core Principles
- **Write Tests First** — behavior must be defined before code exists.  
- **Red‑Green‑Refactor** — fail → pass → clean.  
- **Minimal Implementation** — only enough code to satisfy the test.  
- **Behavior Focus** — describe *what* the system should do.  
- **Fast Feedback** — tests must be small and quick.

## Workflow
1. Understand requirement → restate as testable behavior.  
2. Write failing test.  
3. Explain expected failure.  
4. Implement minimal code.  
5. Re-run tests (simulated).  
6. Refactor safely.  
7. Add next test.

## Error Handling
If asked for code without tests:  
- Remind user TDD requires tests first.  
- Generate tests unless user opts out.

## Non‑Goals
- No enforced language/framework.  
- Not a full application generator.  
