---
layout: doc
description: "How MeshLive handles your information: nothing is collected, and everything stays on your phone."
title: MeshLive privacy policy
permalink: /privacy/
---

# Privacy policy

Last updated: 13 November 2026 (iPhone and Mac section added)

MeshLive is an open-source app for calls, chats and livestreams between phones over Bluetooth. This policy explains
what happens to your information.

## We collect nothing

MeshLive has no servers, no accounts, no analytics and no ads. The developers never receive your calls, messages,
livestreams, contacts, name, location or any other information about you.

## What stays on your phone

The app keeps the following only on your phone: your contacts and their names, recent calls, chat messages and
attachments (stored encrypted), your settings, and your phone's MeshLive identity keys. Android backups of this data
are turned off.

## What other phones nearby receive

MeshLive talks directly to other phones over Bluetooth. Calls, chats and livestreams are end-to-end encrypted.

- **Livestreams are public.** Anyone nearby with MeshLive can watch or listen, and other phones can pass them on.
- **Calls and chats** go only to the person you call or message. Phones that help relay them cannot see or hear the
  content.
- Your phone broadcasts a short Bluetooth announcement so others can find you. Its ID changes regularly. Your name is
  shared only with the people you choose.

The full technical detail is in the [privacy and security document](https://github.com/MeshLive/meshlive-android/blob/main/docs/privacy.md).

## Internet use

MeshLive works without internet. The only internet connections are:

- **Check for updates** (versions downloaded from GitHub only): the app asks GitHub for the latest release. GitHub sees
  your IP address, as with any website. App store versions use the store's own updates instead.
- **Crash reports**: if the app closed unexpectedly, it offers to share a report the next time you open it. Nothing is
  sent unless you choose to send it, and you pick the app that sends it.

## Permissions

- **Bluetooth (Nearby devices):** to find and connect to other phones.
- **Microphone and camera:** only for calls and livestreams you start or accept.
- **Notifications:** to show incoming calls and messages.
- **Location (Android 10 to 12 only):** Android requires it for Bluetooth scanning on these versions. MeshLive never
  reads your location.

## Deleting your data

Use **Settings > Delete everything** in the app, or uninstall it. Either removes everything MeshLive stored on your
phone. There is nothing to delete anywhere else, because nothing is stored anywhere else.

## Children

MeshLive is not directed at children under 13.

## Changes

Changes to this policy are published on this page and in the app's source code history.

## Contact

Questions or concerns: email [meshlive.dev@gmail.com](mailto:meshlive.dev@gmail.com) (also from **Settings > Contact us** in
the app), or open an issue at [github.com/MeshLive/meshlive-android/issues](https://github.com/MeshLive/meshlive-android/issues).
Contacting us sends an email from your own email app; we only see what you write.

See also our [child safety standards](../child-safety/).

## iPhone and Mac

This section covers the MeshLive app for iPhone and Mac.

### In short
- MeshLive has no account, no server, no ads and no analytics. The developers collect no data about you.
- Calls and livestreams go directly between nearby devices over Bluetooth and are end-to-end encrypted (calls) or encrypted
  between devices (livestreams). Nothing goes through the internet.
- The content is encrypted; the fact that a MeshLive device is nearby is not hidden from someone with a Bluetooth scanner.
- Your identity key stays in the device Keychain. Contacts, recent calls and settings stay on your device and are not backed up.
- Release builds keep no log file and write nothing to the system log.

### What the app asks for
- Bluetooth: to find and connect to people nearby.
- Microphone: for calls.
- Camera: for video calls and to scan a contact's code (asked the first time you need it).
- Notifications: so your device rings for a call.
MeshLive does not use your location, contacts, photos or advertising identifier, and does not track you.

### What nearby devices can see
While the app is open and ready for calls, its Bluetooth announcement carries a rotating ID that changes every 15 minutes. A
livestream offer or a viewer request can carry a stable ID prefix, so a scanner that records them can recognise the same device
over time. Connections use hidden identities: a stranger sees a temporary ID, and your usual ID goes to verified contacts and to
a person you call or whose call you accept. Your name is never broadcast: it is sent encrypted only to the people "Who sees
my name" allows. A livestream title is public to anyone who joins. MeshLive does not make you anonymous. iOS may show your
iPhone's device name (Settings > General > About > Name) to a device that connects, so give it a neutral name.

### What stays on your device
Your keys, verified contacts, recent calls (encrypted with a key that never leaves the device) and settings. "Delete
everything" in Settings erases them. It cannot erase copies held by other people or backups made elsewhere.

### Crash reports
After a crash, the system gives MeshLive a diagnostic. The app keeps a short report (app and system version, device model and
where the app failed; no names, IDs, messages or keys) for up to 7 days and asks at the next launch whether you want to share it.
It is sent only if you share it yourself. "Don't ask again" deletes it and stops keeping reports. "Export diagnostics" in
Settings shows a short technical text before anything leaves the device.

### Blocking and reporting
Blocking is local: the block list is stored encrypted on your device and nobody is told. A report only prepares an email that
you choose to send.

### Children
MeshLive is for people 18 and older.

### Third-party code
MeshLive includes the open-source Opus and libvpx codecs. Their licences are shown in the app under Settings > About this app >
Open-source licences.

### On a Mac
On a Mac, MeshLive advertises from the Mac's fixed Bluetooth address, so anyone scanning nearby can recognise the same Mac over
time. Turn off Allow calls or quit the app when you do not want to be recognisable.

### Contact and changes
meshlive.dev@gmail.com. We will update this page when the app changes; the date of the last change is at the top of the
published page.
