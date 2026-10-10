# Jesses-Shop

Third Earth Surfboards Repair Manager — repair intake, customer records,
employee work logs and payment bookkeeping. Payments and refunds are processed
outside this software, such as through Square.

## Downloads — version 1.7.2

- [Windows installer](https://github.com/LordInfamous0217/Jesses-Shop/releases/download/v1.7.2/ThirdEarthRepairManager-Setup-1.7.2.exe)
- [Universal Mac app — compatibility preview](https://github.com/LordInfamous0217/Jesses-Shop/releases/download/v1.7.2/ThirdEarthRepairManager-Mac-1.7.2-universal.zip)
- [Release notes](https://github.com/LordInfamous0217/Jesses-Shop/releases/tag/v1.7.2)

The Mac download contains Intel and Apple Silicon backends in one application.
Unzip it on the Mac and move **Third Earth Repair Manager.app** to Applications.
It carries over the current Windows features and wave-styled interface,
including the full-size Support log console, permission rules, ticket reprints,
receipts and private cloud sharing. macOS dialogs and fonts differ from Windows.

The Mac build is still a testing preview: the user's Monterey Mac Pro and M1
MacBook Air, physical printing and Keychain behavior have not been verified.
Monterey is outside [.NET 10's official OS support](https://github.com/dotnet/core/blob/main/release-notes/10.0/supported-os.md).
The app is ad-hoc signed, not Apple Developer ID signed or notarized, and macOS
may block it. Do not disable Gatekeeper; contact the developer if it cannot open.

## Records and updates

Customer records and private connection codes are **not** bundled in downloads
or published here. Application data lives separately from installed program
files. A new computer must restore an encrypted backup or join the shop's
existing private cloud connection. Never seed the production shop from a blank
test computer.

An Administrator can check for updates inside the app. Confirming Update Now
downloads and verifies the appropriate platform package, saves a local recovery
copy, attempts a cloud backup, then closes for installation and reopening.
Save unfinished work first. If the older 1.7.0 Mac preview gets stuck closing
for an update, replace it manually with the 1.7.2 ZIP; the fix is included here.

For help, use the Support tab inside the app.
