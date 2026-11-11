---
title: DMX Toolkit privacy policy
permalink: /toolkit/
---

# Privacy policy — DMX Toolkit

Last updated: 2026-11-11

DMX Toolkit is a free Android app by dmx fun for lighting technicians. This page explains what the app does with your data. Short version: the developer collects nothing. There is no account, no server of ours, no analytics and no ads.

## What stays on your phone

Your patches, fixture profiles, favourites and settings are stored in the app's private storage on your phone. They are never sent to the developer. Uninstalling the app deletes them. The "Export" functions write files only where you choose to share them.

## Network traffic

- **Lighting network.** The app sends Art-Net and sACN (DMX) packets and RDM requests to the address you choose on your local network. This traffic stays on that network.
- **GDTF Share (optional).** If you use "Search GDTF Share", the app sends the GDTF Share login and password you enter to gdtf-share.com, and downloads the fixture catalogue and the profiles you pick. The login and password are kept in the phone's secure storage (Android Keystore) and sent only to gdtf-share.com. Signing out deletes them. GDTF Share's own terms and privacy policy apply to that service.
- **Photo profile (optional).** If you use "Read chart from photo", the photo you take or choose is sent to the Anthropic API (api.anthropic.com) together with your own Anthropic API key, which you enter yourself. The key is kept in the phone's secure storage and sent only to Anthropic. Anthropic's terms and privacy policy apply to what it receives. The developer never sees your photos or your key.

If you never use these two functions, the app sends nothing to the internet.

## Permissions

- **Internet / network state / Wi-Fi state:** to reach your lighting node and, optionally, the two services above.
- **Camera:** only to photograph a DMX chart for "Read chart from photo". Photos are not stored by the app beyond that feature.
- **Notifications, foreground service, wake lock:** to keep long output runs alive with the screen off, and to show that the app is sending.

## Data shared with third parties

The developer shares nothing. Data goes to GDTF Share or Anthropic only when you use the matching function, as described above.

## Children

The app is not directed at children.

## Changes

If this policy changes, the new version will be published at this address with a new date.

## Contact

dmx fun — [CONTACT EMAIL]
