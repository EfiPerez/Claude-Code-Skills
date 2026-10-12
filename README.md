# claude-code-skills

Practical Claude Code skills for real workflows, by Efi Perez ([@EfiPerez](https://github.com/EfiPerez)).

## Install

**Option A - plugin marketplace (recommended):**
```
/plugin marketplace add EfiPerez/claude-code-skills
/plugin install done@efi-skills
```
One-time marketplace registration; every skill added later needs no new
setup on your side. Third-party marketplace auto-update is **off by
default** - run `/plugin marketplace update` to pull new versions, or turn
on auto-update for this marketplace.

<details>
<summary>Option B - manual copy (no plugin system)</summary>

There is no `claude skill install` command. Download this repo, then copy
the folder for the skill you want into `~/.claude/skills/`:

```
cp -r claude-code-skills/skills/done ~/.claude/skills/
```
</details>

## Skills in this repo

| Skill | What it does |
|---|---|
| `done` | End-of-session wrap-up: detects what changed, updates CLAUDE.md with gotchas only (not inventories), runs the test suite, commits and pushes, and prints a short status report. |

## Licence

MIT - see [LICENSE](LICENSE).

## Credit

Built by Efi Perez, published from personal Claude Code skills developed for real day-to-day work.
