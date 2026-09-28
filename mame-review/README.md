# mame-review plugin (Sep. 27, 2026)

This plugin allows your agent to do an in-depth review of either a Github pull request or local files.  It's based on MAME's published
C++ coding standards plus years of coordinator Vas Crabb's PR reviews and "Tidy" changelists, so it should represent the actual state of
what Vas and other maintainers are looking for.

**IMPORTANT** Passing meme-review does not mean your PR will be accepted, but it does give it better odds.

## How to install
Copy this entire mame-review folder into your agent's skills directory.  Or ask your agent how it wants this installed.

Claude Code on Linux or macOS: ~/.claude/skills/
Codex on Linux or macOS: ~/.codex/skills/
Grok Code on Linux or macOS: ~/.grok/skills/

## How to use
In your agent `/mame-review filespec`, where `filespec` can be a local path, a Github mamedev/mame pull request URL, or a Github
mamedev/mame pull request number.

## License
BSD-3-Clause
