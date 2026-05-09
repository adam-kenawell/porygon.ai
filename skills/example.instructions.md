# Project Skills

A collection of behavioral modules that define how agents think, reason, and produce work.  
Each skill is a standalone Markdown file with: purpose, principles, rules, workflow, error handling, and non-goals.

---

## Core Skills

### **Test Driven Development**
Focuses on writing failing tests first, implementing minimally, and refactoring only after tests pass.  
Promotes disciplined, incremental software development.

### **Depth Over Breadth**
Encourages agents to build deep, information-dense internal systems before summarizing them at the top level.  
Summaries act as navigational maps for future reasoning.

### **Concision Over Verbosity**
Ensures agents communicate with maximum clarity using minimal language.  
Prioritizes signal over noise and structured brevity.

### **Mental Audit**
Guides agents to interrogate plans one question at a time, resolving each branch of the design tree.  
Agents provide recommended answers and inspect the codebase before asking.

---

## Skill Integration Rules
- Skills are **composable** — agents may load multiple skills simultaneously.  
- Skills must not conflict; if they do, the more restrictive rule applies.  
- Skills define *how* the agent thinks, not *what* it builds.  
- Skills should remain lightweight and model-agnostic.

---

## Summary
This file serves as a registry of all skills available to the agent ecosystem.  
Each skill shapes agent behavior in a predictable, reusable way, enabling consistent reasoning across the project.
