# Unscroll

Instagram without the endless scroll: no Reels, no Explore, no suggested posts —
just the people you follow, their stories, and your DMs.

**Latest version: 1.7.2** · [Download](https://github.com/blossqt/unscroll-releases/releases/latest)

## Install on Android

1. On your phone, download `Unscroll-1.7.2.apk` from the
   [latest release](https://github.com/blossqt/unscroll-releases/releases/latest)
   and open it. Allow installing apps from your browser when Android asks.
2. If Play Protect says the app is blocked, tap **Install anyway**: it warns
   about any app from outside the Play Store that asks for notification or
   accessibility access.
3. Open Unscroll and log in to Instagram on Instagram's own page.

## Install on iPhone

An iPhone only installs apps from the App Store, unless you use an app that
sideloads them. Unscroll is `Unscroll-1.7.2.ipa` in the
[latest release](https://github.com/blossqt/unscroll-releases/releases/latest),
unsigned, for any of these to sign with your own Apple ID and install:

- **SideStore** or **AltStore** (free): add this source, then install Unscroll
  from it. They update Unscroll whenever there's a new version.

  ```
  https://raw.githubusercontent.com/blossqt/unscroll-releases/main/altstore.json
  ```

  With a free Apple ID, Apple makes a sideloaded app stop opening after 7 days
  unless it's refreshed: SideStore refreshes it on the phone, AltStore through
  AltServer on your computer.
- **Sideloadly** (on a Mac or PC): download the `.ipa` and drag it in.
- **TrollStore**, on the iOS versions it works on: open the `.ipa` with it.
  Installed for good, no refreshing.

Then open Unscroll and log in to Instagram on Instagram's own page.
**Settings:** touch and hold the Unscroll icon on your Home Screen.

It needs iOS 16.4 or newer, and works best on iOS 26.2 or newer: the page
animations, and some of how stories play, use what Safari gained there. What an iPhone won't
let it do: show Instagram's notifications, block Instagram's own app (Screen
Time can: Settings → Screen Time → App Limits), or open Instagram links from
other apps by itself. For a link, copy it (touch and hold it, Copy) and come
back to Unscroll, which offers to open it.

## Updates

Unscroll checks here for a newer version when it opens, and twice a day while
it stays open, and offers to install it. It only believes an update carrying
the release signature (`latest.json.sig`), and Android only installs one signed
like the app it replaces, so it keeps you logged in. **Settings → Updates**
checks straight away.

On iPhone, Unscroll says when there's a new version, and SideStore or AltStore
install it from the source above.

## Source

Unscroll is free software under the AGPL-3.0, based on
[NoScroll](https://github.com/Blueturboguy07/noscroll) by Blueturboguy07. Each
release carries the source it was built from (`Unscroll-1.7.2-source.tar.gz`).

Not affiliated with, endorsed by, or connected to Meta or Instagram.
