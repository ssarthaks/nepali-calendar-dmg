# Patrobar — Nepali Calendar for Mac

> **Sajilo Patro is now Patrobar** (version 2.4.0). Same app, new name. If you have Sajilo Patro
> installed, it updates itself to Patrobar and keeps your settings and Pro licence.

**Patrobar** (पात्रोबार) puts today's Bikram Sambat (BS) date in your Mac's menu bar, with
Government of Nepal public holidays, festivals and tithi one click away. Free, private and offline.

Website: **[nepali-calendar.sarthaksharma.com.np](https://nepali-calendar.sarthaksharma.com.np/)**

This repository only hosts the downloads (see [Releases](../../releases)). The source code is not
public.

## Install

**Homebrew**

```bash
brew install --cask ssarthaks/tap/patrobar
```

**Or download the DMG**

[Download the latest version](../../releases/latest/download/Patrobar.dmg), open it and drag
**Patrobar** into **Applications**.

One download for Apple Silicon and Intel Macs. Requires macOS 11 Big Sur or later.

## Update

From version 2.2.0, Patrobar updates itself: it checks once a day, a dot appears on the
popup's Settings button, and **Settings → About → Update & Relaunch** installs the new version.
Updates are signed and verified before they are installed. You can also check now from the same
place, or turn the daily check off.

On version 2.1.2 or earlier, update once by hand: `brew upgrade --cask patrobar`, or download
the latest DMG above and replace the app in **Applications**. Your settings are kept. See
[Releases](../../releases) for what's new in each version.

## Features

- **Menu bar date** in Nepali or English: day and month, weekday, full date, tithi, BS and AD, or
  your own layout, as plain text or in a frame, with or without the icon.
- **Month calendar** with AD dates, public holidays, festivals and every day of Dashain and Tihar.
  Click a day for its date, tithi and events.
- **Upcoming events and holidays** with a countdown ("Tomorrow", "in 4 days"), and a BS → AD
  converter.
- **Desktop widgets**: a Today card, a Month calendar you can browse and click, and Upcoming
  events on your wallpaper, on every Space.
- **Your own calendars**: events from the Mac's Calendar app and reminders with a due date on
  their Nepali dates, from every account on your Mac, including **Google Calendar** (add your
  Google account in System Settings → Internet Accounts), iCloud and Outlook. Turn it on in
  Settings → My calendars. Read-only: Patrobar never changes your calendars.
- **One-click updates** from Settings → About.
- Light and Dark, opens at login, works offline. No account, no ads, no tracking.

## First launch

Patrobar isn't notarized by Apple yet, so the first time you open it macOS asks you to confirm.
Open **System Settings → Privacy & Security**, click **Open Anyway** next to the Patrobar
message and confirm. You only do this once per version. Then click the date in your menu bar.

To check a download, compare its SHA-256 with `SHA256SUMS.txt` in the release:

```bash
shasum -a 256 ~/Downloads/Patrobar*.dmg
```

## Pro

Everything above is free. **Patrobar Pro** (NPR 299, one time, for life, on two Macs) adds
twelve colour themes, each in light and dark or following macOS (Himalaya, Lali Gurans, Phewa,
Mustang, Everest Night, Terai Sunset, Tihar Lights, Dhaka, Chitwan, Rara, Jacaranda and Barkha),
the upcoming Ekadashi, Purnima and Aunsi list, and popup customisation (card opacity, accent
colour, size and more). To get a licence key, use the
[contact form](https://sarthaksharma.com.np/contact),
[LinkedIn](https://www.linkedin.com/in/ssarthaks/) or email ssarthakxd@gmail.com.

---

© 2026 [Sarthak Sharma](https://sarthaksharma.com.np/). All rights reserved. Patrobar is free to
download and use; Pro features need a licence. Not an official government calendar and not
endorsed by the Government of Nepal.
