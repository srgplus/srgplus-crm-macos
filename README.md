# SRG+ CRM for Mac

The Mac app of SRG+ CRM, for download outside the App Store.

**Download:** [SRG-Plus-CRM.dmg](https://github.com/srgplus/srgplus-crm-macos/releases/latest/download/SRG-Plus-CRM.dmg)

Open the DMG and drag SRG+ CRM to Applications. The app updates itself (Sparkle): it checks once a day, and
**SRG+ CRM › Check for Updates…** checks at once. It needs macOS 26 or later.

Sign in with your SRG+ account (a code by email or text). Since build 202610141628 the app works on the CRM's production
server.

This repository only hosts the releases (the DMG) and `appcast.xml`, the update feed the installed apps read
(GitHub Pages, `https://srgplus.github.io/srgplus-crm-macos/appcast.xml`). The app's code and the build script
(`apps/apple/scripts/mac-dmg.sh`) are in the private repository srgplus/srgplus-crm. Changes to `appcast.xml` go
through a pull request, never straight to `main`.
