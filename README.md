# homebrew-fast-mempalace

Homebrew tap for [**fast-mempalace**](https://github.com/debpalash/fast-mempalace) —
local-first long-term memory for AI coding agents, in a single static binary.

```bash
brew tap debpalash/fast-mempalace
brew trust debpalash/fast-mempalace   # newer Homebrew requires trusting third-party taps
brew install fast-mempalace
```

> Prefer no tap-trust step? The one-line `curl … | bash` installer in the main repo
> does the same thing without Homebrew.

This installs the native binary plus the on-device embedding model (bundled), and
wraps the binary so it works with zero configuration. Nothing leaves your machine.

Then, in Claude Code:

```
/plugin marketplace add MemPalace/fast-mempalace
/plugin install fast-mempalace
```
