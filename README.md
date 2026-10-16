# CodeTalks Homebrew tap

## Diffbell

[Diffbell](https://github.com/CodeTalks/diffbell) watches key files across your
projects with Watchman and sends a Telegram message when they change.

```bash
brew install codetalks/tap/diffbell
diffbell install         # starts the agent and opens the web UI
```

After every `brew upgrade diffbell`, run `diffbell install` again to restart the
agent on the new version.

## Documentation

`brew help`, `man brew` or [Homebrew's documentation](https://docs.brew.sh).
