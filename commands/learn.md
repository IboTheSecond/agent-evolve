---
description: Record verified lessons, corrections and repeat mistakes from completed work.
---

# Learn

Use `AGENT_MEMORY` as the learning-library root and `AGENT_DOCTRINE` as the rules file
read before work. If unset, ask for their locations before writing. Follow repository
rules and the current runtime's file/memory-update constraints.

**IRON RULE:** when current evidence confirms wrong, faulty or outdated skill guidance,
correct its authoritative source immediately before reuse. Verify and date the correction,
preserve historical evidence and refresh affected references. If blocked, mark the guidance
DO NOT USE and report why. Do not wait for this command or the end of a session.

1. Read `RETRO-LOG.md`. Its newest timestamp defines the retrospective window; if absent,
   cover the current session. Use the real clock and state any missing context.
2. Review completed work and its evidence. Collect proven reusable techniques,
   failures with established causes, corrected assumptions and repeated known mistakes.
   A plan or a passing simulation is not deployment or real-user proof.
3. Search existing records before creating one. Update the best existing record when
   it already covers the lesson; add dated evidence of genuine reuse. Never force findings.
4. New techniques go under `skills/generated/` with `name`, a searchable one-line
   `description`, `confidence: 0.5`, `created` and `tags`. Include when to use, exact
   procedure, evidence and pitfalls. Keep each record focused and under 500 lines.
5. Generalizable failures go under `failure-patterns/active/`: symptom, root cause,
   correction and prevention. Increase `strikes` only for an observed recurrence of a
   mistake already covered. Two strikes, or one critical failure, requires `/evolve`.
6. Append a `RETRO-LOG.md` entry with window, records added/updated, corrections,
   strikes, one-off failures and one actionable hardening rule. Apply that rule at
   the narrowest relevant scope when authorized; preserve the append-only history.
7. Rebuild `INDEX.md` from current records: name, relative link, description and
   confidence for techniques; name, relative link and description for failure patterns.
   Validate every link and reject blank metadata or fabricated evidence.
8. Report exact counts, evidence limits and the hardening rule. Honest zeros are valid.

Share only material intended for publication. Curation does not authorize operational
actions, unrelated product changes or changes outside the permitted library.
