# Contributing

I highly suggest using a three-way merge tool (e.g. WinMerge) when managing this project. Updating this project to a new Stellaris release typically takes a couple hours; for v4.2 the repository was re-documented for GitHub.

Guidelines:
- Document changes clearly. Update the appropriate Changes and ChangeLog files for PRs.
- Avoid unnecessary changes (whitespace-only, formatting changes) unless required.
- Contributions become public and may be reused by others — please keep that in mind.

## What is in scope
We accept fixes for:
- Crashes
- Exploits (serious unintended advantages)
- Functionality additions that don't unbalance the game
- AI improvements
- General bugfixes
- Oversights (flavor/bad behavior)
- Performance improvements (remove expensive operations)
- Mod support (avoid breaking mods)
- UX and cosmetic fixes (typos, icons, graphics)

## What is out of scope
- Tuning/Balance-only changes (unless part of a larger fix)
- Major gameplay redesigns (there will be a separate balance mod for that)

## Branch policy
Every major Stellaris release gets its own branch (e.g. 3.6, 3.14). The `master` branch targets the current version.

## Pull Request checklist
- Clear description of the problem and the fix
- Minimal, focused diff
- Updated ChangeLog/Changes where applicable
- No unnecessary reformatting

Thanks for contributing.

(See also: [Credits.md](Credits.md) and the in-repo changelogs.)
