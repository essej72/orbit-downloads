# Orbit for Windows — tester preview

Orbit brings a supported iPhone into a Windows workspace, with a movable phone view, mouse controls and automatic keyboard input where the connection supports them.

## Download

[Download Orbit 0.11.2 for Windows x64](https://github.com/essej72/orbit-downloads/releases/download/v0.11.2/Orbit-Windows.zip)

[Release notes and checksums](https://github.com/essej72/orbit-downloads/releases/tag/v0.11.2)

1. Download `Orbit-Windows.zip` and use Windows **Extract All**.
2. Keep the entire extracted `Orbit-win32-x64` folder together. Open `Orbit.exe` inside it.
3. Read `TESTER-START-HERE.md` for the connection appropriate to your setup.

## Connect

**Nearby Wi-Fi → Automatic** is selected first. For an already prepared phone, keep it unlocked on the same network and click **Connect phone**. Reconnect can reuse the last successful method.

A new phone or PC needs one-time trusted USB preparation and Developer Mode for native wireless control. Follow the included setup guide, then use **Prepare Wi-Fi by USB**. After successful preparation, routine Nearby Wi-Fi sessions do not need a cable.

For first-time viewing with no cable, select **Cable-free viewing** and use the iPhone's Screen Mirroring menu. This AirPlay route is viewing-only; PC touch and typing are unavailable.

## Preview scope

- Windows x64. iPhone services and iOS version determine available controls; the tested native live-control path uses compatible iOS 27+ services.
- Keep the iPhone awake and unlocked. Screen-off control and remote unlocking are unsupported.
- Private VPN is experimental. Phone cellular control is unsupported; separate-location operation is unverified.
- First-time preparation on additional phones and PCs still needs tester validation. Existing successful physical checks apply to the original prepared setup, not every iPhone.
- The download contains the app and bundled runtime, not another person's device pairing or credentials.

The app includes privacy details, versioned release notes and dependency notices. The matching source bundle for the redistributed AirPlay receiver is attached to the release.

For useful feedback, report your Windows version, iPhone/iOS version, connection method and steps that caused the issue. Orbit can export diagnostics that omit phone content and device addresses; review anything you share. Do not post pairing files, account credentials or private phone screenshots.
