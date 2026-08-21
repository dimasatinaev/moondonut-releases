# Moondonut — releases

Downloads and updates for [Moondonut](https://moondonut.pages.dev), an IDE for
Markdown documents.

The source lives elsewhere; this repository holds nothing but release
artifacts. Grab the newest build from **[Releases](../../releases/latest)**.

## macOS

Apple Silicon is `aarch64`, Intel is `x64`. Open the `.dmg`, drag Moondonut to
Applications, then run this once in Terminal:

```
xattr -cr /Applications/Moondonut.app
```

Preview builds are not code-signed yet, and without that command macOS says
**"Moondonut is damaged and can't be opened, you should move it to the
Trash"**. It is not damaged — that is what an unsigned app looks like on
current macOS, and right-clicking and choosing *Open* no longer gets around
it. The command clears the quarantine flag your browser attached to the
download.

## Windows

Run the `.msi`. On the SmartScreen notice choose **More info → Run anyway** —
again because the build is not signed yet.

## After that

Both warnings go away once the builds are signed and notarised. Once
installed, Moondonut updates itself from here: new versions arrive in the app
as *Update available · Install*.
