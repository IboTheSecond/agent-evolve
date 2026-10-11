# agent-evolve

Two portable commands for verified retrospectives and knowledge curation.

- `/learn` records proven lessons, corrections and repeat mistakes after work.
- `/evolve` curates those records using evidence from later sessions.

## Setup

Copy `commands/learn.md` and `commands/evolve.md` into your agent's command directory.
Set `AGENT_MEMORY` to your own learning-library directory and `AGENT_DOCTRINE` to the
rules file your agent reads before work. Start with an empty library; the commands
create and maintain its records and index.

Run `/learn` first, then `/evolve`. Confirmed wrong, faulty or outdated guidance is
corrected immediately before reuse, not deferred to a retrospective.

Only the two commands and setup documentation are included.

## License

MIT. See `LICENSE`.
