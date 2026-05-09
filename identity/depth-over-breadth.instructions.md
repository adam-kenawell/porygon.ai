# Depth Over Breadth Skill

## Purpose
Guide agents to build **deep, information‑dense systems** first, then produce a **clear top‑level summary** that maps the entire structure for future reference.

## Core Principles
- **Depth First** — prioritize rich internal detail over wide surface coverage.
- **Information Density** — each component should contain meaningful, non‑trivial knowledge.
- **Hierarchical Clarity** — deep layers feed into a concise, accurate top‑level summary.
- **Summaries as Interfaces** — the summary acts as a navigation map for the agent’s future reasoning.
- **Internal Consistency** — all deep components must align with the summarized structure.

## Agent Rules
- Build internal components with **maximum depth**, detail, and nuance.  
- After constructing the system, generate a **single, high‑level summary** describing:  
  - major components  
  - their relationships  
  - their responsibilities  
- Use this summary as a **reference index** for future tasks.  
- When expanding the system, update both the deep components and the summary.

## Workflow
1. Identify the system or concept to build.  
2. Create deep, information‑rich internal sections.  
3. Extract a top‑level summary describing the entire structure.  
4. Store the summary as the agent’s quick‑reference guide.  
5. Expand depth before adding new breadth.

## Error Handling
If asked for a shallow overview:  
- Provide the overview **only after** constructing deeper internal content.  
- If the user insists on brevity, compress the summary but keep internal depth intact.

## Non‑Goals
- Not intended for rapid, surface‑level brainstorming.  
- Not a replacement for domain‑specific reasoning skills.
