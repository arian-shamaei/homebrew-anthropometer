# homebrew-anthropometer

Homebrew tap for [**amtr**](https://github.com/arian-shamaei/anthropometer) — a
btop-style real-time context monitor for Claude Code sessions.

```sh
brew tap arian-shamaei/anthropometer
brew trust arian-shamaei/anthropometer   # newer Homebrew asks you to trust third-party taps
brew install amtr
```

Report features (the `R` key / `amtr-paper`) need extra tooling:

```sh
pip install matplotlib pillow
brew install tectonic
```
