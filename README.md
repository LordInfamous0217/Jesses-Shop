# Jesses-Shop

Third Earth Surfboards Repair Manager — repair intake, customer records,
employee work logs and payment bookkeeping. Payments and refunds are processed
outside this software, such as through Square.

## Windows download — version 1.9.1

- [Windows installer](https://github.com/LordInfamous0217/Jesses-Shop/releases/download/v1.9.1/ThirdEarthRepairManager-Setup-1.9.1.exe)
- [Release notes](https://github.com/LordInfamous0217/Jesses-Shop/releases/tag/v1.9.1)

Version 1.9.1 adds Administrator right-click repair-catalog removal, manual
merchandise inventory, customer-prefilled Start Sale, immutable logo-branded
merchandise receipts and shared/offline stock bookkeeping. In Merchandise,
search goods on the left and record the sale only after payment is handled
outside this app. Saved customer/repair records and old receipts are preserved.
Administrators manage stock and discounts; employees can sell and raise prices.

The normal field installer preserves the existing 1.7.2 repair workflow and data
location. It adds durable offline shared saves, Today/work tracking, appointments,
bookkeeping reports, per-PC Letter/A4 printer setup, Administrator audit and a
subdued point-break wave texture. Updates create verified local recovery archives
before database initialization; an existing database is not replaced with a cloud
snapshot merely because the version changed.

The existing private shop Worker keeps backward-compatible repair/customer feeds.
Upgrade all working PCs to 1.9.1 before using new catalog/sales features; finish
one online startup to download merchandise metadata for offline saving. Already
connected PCs retain their connection. New PCs must join and download shop records online first.
Waiting or conflicting saves remain under Today → Sync Queue; never re-enter a
payment because an acknowledgment is delayed. Actual payments are still processed
outside the app. Wireless printers require a working Windows-installed queue/driver.

Offline stock is provisional. Concurrent sales remain in the ledger; a shortage
warning prompts an Administrator to count physical stock. Inventory conflicts
remain under Today → Sync Queue for explicit review after a recovery archive.

This release passed 129 Windows automated tests and Worker isolation tests. Actual
shop printers and field hardware still need a hands-on test. The same normal
installer is used for testing and field installation; no isolated data mode is forced.

## Previous Mac previews — no new Mac update

- [Previous 1.7.2 Mac compatibility preview](https://github.com/LordInfamous0217/Jesses-Shop/releases/download/v1.7.2/ThirdEarthRepairManager-Mac-1.7.2-universal.zip)

## Mac Monterey beta — 1.7.3 beta 1

- [Universal Intel / Apple Silicon beta](https://github.com/LordInfamous0217/Jesses-Shop/releases/download/v1.7.3-beta.1/ThirdEarthRepairManager-Mac-1.7.3-beta.1-universal.zip)
- [Beta notes and testing limits](https://github.com/LordInfamous0217/Jesses-Shop/releases/tag/v1.7.3-beta.1)

This separate beta targets macOS 12 Monterey and later, audits bundled native
minimum OS requirements, uses software rendering on Monterey, and fixes
original-ticket preservation for local-only repair intake. Install it manually
for testing; stable update checks do not offer prereleases. Mac development is
currently out of scope. Tests on newer Mac hosts cannot prove operation on a real Monterey
computer; the office Mac Pro still needs a hardware test.

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
For a trusted, unmodified download, Apple's
[per-app opening instructions](https://support.apple.com/en-us/102445) explain
the **Open Anyway** option. This is not a notarized release.

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

If this repository is made private, the app's current unauthenticated GitHub
update checks/downloads will stop working. Private shop cloud sharing is
separate; it does not depend on this repository being public.
