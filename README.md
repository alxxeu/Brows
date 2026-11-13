# holoholo

holoholo is a native macOS browser written in fast Swift and powered by Chromium. It is quick, modern and carefully thought through: tabs live in a sidebar and are organized into Spaces, so work, study and personal browsing stay apart. Pages are rendered by Chromium, so websites behave as they do in Chrome, and extensions from the Chrome Web Store work.

**Alpha, closed test.** New builds appear on the [Releases](../../releases) page, and the app updates itself.

## Requirements
- macOS 26 or later
- Mac with Apple Silicon (M1 or newer)

## Install
Download `holoholo.dmg` from the latest release, open it and drag holoholo to Applications. The app is signed with a Developer ID certificate and notarized by Apple.

## What makes it different
- **Tabs live in the sidebar**, grouped into Spaces. Swipe with two fingers to flip between Spaces, each one remembers its last tab.
- **Pinned tabs, folders and favorites** keep your sites where you left them; closed tabs go to an archive instead of disappearing.
- **One command bar** for addresses, search and switching tabs.
- **Sort** tidies a messy tab list into topic groups. The grouping is done by an on-device model, nothing leaves your Mac.
- **Split View** puts two tabs side by side.
- **Private Space** is a locked space for private browsing, opened with Touch ID. Its tabs are stored encrypted, cookies and site data last only until you quit.
- **Tweaks** change how a site looks: hide elements, pick a font, narrow the page or add your own CSS.
- **Chrome extensions** live in the sidebar too: pin the ones you use, the rest sit in one tidy grid.
- **Import** your bookmarks, open tabs and extensions from Chrome, Brave, Edge, Vivaldi, Opera, Chromium, Dia and Firefox; Spaces, pinned tabs and favorites from Arc; bookmarks from Safari.
- **Companions** let tools like Claude Code, Claude Desktop or Cursor look at your tabs and act in them. Off by default; every companion asks first and you choose which Spaces it can reach.

## Limitations
- No password manager or autofill, one window
- No passkey support yet
- Safe Browsing warns about known phishing and malware sites; downloaded files are not scanned
- Extensions do not run in Private Space

## Problems and questions
- Bugs and ideas: open an [issue](../../issues)
- Security: see [SECURITY.md](SECURITY.md)

[Privacy](PRIVACY.md) · [Third-party notices](THIRD_PARTY_NOTICES.md)

© 2026 Aleksei Trofimov
