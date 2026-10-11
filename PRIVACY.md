# Padoo Trackpad for Windows: Privacy Policy

Last updated: October 2026

Padoo Trackpad for Windows lets your own iPhone, running the Padoo app, control this PC over your local network. It does not collect, sell or share personal data, and it has no accounts, ads, analytics or telemetry.

## Network

- The app announces itself on your local network (Bonjour/mDNS, using this computer's name) so your iPhone can find it.
- It talks only to iPhones you paired with a QR code, over an encrypted connection on your local network.
- The Microsoft Store version makes no internet connections. The version downloaded from GitHub checks GitHub once a day for a newer version; that request contains no personal data.

## What stays on your PC

- Pairing keys (trust.bin, encrypted with Windows data protection for your user account) and a random computer ID (device.json).
- App usage scores (usage.json): which of your taskbar-pinned apps you switch to and when. Used only for the "most used" row on your iPhone.
- Your optional deck settings (deck.json) and diagnostic logs.

None of these files leave your PC, and none are sent to the developer.

## What your paired iPhone receives

The names and icons of your pinned apps, the name of the app in front, volume levels and whether an app is using the microphone. This goes only to your own paired iPhone, over the encrypted local connection.

## Deleting your data

Uninstalling the Microsoft Store version removes the data it created. Files in %APPDATA%\PadooWin (for example a deck.json you made yourself, or files from an earlier GitHub install) stay until you delete that folder.

## Contact

Open an issue at https://github.com/RonYehuda/padoo-win-releases/issues
