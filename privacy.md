---
title: PeakState^ Privacy Policy
---
# PeakState^ Privacy Policy

**Last updated: October 11, 2026** · Applies to the PeakState^ iOS app


**On your device** — Your workouts, cardio sessions, GPS routes, and personal records are stored locally. PeakState^ has no server of its own for this data.

**No selling, no ads** — We don't sell data, run advertising, or use any analytics or tracking SDK.

**Three outside services** — Apple/RevenueCat (payments), Sentry (crash reports) and Apple Maps (the map picture on outdoor cardio screens) are the only outside parties. None of them receives your workouts, and your GPS route is never sent to anyone.

## Contents
1. Overview
2. Information we collect
3. What stays on your device
4. Location data
5. Third-party services
6. Notifications
7. Data retention and deletion
8. Your rights and choices
9. Security
10. Children's privacy
11. International users
12. Changes to this policy
13. Contact

## 01 Overview

PeakState^ ("PeakState^", published by Lua C LLC, "we", "us") is a strength-training and cardio-tracking app. This policy explains what information PeakState^ collects, where it's stored, and who (if anyone) it's shared with.

The short version: PeakState^ is built local-first. Your training log lives in a database on your phone, not on a server we run. The only outside parties involved are Apple's App Store and RevenueCat (to process your subscription, if you have one), Sentry (to tell us when the app crashes) and Apple Maps (to draw the map on outdoor cardio screens). None of them receives your workout data.

## 02 Information we collect

PeakState^ does not require an account, a name, an email address, or a phone number to use. The table below lists everything the app collects or generates, and where each thing actually goes.

| Data | Stored where | Ever leaves your device? |
|---|---|---|
| Workouts, sets, reps, weights | On-device database | No — unless you export a backup yourself |
| Workout history you import from a file (for example a CSV export from another training app) | On-device database | No — the file is read on your device and never sent anywhere |
| Cardio sessions & GPS routes | On-device database | No — your route is stored on your device and drawn on top of the map locally |
| The map picture on outdoor cardio screens | Apple Maps (built into iOS) | Yes — iOS requests map images from Apple for the area the map is showing (see §4) |
| Personal records & progress history | On-device database | No |
| Bodyweight, training goals, preferences | On-device database | No |
| Subscription status | Apple App Store / RevenueCat | Yes — to RevenueCat, to activate your subscription |
| Crash & error reports | Sentry | Yes — automatically, only when the app crashes or errors |
| Files you export (backup, CSV, share image) | Created on your device, in the app's temporary storage | Only where you choose to send them, through the iOS share sheet |
| Emails you send to support | Our mailbox | Yes — only what you write, sent by your own mail app when you choose to email us |
| Weekly summary notification (optional, off by default) | Built on your device from your training data and scheduled by iOS | No — never sent to us or to anyone |

We don't use analytics, advertising, or tracking software of any kind. There's no behavioral profiling, no ad identifiers, and nothing sold to data brokers.

## 03 What stays on your device

Every workout you log, every cardio session, every set and rep, your personal records, and the patterns PeakState^'s intelligence engine detects in your training — all of it is stored in a local database on your phone. We don't have a server that receives or stores this data, and we can't see it.

**Backing up your data.** PeakState^ lets you export a backup file of your training history for safekeeping, and restore from one. That export is created and shared entirely through your device's own share sheet — where it goes (iCloud, a file you keep, AirDrop, etc.) is your choice, not something PeakState^ controls or has visibility into.

**Importing your history.** PeakState^ can read a CSV export that you choose from your Files app (for example one exported from another training app) and add its workouts to your log. The file is read and processed entirely on your device; it is not uploaded, and PeakState^ does not receive a copy. Imported workouts are stored in the same local database as everything else, and you can remove them again from within the app.

**Exporting a spreadsheet or an image.** PeakState^ can also export your history as a CSV file and make a share image of a lift's best sets. Both are created on your device and handed to the iOS share sheet; where they go (Files, Messages, AirDrop, a social app, etc.) is your choice, and PeakState^ does not receive a copy. The files are kept in the app's temporary storage on your device and the previous export is removed the next time you export. A CSV that PeakState^ exported can be read back in through the same import described above.

**Resetting your data.** You can permanently erase your training history from within the app at any time. This is a real, irreversible deletion on your device — there's no copy on a server for us to also delete, because there never was one.

## 04 Location data

If you track an outdoor cardio activity (a run, walk, or ride), PeakState^ asks for permission to use your location while the app is in use. This is used only to record the route, distance, and pace of that specific activity.

- Location is requested only when you start an outdoor activity — never in the background, and never when you're not actively tracking a session.
- Your GPS route is stored in the same local, on-device database as the rest of your training data. It is not transmitted anywhere.
- **The map.** The live cardio screen and the route summary show a map from Apple Maps (the map built into iOS). To draw it, iOS asks Apple for map images of the area the map is showing, which, while you track an outdoor activity, is the area where you are, and Apple receives your device's network address with those requests, as it does for any app that shows an Apple map. Your route's coordinates are not sent: the route line is drawn on your device on top of the map. Apple handles those map requests under Apple's own privacy policy; PeakState^ does not receive or store them. This map is the only part of the location feature that uses the network.
- You can deny or later revoke location access in iOS Settings at any time; PeakState^'s other features work normally without it.

## 05 Third-party services

PeakState^ uses exactly three outside services. None of them receives your training or cardio data, and none receives your GPS route.

**RevenueCat & the Apple App Store.** If you subscribe to PeakState^ Pro, your purchase is handled by Apple's App Store and processed through RevenueCat, which manages subscription status on our behalf. RevenueCat receives your purchase/subscription receipt information and an anonymous app-user identifier — never your name, your workouts, or your location. See RevenueCat's privacy policy for how they handle it.

**Apple Maps.** On outdoor cardio screens the map picture comes from Apple Maps, as described in §4. See Apple's privacy policy for how Apple handles map requests.

**Sentry (crash reporting).** If PeakState^ crashes or hits an unexpected error, a diagnostic report — the error itself, and technical device information like OS version and app version — is sent to Sentry so we can fix it. These reports are about app stability, not your training data. See Sentry's privacy policy for details.

## 06 Notifications

PeakState^ can schedule local notifications directly on your device. Today that is one optional notification: a weekly summary, off by default, that you can turn on or off in Profile. It arrives on Mondays and describes the training week that just ended using your own logged data, for example how many sessions you logged and, for Pro, the first line of that week's read. The text is built on your device from your on-device database and scheduled with iOS's local notification system; it is delivered by iOS itself, and no notification content or scheduling data is sent to PeakState^, RevenueCat, Sentry or anyone else. PeakState^ asks for notification permission only when you turn the weekly summary on, and you can revoke it at any time in iOS Settings → Notifications. (A reminder before a free trial ends, if a trial is offered, is also a local notification of the same kind.)

## 07 Data retention and deletion

Because your training data lives on your device, you control its retention directly: it stays until you delete the app, use the in-app reset feature, or manually remove it. RevenueCat and Sentry retain the limited data described above according to their own policies; Sentry error reports are not retained indefinitely and are used only for debugging.

## 08 Your rights and choices

Because PeakState^ doesn't collect personal data on a server, most data-subject requests (access, correction, deletion, portability) are things you can already do yourself, instantly, inside the app:

- **Access & portability** — export a full backup, or a CSV spreadsheet of your history, at any time from Profile.
- **Deletion** — permanently erase your training history from Profile (Clear History), or delete the app to remove everything, including the local database, from your device.
- **Location permission** — grant, deny, or revoke at any time in iOS Settings → Privacy → Location Services.
- **Subscription data** — managed through your Apple ID / App Store account; contact Apple for App Store purchase records, or us for anything RevenueCat-specific.

If you're in a region with additional statutory rights (for example the EU/UK or California) and have a request we haven't covered above, contact us using the details in §13 and we'll respond within the timeframe your law requires.

## 09 Security

Your training data is protected by your device's own security (passcode, Face ID/Touch ID, iOS's data protection). Because it never leaves your device by default, there's no PeakState^-operated server or database to be breached. Data you choose to export in a backup is only as secure as wherever you choose to save or share it.

## 10 Children's privacy

PeakState^ is not directed at children under 13 (or the relevant minimum age in your region), and we do not knowingly collect personal information from them.

## 11 International users

Your training data stays on your own device regardless of where you are. Where data does leave your device — a subscription purchase via RevenueCat, a crash report via Sentry, or a map request to Apple Maps — it may be processed in countries other than your own, per those providers' own policies (linked in §5).

## 12 Changes to this policy

If this policy changes in a meaningful way, we'll update the "Last updated" date above and, for significant changes, note it in the app.

## 13 Contact

Questions about this policy or your data:

| | |
|---|---|
| Email | admin@luacllc.com |
| Developer / entity name | Lua C LLC |
| Address | *(omitted)* |
