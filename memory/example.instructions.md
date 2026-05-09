# Session Memory

## Session Context
This session focused on designing a suite of agent skills and refining the project’s behavioral architecture.  
The user emphasized depth, concision, and predictable reasoning patterns.

---

## Decisions Made This Session

### Skill Creation
- Created new skills:
  - test-driven-development  
  - depth-over-breadth  
  - concision-over-verbosity  
  - mental-audit  
- All skills follow a consistent structure: purpose, principles, rules, workflow, error handling, non-goals.
- Skills must remain lightweight, model-agnostic, and Markdown-based.

### Design Philosophy
- Agents should prioritize **depth over breadth** when constructing systems.  
- Agents should default to **concision over verbosity** unless the user explicitly requests expansion.  
- Agents should use **mental-audit** to interrogate plans one question at a time with recommended answers.

### Memory Requirements
- Memory files should store **session-specific decisions**, not generic summaries.  
- Memory should track:
  - constraints introduced during the session  
  - design choices  
  - naming conventions  
  - skill interactions  
  - unresolved questions  
- Memory should not store transient conversation details or user personal info.

### Interaction Model
- Agents must:
  - ask one question at a time  
  - explore codebase before asking the user  
  - provide recommended answers  
  - maintain a shared mental model  
- Summaries act as navigational interfaces for deeper internal structures.

---

## Constraints Identified
- Skills must avoid external dependencies.  
- Skills must not conflict; if they do, the stricter rule applies.  
- Memory should remain project-focused, not personal.  
- All files should be concise but information-dense.

---

## Unresolved Questions
- Should skills be versioned?  
- Should session summaries be appended or overwritten?  
- Should memory track reasoning chains or only final decisions?

---

## Next Steps (Implied)
- Create a unified meta-skill that coordinates all skills.  
- Build a project-governance skill for versioning and compatibility.  
- Establish a memory-index for cross-session retrieval.

---

## Summary
This session established:
- a consistent skill architecture  
- a depth-first reasoning philosophy  
- a concision-first communication style  
- a structured mental-audit workflow  
- a memory model focused on concrete decisions  

This file captures the actionable outcomes of the session for future agent reference.
