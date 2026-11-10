# 33degrees.studio (project notes for Claude)

The studio's public website. Static, one page; see README.md. Brand decisions live in the
`thirtythree-degrees-studio` repo's CLAUDE.md (name, logo, colors); don't redesign the logo here.

## Settled decisions: read first
- Dark page, yellow #f2c230 accent, the horizontal logo animated in the hero (Josh asked for a site "ready to go
  tomorrow", 2026-11-10). Futura Bold version of the mark until Josh picks between Futura and the chamfered 3.
- No trackers, analytics or outside fonts. No personal data, emails or addresses until Josh gives a studio contact.
- Public repo only with Josh's OK (GitHub Pages on the free plan needs it). Every public site also gets a card on
  joshramey.com (repo `jlr9842/joshramey-site`).

## Hub hookup

The hub (GitHub `jlr9842/hub`) holds the lessons, todos and status for all of Josh's projects. Every project has this same section; the source is `hub/skills/new-project/hub-hookup.md`.
- **Where:** `C:\Users\joshr\code\hub` on the PC, `~/code/hub` on the Mac. In a cloud thread the hub may not be on disk: add and clone `jlr9842/hub`, and read its `BRIEFING.md` first.
- **Start:** `git pull` the hub, read `INDEX.md`, and tell Josh in a line or two which open todos in `inbox/todos.md` are tagged `[thirtythree-degrees-site]` (they may be newer than this repo's own notes).
- **While working:** capture reusable lessons, ideas and todos with the `capture` skill as soon as you learn them. Where the skill isn't installed (cloud threads), follow `hub/skills/capture/SKILL.md` by hand.
- **End:** append each reusable lesson (gotcha, technique, mistake and fix) as one line to `hub/inbox/` (`tech.md`, `workflows.md`, `decisions.md`, format in `INDEX.md`), and list the lines you added in your final report's retro (what went well, what was slow, what you'd change). Then update this project's Status line in `hub/projects.md`, and commit and push the hub (a cloud thread opens a hub PR instead).
