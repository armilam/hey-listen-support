# Hey Listen

**Full-screen calendar alerts you can't miss.**

Hey Listen is a macOS menu bar app that shows full-screen reminders before your calendar events start. It detects meeting links, supports flexible snooze options, and gives you granular control over which events alert you and when.

---

## Getting Started

### 1. Install and Launch

After installing from the Mac App Store, Hey Listen runs in your menu bar. Look for the bell icon in the top-right corner of your screen.

> **Screenshot placeholder:** Menu bar with Hey Listen icon visible

### 2. Grant Calendar Access

Open **Settings → Calendars**. If Hey Listen doesn't yet have access to your calendars, you'll see a prompt — click **Continue** to request permission, then click **Allow** when macOS asks. Without this, no alerts can be shown.

> **Screenshot placeholder:** Calendars tab showing calendar permission prompt with Continue button

### 3. Choose Your Calendars

In **Settings → Calendars**, select which calendars you want alerts for. Calendars are grouped by account. You can also set a custom alert lead time per calendar — it overrides your global setting for just that calendar.

The right side of the tab shows a live preview of upcoming events from your selected calendars.

> **Screenshot placeholder:** Calendars tab showing calendar list grouped by account, with per-calendar alert time fields and the upcoming events preview

### 4. Configure Alert Timing

In **Settings → Alerts**, set how many minutes before an event the alert appears. You can also choose whether alerts appear on your active screen or all connected displays.

> **Screenshot placeholder:** Alerts tab highlighting the alert time field and screen picker

### 5. You're Set

Hey Listen runs silently in the background. When a meeting is about to start, a full-screen alert will appear.

> **Screenshot placeholder:** Full-screen alert showing an event title, time, and Join Meeting button

---

## Features

### Alerts

- **Full-screen alerts** — hard-to-miss reminders appear at your configured lead time before events start
- **Meeting link detection** — join links for Zoom, Google Meet, Microsoft Teams, and more are detected and shown as a prominent "Join Meeting" button in the alert
- **Open in native apps** — optionally have Zoom and Teams links open in their native desktop apps instead of a browser
- **Rich event descriptions** — event notes are rendered with formatting, and links are clickable
- **Flexible snooze** — snooze for 1, 5, or 10 minutes; snooze until a configurable number of minutes before the event; or snooze until the event starts
- **Mute from the alert** — mute the event or its entire recurring series directly from the alert, without opening Settings
- **Missed alert recovery** — if your Mac was asleep when an alert was due, it fires as soon as you wake up (as long as the event hasn't ended)
- **Focus restoration** — when you dismiss an alert, Hey Listen returns focus to whatever app you were using before
- **Alert preview** — use the "See an alert" button in Settings → Alerts to demo what an alert looks like; snooze and dismiss work normally
- **VoiceOver support** — alert controls are fully accessible via VoiceOver

### Menu Bar

- **Menu bar event list** — see upcoming events directly from the menu bar icon; configure how many days ahead to show (today through 7 days)
- **Calendar color dots** — events in the menu list show a color dot matching their calendar (shown when two or more calendars are monitored)
- **Meeting link indicator** — an optional video icon on menu items marks events that have a detectable meeting link
- **One-click meeting access** — join or copy meeting links directly from the menu
- **Dynamic menu bar label** — display the next event's start time or time remaining in several configurable formats, or hide it entirely; also shows time remaining for an event currently in progress
- **Event submenus** — click any event in the menu for quick access to:
  - Join or copy its meeting link
  - View full event details (title, time, location, notes, attendees)
  - Mute or unmute that event or its entire recurring series
  - Set a custom alert time for that event or series

> **Screenshot placeholder:** Menu bar dropdown showing event list with a submenu open

> **Screenshot placeholder:** Event detail panel showing title, time, attendees, and notes

### Filtering and Control

- **RSVP filtering** — choose which events alert you based on your response status (accepted, tentative, unanswered, or declined)
- **Mute by title** — suppress alerts for recurring events whose title contains a pattern you define, like "Focus Time" or "No Meeting Block"
- **Per-event and per-series alert times** — override the default alert lead time for any individual event or recurring series, directly from the menu bar
- **Work hours** — optionally limit alerts to your working hours and days

### General

- **Launch at login** — optionally start Hey Listen automatically when your Mac boots
- **Time format** — choose 12-hour, 24-hour, or your system default for all times shown in the app and menu bar

### Purchasing

- **2-week free trial** — try all features before buying
- **One-time purchase** — no subscription required

---

## Support

If you need help, have a feature request, or want to report a bug, please [open an issue](../../issues/new).

---

## Privacy

Hey Listen operates entirely offline. It accesses your calendar data locally and never transmits it. No accounts, no analytics, no tracking. Read the full [privacy policy](PRIVACY.md).
