# Nelson Player updates

Official Nelson Player Android and Windows installers and update metadata.

Download the APK or Windows Setup from [the latest release](https://github.com/nlsnhudson-stack/nelson-player-updates/releases/latest). These downloads are public. They contain no provider login, personal library or signing keys.

- **Android / Fire TV / SHIELD:** install `Nelson-Player-0.3.34.apk` over your existing Nelson Player. Allow installation from your download source if your device asks. After this initial installation, Nelson Player checks for updates when opened; Settings also includes **Check for app updates**. Android still asks you to approve installation.
- **Windows x64:** run `Nelson-Player-Windows-0.2.15-Setup.exe`. The app checks for updates when opened; Settings includes **Check for updates**. Download and install when you are ready. Saved accounts and libraries remain in the existing profile.
- **Samsung:** updates remain manual and are not included in this feed.

`latest.json` describes both supported platforms, with version-specific URLs, exact byte sizes and SHA-256 checksums. The apps verify downloads before offering installation. Android also checks package identity and the existing signing certificate. Updates are not forced during playback or media downloads.

Release files are attached to GitHub Releases, rather than stored in Git history. The application source is maintained separately.
