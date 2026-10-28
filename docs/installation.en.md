# Installation and updates

> Public Beta v1.3.0-beta.1 is available from the [official Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.3.0-beta.1).

## Before you start

- Designed for **64-bit Windows 10/11**, with .NET Framework 4.8 and Microsoft Edge WebView2 Runtime. Compatibility across devices still needs Public Beta validation.
- Get the installer and SHA-256 checksum only from this repository's [official Releases](https://github.com/k-kaiko/KaikoLibrary/releases). Compare the installer's name, size, and SHA-256 with the Release details.
- The first installer is not digitally signed by a trusted publisher. Windows may say “Unknown publisher.” Do not run a file whose origin you cannot verify.

## Install or update in place

1. Close KaikoLibrary. Back up your original images and `%LOCALAPPDATA%\KaikoLibrary\UserData`. Do not upload either to GitHub.
2. Download the official installer and compare its SHA-256 with the value in the Release.
3. Run the installer yourself. Isolated in-place upgrade tests passed from V1.2.1, V1.3-P3, and V1.3-P4 RC; **do not uninstall first or delete UserData**. For other older versions, keep the old installer and wait for compatibility guidance.
4. Open the app and check libraries, favorites, tags, and progress. If folder authorization asks you to confirm a root, choose the original library folder. This is not a reimport.

If WebView2 Runtime is missing, setup may use Microsoft's bootstrapper and need a network connection. If that fails, obtain the Runtime from [Microsoft's official WebView2 page](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) and retry.

Program files and personal data are separate; updates and uninstall are designed to retain the latter. Keep your own backups of important collections. See [troubleshooting](troubleshooting.en.md); clearing data is not a routine repair step.
