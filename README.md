# Package Bundle

This repository stores my personal [Homebrew](https://brew.sh) setup using a `Brewfile` and [Oh My Droid](https://github.com/tsirysndr/oh-my-droid) setup using a `oh-my-droid.toml`.  
It allows me (or anyone else) to quickly reinstall and sync all my brew packages, casks, taps and linux packages across machines.

## Install from Brewfile

Clone this repo and run:

```bash
brew bundle --file ./Brewfile
```

This will install all packages, casks, and taps listed in the `Brewfile`.

## 📂 Contents

- `Brewfile` — List of all installed brew formulas, casks, and taps.
- `oh-my-droid.toml` - List of all installed Android Linux Terminal/Debian packages.

## 💡 Notes

- Useful for setting up a new macOS machine/Android Linux Terminal/Debian in minutes.
- Ensures consistency across multiple environments.

## 📜 License

MIT - free to use, share, and modify
