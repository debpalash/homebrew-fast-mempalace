# homebrew-memxt

Homebrew tap for [**memxt**](https://github.com/Yupcha/memxt) — local-first long-term
memory for AI coding agents, in a single static binary.

```bash
brew tap Yupcha/memxt
brew trust Yupcha/memxt   # newer Homebrew requires trusting third-party taps
brew install memxt
```

Installs the native binary plus the on-device embedding model (bundled), wrapped so it
works with zero configuration. Nothing leaves your machine.

Then, in Claude Code:

```
/plugin marketplace add Yupcha/memxt
/plugin install memxt
```

Prefer no tap-trust step? The one-line `curl … | bash` installer in the main repo does
the same thing without Homebrew.
