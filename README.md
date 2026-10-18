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

## Publishing (maintainers)

A formula change is a pull request; `brew test-bot` builds and tests it, with a
bottle for each macOS in its matrix. Publish it with the **brew pr-pull** workflow
(Actions → brew pr-pull → Run workflow, the PR number), never with GitHub's merge
button: pr-pull uploads the bottles to this repository's releases, adds the
formula's `bottle do` block and pushes to `main`.

## Documentation

`brew help`, `man brew` or [Homebrew's documentation](https://docs.brew.sh).
