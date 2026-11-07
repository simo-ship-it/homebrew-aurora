# Homebrew tap for Aurora

[Aurora](https://github.com/simo-ship-it/Aurora) is a native Markdown editor for
macOS that shows text formatted while you write it.

```bash
brew install simo-ship-it/aurora/aurora
```

To update an existing installation:

```bash
brew update
brew upgrade simo-ship-it/aurora/aurora
```

This is a **formula**, not a cask: it fetches the source and builds Aurora on
your own machine. Aurora is not signed with an Apple Developer ID, so a
downloaded copy would be quarantined by macOS and refused at first launch —
something compiled locally never is. The build needs only Xcode's Command Line
Tools and takes about a minute.

To build straight from `main` instead of the latest release:

```bash
brew install --HEAD simo-ship-it/aurora/aurora
```

Every update is audited, built from source and tested on a clean macOS runner.
