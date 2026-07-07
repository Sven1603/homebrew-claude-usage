# homebrew-claude-usage

Homebrew tap for [Claude Usage](https://github.com/Sven1603/claude-usage) — a
macOS menu bar app showing live Claude 5-hour session usage.

## Install

    brew tap sven1603/claude-usage
    brew trust --tap sven1603/claude-usage
    brew install claude-usage

The `brew trust` line is required because Homebrew gates casks from non-official
taps behind explicit trust. Upgrade later with `brew upgrade claude-usage`.

The app is signed with a Developer ID and notarized by Apple, so it opens with
no Gatekeeper workaround.
