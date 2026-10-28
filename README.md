# Getter releases

Installers for [Getter](https://github.com/hofferman/getter), a local-first HTTP
client for macOS. The app checks this repo for updates.

## Install

Download the `.dmg` for your Mac from the [latest release](../../releases/latest):

- `Getter-<version>-arm64.dmg` for Apple Silicon (M1 and later)
- `Getter-<version>-x64.dmg` for Intel

Drag Getter to Applications, then run this once, because the app is not signed with
an Apple Developer certificate:

```sh
xattr -dr com.apple.quarantine /Applications/Getter.app
```

After that, Getter updates itself: **Getter → Check for Updates…**, or wait for the
prompt it shows when a new version is out.
