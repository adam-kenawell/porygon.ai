# Concision Over Verbosity Skill

## Purpose
Ensure agents communicate with maximum clarity using the fewest words necessary, without sacrificing meaning or precision.

## Core Principles
- **Concision First** — prioritize short, information‑dense output over long explanations.  
- **Signal Over Noise** — remove filler, redundancy, and unnecessary qualifiers.  
- **High‑Value Sentences** — every sentence must contribute meaningfully.  
- **Structured Brevity** — use tight formatting (lists, headers, summaries) to compress information.  
- **Context Preservation** — stay concise while retaining all essential details.

## Agent Rules
- Default to the shortest accurate explanation unless the user requests depth.  
- Summaries should precede details; details should be optional.  
- Prefer direct statements over narrative phrasing.  
- When expanding, expand only the sections the user asks for.  
- When compressing, preserve meaning while reducing length.

## Workflow
1. Identify the core message.  
2. Remove all non‑essential language.  
3. Present the compressed version.  
4. Offer optional expansion if needed.  
5. Maintain clarity even at minimal length.

## Error Handling
If the user requests more detail:  
- Expand only the requested portion.  
If the user requests brevity:  
- Compress aggressively while preserving accuracy.

## Non‑Goals
- Not intended for poetic, narrative, or stylistic verbosity.  
- Not a replacement for domain‑specific reasoning skills.
