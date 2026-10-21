---
title: MeshLive privacy policy
permalink: /privacy/
---

# Privacy policy

Last updated: 22 October 2026

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
