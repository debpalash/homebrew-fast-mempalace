# homebrew-fast-mempalace

Homebrew tap for [**fast-mempalace**](https://github.com/debpalash/fast-mempalace) —
local-first long-term memory for AI coding agents, in a single static binary.

```bash
brew tap debpalash/fast-mempalace
brew install fast-mempalace
```

This installs the native binary plus the on-device embedding model (bundled), and
wraps the binary so it works with zero configuration. Nothing leaves your machine.

Then, in Claude Code:

```
/plugin marketplace add MemPalace/fast-mempalace
/plugin install fast-mempalace
```
