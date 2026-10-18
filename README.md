# CodeTalks Homebrew tap

## Diffbell

[Diffbell](https://github.com/CodeTalks/diffbell) watches key files across your
projects with Watchman and sends a Telegram message when they change.

```bash
brew install codetalks/tap/diffbell
diffbell install         # starts the agent and opens the web UI
```

Upgrades need only `brew upgrade diffbell`: the agent restarts itself on the new
version within about a minute, and Telegram tells you (silently).

## Documentation

`brew help`, `man brew` or [Homebrew's documentation](https://docs.brew.sh).
