---
title: AutoKlik — Privacy Policy
---

[Polski](pl/)

# AutoKlik — Privacy Policy

**Last updated:** 13 September 2026
**Applies to:** AutoKlik (`com.dismonder.autoclicker`), all versions from 1.1.0

## Summary

AutoKlik does not collect, transmit, or share any personal data. Everything the app
stores stays on your device. The app has no internet access at all — it does not
declare the `INTERNET` permission, so it is technically incapable of sending data
anywhere.

## What the app stores, and where

All of the following is written only to AutoKlik's private storage on your device:

| Data | Purpose | Where |
| --- | --- | --- |
| Automation profiles (names, tap/swipe coordinates, timings, loop settings) | The scenarios you build | Local database on device |
| Run history (start time, duration, click and loop counts, outcome) | The history screen | Local database on device |
| App settings (overlay opacity, default timings, toggles) | Your preferences | Local preferences file on device |

Nothing above is uploaded, backed up to the cloud, or shared with the developer or
any third party. Cloud backup and device-to-device transfer are explicitly disabled.

## What the app does *not* do

- No analytics, telemetry, crash reporting, or advertising SDKs.
- No account, sign-in, or user identifier of any kind.
- No access to contacts, location, camera, microphone, photos, files, or call data.
- No reading of the contents of other apps, and no logging of what you type.

## Permissions and why they are needed

**Accessibility service.** AutoKlik performs the taps and swipes you record by using
Android's accessibility gesture API (`dispatchGesture`). This is the only way for an
app to tap the screen on your behalf without root access.

The service is configured as narrowly as Android allows:

- It **cannot retrieve window content** — it cannot read what is on your screen.
- It **does not filter key events** — it cannot observe what you type, in AutoKlik or
  in any other app.
- It subscribes to no accessibility event data about your activity.

It only sends gestures. Nothing it can access is collected, stored, or transmitted.

**Display over other apps.** Shows the floating control panel and the click markers on
top of other apps so you can start, pause and stop a scenario without leaving them.

**Notifications.** Shows the run-control notification while a scenario is loaded or
running. Optional — the app works without it.

**Vibration.** Haptic confirmation when you use the floating controls.

## Children

AutoKlik is not directed at children and collects no data from anyone, including
children.

## Changes to this policy

If this policy changes, the updated version will be published at the same address and
the "Last updated" date above will change.

## Contact

Questions about this policy: **dismonder@gmail.com**
