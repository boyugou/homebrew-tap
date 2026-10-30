# Homebrew tap of Right Here

[Right Here](https://github.com/boyugou/right-here) sends a folder or a Finder selection to terminals, editors and AI agents. It needs
a Mac with Apple silicon and macOS 26 or later.

```sh
brew install --cask boyugou/tap/right-here    # the app: the Finder menu, the setup window and rh
brew install boyugou/tap/rh                   # only the rh command-line tool, built from source (needs Xcode 26)
```

Then open Right Here and press **Set Up**, or run `rh setup`.

The files here are copies. Their source is [`packaging/homebrew`](https://github.com/boyugou/right-here/tree/main/packaging/homebrew)
in the main repository, and each release copies them here. Report problems there.

Licensed under the Apache License 2.0, as Right Here is.
