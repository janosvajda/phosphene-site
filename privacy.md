---
title: Phosphene Privacy Policy
permalink: /privacy/
---

<p class="back"><a href="{{ "/" | relative_url }}">← Phosphene</a></p>

# Phosphene Privacy Policy

Effective date: 15 November 2026

Phosphene is a free macOS audio visualizer developed by Jan Vajda. It processes
audio on your Mac to produce visuals. Phosphene does not send your audio,
screenshots, listening activity, or settings to the developer
or to a third party. It has no advertising, analytics, tracking, accounts, or
in-app purchases.

## System audio permission

Phosphene uses Apple's Core Audio taps to receive system audio from all apps or
from an app you choose. macOS asks for the “System Audio Recording” permission
the first time Phosphene starts listening.

Audio samples are held briefly in memory for analysis and visualization. They
are not saved as audio recordings. Phosphene does not record your microphone
or your screen.

With All Sound, Phosphene hears everything your Mac plays, which can include
the voices of people in a call or a video. To avoid this, Phosphene stops
listening while any app uses a microphone, as during a call, and starts again
after; you can turn this off in Settings. A call you only listen to, without a
microphone, cannot be told apart: choose your music app in the Audio menu, or
pause listening.

Analyse Music (Audio → Analyse Music) names the instruments and voices it
hears using Apple's built-in Sound Analysis, entirely on your Mac and only while
Analyse Music is shown. Nothing it hears or recognises is saved or sent.

You can stop listening in the Audio menu, quit Phosphene, or revoke its permission
to hear the sound in System Settings → Privacy & Security.

## Files stored on your Mac

Phosphene stores settings, your selected audio app's name and bundle identifier,
and visual-selection preferences.
The sandboxed app stores these files in its own container's Application Support
folder. Development builds may use the project folder or an explicitly selected
development location.

Use Settings → Open Settings Folder to find these files.
You can delete them in Finder; quitting the app before deleting settings prevents
later changes from saving them again. Removing the app's container deletes all
of its local settings.

## Diagnostics and external links

Phosphene does not automatically upload diagnostics. Developer tools, when
explicitly enabled in a development build, can write local logs, visual snapshots,
and audio-analysis measurements. macOS may separately collect crash reports or
usage information under your Apple privacy settings; Apple controls that service.

Opening the online privacy policy, help, or repository launches your browser.
GitHub and your browser may process connection information under their own
privacy policies. Phosphene does not embed GitHub tracking or send it any
audio. If you voluntarily open a GitHub issue, the information you post is handled
by GitHub and may be public. Do not include private recordings or sensitive data.

## Sharing, retention, and changes

Phosphene does not sell or share your data. Transient audio is discarded as the
in-memory buffer is overwritten or the app quits. Local settings remain until
you delete them. Any change to these practices will be
described here with an updated effective date.

## Contact

For privacy questions, [open an issue on GitHub](https://github.com/janosvajda/phosphene-site/issues).
You can ask a general question without attaching personal information.
