# AGENTS.md

## Shared rules

Read `../VPOS-Lua-script-starter/CONTRIBUTING.md` before working here
(https://github.com/Touch-Vectron/VPOS-Lua-script-starter/blob/main/CONTRIBUTING.md if the sibling checkout is missing).
A rule you learn here that fits every VPOS script goes into that file, by pull request, in the same session.

## This repo

- Scripts: `logger.vsp` (installed on the POS), `logger_pasteInYourCode.vsp` (the block other scripts paste in).
- Default branch: `main`.
- Ticket prefix: `VCS`.
- Tests: `logger_ut.vsp` with `logger_ut.ini`, run on a VPOS.
- Tags: `logger_<version>`.
- A change to the pasted block affects every script that carries a copy; say so in the pull request.
