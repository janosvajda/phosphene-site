---
title: Phosphene Help
permalink: /support/
---

<p class="back"><a href="{{ "/" | relative_url }}">← Phosphene</a></p>

# Phosphene Help

Phosphene turns the sound your Mac plays into visuals that move with the music.
It is free, with no account, advertising or tracking.

## What you need

A Mac with Apple silicon and macOS 14.2 or newer.

## Getting started

1. Play some music in any app.
2. Open Phosphene.
3. When macOS asks, allow System Audio Recording. Phosphene uses it only to
   hear the sound. It never records the screen or the microphone, and it never
   saves audio.

A white line across the window means Phosphene is listening. While no sound
comes, the line slowly brightens and dims, and after a few seconds a short
message under it says what to do, for example "Play some music on your Mac".
Visuals start as soon as sound arrives and change by themselves every 20 to 40
seconds.

## Keys

- Space or Right Arrow (⌘N): next visual
- L (⌘L): lock or unlock the current visual
- F (⌃⌘F): full screen on or off
- ⌘B: show the visual list
- ⌥⌘A: Analyse Music
- ⇧⌘N: new window showing the same visual as the main window
- ⌘,: open Settings
- Esc: close the visual list, or leave full screen
- ⌘W: close the front window (closing the main window quits)
- ⌘Q: quit

Every action is also in the menus.

## Choosing visuals

While you move the mouse, a Visuals tab shows in the middle of the left edge
of the window. Click it to open the visual list; while the list is open, the
tab sits on its edge, and a second click closes it. A click on the picture
also closes the list. You can also click the
Visuals button at the top left of the window (click it again to close the
list), or choose Visuals → Show Visuals (⌘B). The list stays while the pointer
is over it, and slides away by itself a few seconds after. Esc closes it at
once. With Keyboard navigation turned on (System Settings →
Keyboard) or VoiceOver, ⌘B also puts the keyboard in it: Tab moves through the
list and Space ticks a box.

- The checkboxes choose which visuals take turns.
- Click a name to show that visual right away, even if it is unchecked. With
  no music playing, it starts as soon as sound arrives.
- All Visuals checks every visual, or clears them all if all are checked.
- If nothing is checked, Phosphene shows only the listening line.
- When a new visual comes on, its name shows for a moment in the bottom-left
  corner. Click it to open the visual list.

## Locking a visual

Normally the visuals change by themselves. To keep the one on screen, press L,
choose Visuals → Lock Visual, or click Lock at the top of the visual list. To
play another visual and lock it at once, right-click its name in the visual
list (or Control-click it) and choose Play and Lock; on the locked visual the
same menu says Unlock.

- While locked, the visual stays until you unlock it.
- Next Visual (Space) still works: it moves to another visual, and the lock
  stays on the new one. Clicking a name in the visual list does the same.
- "🔒 Locked" appears briefly in the top-right corner, and a padlock shows in
  the window title, in the visual list and next to the locked visual's name.
- To unlock, press L again, choose Visuals → Unlock Visual, click Unlock at
  the top of the visual list, or click the "🔒 Locked" badge.
- The lock is remembered: when you open Phosphene again, it starts with the
  same visual as soon as music plays (if it is still checked in the visual
  list).

## More windows

You can open up to four more windows of visuals. Choose Window → New Window,
then the visual the window should show: Same as Main Window (⇧⌘N) follows
whatever the main window shows, or pick any visual for it. To change a
window's visual later, right-click the picture (or Control-click it) and
choose another.

- Move and size it like any window, or drag it to another screen or a
  projector and show it full screen there.
- To show it full screen, click its green button, choose View → Enter Full
  Screen, or press F while it is in front. Esc leaves full screen.
- Close it with its close button or ⌘W.
- With four windows open, New Window is greyed out until you close one.
- These windows are not kept when you quit: next time Phosphene opens with
  its main window only.
- Each window with a visual of its own makes your Mac work about as hard as
  another Phosphene. Windows showing the same visual as the main window cost
  almost nothing.

## Analyse Music

Analyse Music shows what Phosphene hears, in place of the visuals. Open it
with Audio → Analyse Music (⌥⌘A), or with the Analyse Music button at the
top of the visual list. It shows:

- Instruments: the instruments and voices heard now, such as Vocals, Drums,
  Electric guitar or Piano, with a line under each showing how sure macOS
  is. A name appears about a second after the instrument starts and fades
  soon after it stops. The names are approximate: in a dense mix an
  instrument can be missed or named as a similar one, and unusual voices may
  not be recognised as singing.
- Spectrum: how loud each part of the sound is, from the deepest bass
  (20 Hz) to the highest treble (20 kHz), with the recent peaks marked.
- Sound: the music's tempo, loudness, beat, bass, mids and treble, drum
  hits, the singer's note, brightness, how much the sound is changing, and
  stereo width. The tempo appears after a few bars of music with drums.

While it is shown, the visual on screen pauses. To go back, click Close in
its top-right corner or Back to Visuals in the visual list, press Esc or
Space, or click a visual in the list: the visual carries on where it was,
still locked if it was locked.

Instruments are recognised by macOS's built-in sound recognition, entirely on
your Mac and only while Analyse Music is shown. No sound is saved or sent.

## Choosing what Phosphene listens to

By default Phosphene hears every app. Use the Audio menu to change that:

- All Sound: listen to everything your Mac plays, from every app at once.
- An app's name: listen only to that app, for example your music player, so a
  video or a call elsewhere does not move the visuals. The menu lists the
  supported apps that are running (see below): under Playing Now those
  playing at this moment, under Not Playing the others. Your chosen app stays
  in the list, and if it is not running, Phosphene waits and starts listening
  when it opens.
- Pause Listening: stop listening. While paused, the same item reads Resume
  Listening and starts listening again.
- Retry Listening: start listening again after a problem.
- Audio Permission…: explains why Phosphene needs to hear the sound, and lets
  you allow it, or open System Settings to allow it there.

The window title shows the current visual, what Phosphene listens to, and
whether it is listening or paused.

## Supported apps

You can listen to one of these apps on its own:

- Music players: Apple Music, Spotify, TIDAL, Deezer, Amazon Music, VLC
- Browsers (for YouTube, SoundCloud, Bandcamp and other players on the web):
  Safari, Google Chrome, Firefox

Sound from any other app is heard with All Sound. A browser is heard as a
whole: music in one tab and a video in another are heard together.

## Paused during a call

Pause during calls is on by default. About once a second, Phosphene checks
whether another app is using audio input, such as a microphone during a call
in Google Meet, Zoom, Teams or FaceTime. When it detects input use, it stops
listening and the window title says "Paused during a call". When input use
ends, it starts listening again by itself. A pause you choose yourself stays
paused.

This is a best-effort safeguard. Detection takes time, so All Sound can briefly
include other participants' voices before listening pauses. If macOS cannot
determine whether input is in use, Phosphene keeps its current state: existing
listening continues, and an existing call pause stays paused. Phosphene does
not directly capture microphone input, and audio is never saved or sent anywhere.

Calls that do not use a microphone cannot be identified this way. To keep call
audio out, choose Audio → Pause Listening before joining, or select a separate
music app. A selected browser includes audio from all its tabs, including calls.

Other apps that take in sound, such as dictation or a sound recorder, can also
trigger a pause; playing music on a headset does not. You can turn automatic
call pausing off in Settings (Pause during calls).

## Settings

Open Phosphene → Settings… (⌘,). Each setting is a choice from a list or a
checkbox, with a short explanation under it. Changes apply when you click Save.

- Visual quality: how sharp the picture is (Low, Standard, High or Very High).
  Lower is lighter on older Macs and on the battery.
- Frame rate: how smoothly the visuals move. 30 fps uses the least power;
  Display refresh rate is the smoothest.
- Each visual stays: how long a visual stays before the next one, for example
  20 s to 40 s. Phosphene picks a random time in this range and changes on a
  beat. If you choose a longest time shorter than the shortest, both are the
  shortest.
- Pause during calls: pauses listening when another app's audio input use is
  detected, and resumes after. On by default; see the limitations above.
- Gentler effects: fewer flashes, camera jumps and fast motion.
- Reset Defaults: puts every choice back to the original setting. The
  window stays open; click Save to keep them, or Cancel to keep what you had.
- Open Settings Folder: shows where Phosphene keeps its settings.

Window → Keep on Top keeps Phosphene above other windows. Phosphene remembers
your visuals, your audio source, the lock and its window position for the next
time you open it.

## If something does not work

The visuals do not react to the music:

1. Read the message under the white line: it says what Phosphene is waiting
   for, such as music in the chosen app or the permission to hear it.
2. Check that music is playing and that the window title says Listening.
3. In the Audio menu, check that the right source is chosen (All Sound, or
   the app that is playing).
4. Choose Audio → Retry Listening.
5. Open System Settings → Privacy & Security → Screen & System Audio Recording,
   and make sure Phosphene is allowed under System Audio Recording Only.
   Quit and reopen Phosphene after allowing it.

The window title says "Silent": the app plays, but only silence arrives. It
may be muted (a muted video, or its volume at zero); unmute it. Otherwise,
allow Phosphene as in step 5 above, then choose Audio → Retry Listening.

Some protected media, such as certain streaming video, cannot be heard by any
app. That is a macOS limit, not a fault in Phosphene.

macOS did not ask for permission: choose Audio → Audio Permission…, or allow
Phosphene in System Settings as in step 5 above.

The visuals flash too much: turn on Gentler effects in Settings. It reduces
flashes and motion but cannot guarantee safety for photosensitive viewers.

Phosphene uses too much power or runs slowly: lower Visual quality or the
Frame rate in Settings.

To start fresh, choose Reset Defaults in Settings. To remove everything
Phosphene saved, quit it and delete the files shown by Open Settings Folder.

## Getting help

Report a problem or ask a question at
<https://github.com/janosvajda/phosphene-site/issues>
(in the app: Help → Report a Problem…).

Please include your macOS version, your Mac model, the Phosphene version
(Phosphene → About Phosphene), and what you did before the problem appeared.
Issues there are public: do not post recordings, personal details or anything
private.

## Privacy

Phosphene analyses sound only on your Mac and never saves or sends it. Read
the full [privacy policy]({{ "/privacy/" | relative_url }}) or, offline, in
Help → Privacy Policy…

More about Phosphene: [the Phosphene home page]({{ "/" | relative_url }})

---

© 2026 Jan Vajda. All rights reserved.
