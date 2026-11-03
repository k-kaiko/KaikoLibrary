# Installation and in-place updates

Get `KaikoLibrary.v1.4.0.Setup.exe` and `SHA256SUMS.txt` from the [official v1.4.0 Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.4.0).

## Before installation

- Designed for 64-bit Windows 10/11, .NET Framework 4.8 and Microsoft Edge WebView2 Runtime. Not every system or device has been tested.
- The installer has no trusted-publisher digital signature. Windows may show “Unknown publisher.” Verify its source, name, size and SHA-256; do not run a file whose origin you cannot establish.
- Close KaikoLibrary and back up originals and `%LOCALAPPDATA%\KaikoLibrary\UserData` separately. Never upload these backups to GitHub.

## Install or update

1. Compare the Release checksum, run the installer yourself, and read and accept the license.
2. **Do not uninstall first or clear UserData.** Isolated upgrades cover V1.2.1, V1.3-P3, V1.3-P4 RC, v1.3.0-beta.1 and V1.4 candidate.1, candidate.2 and rc.1. Other sources have not all been verified.
3. Open the app and check libraries, tags, favorites, groups and continue-reading. If native Windows authorization is requested, choose the original library root. This is not a reimport.

Without WebView2 Runtime, setup can use Microsoft's bootstrapper and may need internet access. If it fails, obtain the Runtime from [Microsoft](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) and retry.

Program files and personal data are separate. Upgrade, rollback and uninstall data retention have been tested using synthetic profiles, not every possible failure environment. Retain the old installer and backups; restoring program files does not restore a personal database. Deleting the database or reinstalling is not routine troubleshooting. See [troubleshooting](troubleshooting.en.md).
