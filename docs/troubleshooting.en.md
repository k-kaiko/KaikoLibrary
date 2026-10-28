# Troubleshooting

**ZIP unreadable or no cover?** Check for corruption, encryption, or a moved library root. Encrypted ZIP, RAR, and 7z are unsupported. Do not alter the source archive. If an older library needs native authorization, select its original root.

**Show location asks for a folder again?** This confirms native Windows file access, not a reimport. Select the original root corresponding to that library; cancelling does not delete its record.

**Thumbnail drawer does not appear?** Move the pointer to the reader's bottom edge, press `T` or `B`, or use the lower-left button. Touch and keyboard users can use the backup control.

**Mouse side buttons do not turn pages?** The browser runtime or device driver may handle them first. Use arrow keys or edge buttons and mention the device model in an Issue; do not attach your collection.

**Library missing after update?** Check that the original folder still exists, its drive is connected, and permission is valid. Do not uninstall or delete UserData. Close the app, preserve backups of originals and app data, then describe the issue in [GitHub Issues](https://github.com/k-kaiko/KaikoLibrary/issues).

**Setup needs WebView2?** Check network access or install the Runtime from [Microsoft's official page](https://developer.microsoft.com/en-us/microsoft-edge/webview2/). The first Beta installer does not have a trusted publisher signature.
