# TermRoad releases

Downloads of [TermRoad](https://termroad.com) for macOS and Windows, and the feeds the apps check for
updates.

**Download:**
- **macOS:** [TermRoad.zip](https://github.com/TermRoad/releases/releases/latest/download/TermRoad.zip)
  (the newest Mac release; [all Mac releases](https://github.com/TermRoad/releases/releases) are
  tagged `v<version>`).
- **Windows:** [TermRoad.Windows-win-Setup.exe](https://github.com/TermRoad/releases/releases/download/windows/TermRoad.Windows-win-Setup.exe)
  (the newest Windows release; each version is also kept in a `windows-v<version>` release).

**Update feeds:**
- macOS: `appcast.xml` here, served by GitHub Pages, for Sparkle.
- Windows: the `windows` release, whose files each Windows release replaces. Installed copies check
  its `releases.win.json`, accepted only with a valid signature.

Everything here is published by TermRoad's release workflows. Mac zips are signed with Developer ID,
notarised by Apple, and signed for the app's updater. Windows packages are listed in a signed update
feed. Please don't open issues or pull requests here; for support, see
[termroad.com](https://termroad.com).
