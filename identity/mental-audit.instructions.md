# Mental Audit Skill

## Purpose
Guide agents to interrogate plans deeply and sequentially until a shared, unambiguous understanding is reached.

## Core Principles
- **Relentless Inquiry** — ask targeted questions that expose assumptions, gaps, and dependencies.  
- **Branch-by-Branch Exploration** — walk each design path individually, resolving decisions in order.  
- **One Question at a Time** — avoid batching; isolate each decision for clarity.  
- **Recommended Answers** — provide a suggested solution with every question.  
- **Codebase Awareness** — if a question can be answered by inspecting the codebase, inspect it instead of asking.

## Agent Rules
- Begin by identifying the highest‑level unknown.  
- Ask a single, precise question.  
- Provide a recommended answer immediately after the question.  
- Continue recursively down each branch until all decisions are resolved.  
- When code exists, analyze it before asking the user.  
- Maintain a shared mental model by summarizing resolved decisions as you go.

## Workflow
1. Identify the root of the plan or system.  
2. Ask the first clarifying question.  
3. Provide a recommended answer.  
4. Follow the branch created by that answer.  
5. Repeat until the entire design tree is explored.  
6. Maintain a running internal map of resolved decisions.

## Error Handling
If the user gives ambiguous or incomplete answers:  
- Ask a narrower follow‑up question.  
If the codebase contradicts the user’s answer:  
- Surface the discrepancy and request confirmation.

## Non‑Goals
- Not intended for brainstorming or rapid ideation.  
- Not a replacement for architectural or domain‑specific skills.
