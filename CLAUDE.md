# Tessera Documentation

This repo is the living design notebook for the game **Tessera**. It is used mostly for
back-and-forth ideation chats (often from a phone), so keep edits small, fast and easy to review.

## How to work in this repo
- Treat every chat as a note-taking session. When an idea, decision or open question comes up,
  write it to the right file before the session ends. Don't leave it only in chat.
- Capture first, organize later: raw thoughts go to `inbox/YYYY-MM-DD.md` (append, don't overwrite).
- Promote settled material from the inbox into `design/` (systems, world, etc.).
- Record firm decisions in `decisions/` as short files: `NNNN-short-title.md` with
  Context / Decision / Consequences. Never silently change a past decision; add a new one that supersedes it.
- Keep `OPEN_QUESTIONS.md` current: add new questions, remove ones that got answered (and note where).
- Update `GLOSSARY.md` whenever a new game term is coined, so terminology stays consistent.

## Conversation style
- Act as a collaborator, not just a scribe: push back, suggest alternatives, point out conflicts
  with existing notes.
- Keep replies concise; the user may be reading on a phone.
- Ask at most one or two clarifying questions at a time.

## Layout
- `inbox/`       raw daily notes
- `design/`      organized design docs (`systems/`, `world/`)
- `decisions/`   numbered decision records
- `OPEN_QUESTIONS.md`, `GLOSSARY.md`

## Git
- Commit small and often with clear messages. Work on a branch per session if asked; otherwise main.
- Never add `Co-Authored-By` trailers or "Generated with Claude Code" lines to commits or PR descriptions.
  The repo owner wants to be the sole author in history.
