# SETUP.md -- your vault coordinates

> **For the participant.** Fill this in at the end of bootstrap. Commit it. Every future agent session that starts in this repo reads this file first so it knows **where your vault lives** and **what to write to**.
>
> **For the agent.** If any of the fields below are still `<TODO>` and the user asks you to save, note, capture, or log something, stop and run the bootstrap first. Do not guess a location.

**Path:** A
**Agent:** Claude Code
**Last updated:** 24.04.2026

---

## Path A -- Obsidian vault

- **Vault path (absolute):** `/Users/larstonder/Documents/personal/vault`
- **Git remote for the vault:** `git@github.com:larstonder/vault.git`
- **Branch:** `main`
- **Skills present in `$VAULT/.claude/skills/`:** `obsidian-vault`, `youtube-transcribe`, `skill-creator`, `brainstorming` (the four that ship with starter-vault).

---

## Notes

- Primary goal: building flexibility plan (side + front splits) to improve kicking for ITF Taekwondo patterns competition. First real notes are 4 Learning summaries of flexibility YouTube videos plus a master `Projects/Flexibility.md` plan.
- Vault git repo is separate from the workshop repo (`second-brain/`). Vault already initialised as `main` with remote to `github.com/larstonder/vault.git` at bootstrap time.
- `yt-dlp` installed via Homebrew during bootstrap (needed for the `youtube-transcribe` skill).
