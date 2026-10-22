# Phosphene Help

Online: https://janosvajda.github.io/phosphene-site/support

Phosphene turns the sound your Mac plays into visuals that move with the music.
It is free, with no account, advertising or tracking.

## What you need

- macOS 14.2 or newer

## Getting started

1. Play some music in any app.
2. Open Phosphene.
3. When macOS asks, allow System Audio Recording. Phosphene uses it only to
   hear the sound. It never records the screen or the microphone, and it never
   saves audio.

A white line across the window means Phosphene is listening. Visuals start as
soon as sound arrives and change by themselves every 20 to 40 seconds.

## Keys

- Space or Right Arrow (⌘N): next visual
- L (⌘L): lock or unlock the current visual
- F (⌃⌘F): full screen on or off
- ⌘B: show the visual list
- ⌘,: open Settings
- Esc: leave full screen, or quit

Every action is also in the menus.

## Choosing visuals

Open the visual list with View → Show Visuals (⌘B), or move the pointer to the
left edge of the window.

- The checkboxes choose which visuals take turns.
- Click a name to show that visual right away, even if it is unchecked.
- All Visuals checks every visual, or clears them all if all are checked.
- If nothing is checked, Phosphene shows only the listening line.

To keep one visual on screen, use View → Lock Visual (L). A lock symbol
appears in the window title while it is locked.

## Choosing what Phosphene listens to

By default Phosphene hears every app. Use the Config menu to change that:

- All Apps: listen to everything.
- An app's name: listen only to that app, for example your music player, so a
  video or a call elsewhere does not move the visuals. If the app is not
  running, Phosphene waits and starts listening when it opens.
- Pause Listening: stop listening until you choose it again.
- Demo: play built-in synthesized music, without listening to your Mac.
- Retry Audio Capture: start listening again after a problem.
- Enable System Audio… and Open Audio Privacy Settings…: give Phosphene
  permission to hear the sound.

The window title shows the current visual, what Phosphene listens to, and
whether it is listening, paused or playing the demo.

## Settings

Open Phosphene → Settings… (⌘,):

- Visual quality: Low, Standard, High or Very High. Lower quality is lighter
  on older Macs and on the battery.
- Frame rate: lower rates use less power; Display refresh rate uses the full
  rate of your screen.
- Minimum and maximum scene seconds: how long each visual stays.
- Gentler effects: reduces flashes, camera jumps and fast motion.
- Reset Defaults: brings back the original settings.
- Open Settings Folder: shows where Phosphene keeps its settings.

Window → Keep on Top keeps Phosphene above other windows. Phosphene remembers
your visuals, your audio source, the lock and its window position for the next
time you open it.

## If something does not work

The visuals do not react to the music:

1. Check that music is playing and that the window title says Listening.
2. In the Config menu, check that the right source is chosen (All Apps, or
   the app that is playing).
3. Choose Config → Retry Audio Capture.
4. Open System Settings → Privacy & Security → Screen & System Audio Recording,
   and make sure Phosphene is allowed under System Audio Recording Only.
   Quit and reopen Phosphene after allowing it.

Some protected media, such as certain streaming video, cannot be heard by any
app. That is a macOS limit, not a fault in Phosphene.

macOS did not ask for permission: choose Config → Enable System Audio…, or
allow Phosphene in System Settings as in step 4 above.

The visuals flash too much: turn on Gentler effects in Settings. It reduces
flashes and motion but cannot guarantee safety for photosensitive viewers.

Phosphene uses too much power or runs slowly: lower Visual quality or the
Frame rate in Settings.

To start fresh, choose Reset Defaults in Settings. To remove everything
Phosphene saved, quit it and delete the files shown by Open Settings Folder.

## Getting help

Report a problem or ask a question at
https://github.com/janosvajda/phosphene-site/issues
(in the app: Help → Report a Problem…).

Please include your macOS version, your Mac model, the Phosphene version
(Phosphene → About Phosphene), and what you did before the problem appeared.
Issues there are public: do not post recordings, personal details or anything
private.

## Privacy

Phosphene analyses sound only on your Mac and never saves or sends it. Read
the full privacy policy at https://janosvajda.github.io/phosphene-site/privacy
or, offline, in Help → Privacy Policy…

More about Phosphene: https://janosvajda.github.io/phosphene-site/
