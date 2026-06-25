# Trigger changelog

All notable changes to Trigger, the Ableton Live remapping utility from All Good Folks.

## 1.4

New
- In-app updates: Trigger now tells you the moment a new version is out and installs it for you in one click, no more manual downloads.

Improved
- Faster, more reliable key and MIDI mapping.

Fixed
- Small fixes and polish.

## 1.3

Fixed
- Pause remaps while typing now reliably detects Live's text fields. When you rename a track, clip or scene, or type in the browser search, a remapped single key types the character instead of firing its shortcut. The detection was reworked to read Live 12's focused field two ways (its text-field role and any focused field that accepts typed text), so it no longer misses a rename and never freezes the keyboard while reading.

## 1.2

New
- Keep Ableton views in sync: Trigger reads Live's View menu so your remaps stay accurate to what is actually showing.
- Minimize Ableton with Cmd+M: optional override so the shortcut minimises Live instead of the foreground window.
- Compact menu bar icon: a slimmer icon option showing just the middle three keys.
- Attach window to menu bar: choose between a popover that drops from the icon or a free floating, movable window.
- About screen now links to allgoodfolks.com/apps and the All Good Folks Spotify.

Improved
- Custom tab bar replaces the native band so the panel reads as one clean surface.
- Floating window for Remaps and Reference is now resizable, while Settings stays at a fixed, tidy size.
- Appearance control (System, Light, Dark) now applies reliably across the whole app.
- Clearer wording: remaps now say they "override" Ableton's defaults rather than "conflict with" them.
- The window opens on a manual launch but stays out of the way on a login launch.
- Dock icon and menu bar icon both toggle the window open and closed.
- Several settings now ship on by default for a better out of the box experience.

Fixed
- Pause remaps while typing: when you rename a track, clip or scene, or type in the browser search, a remapped single key now types the character instead of firing its shortcut. On by default, with a switch in Settings.
- Fixed a rare crash while reading incoming MIDI.
- Hardened the Accessibility reads so a slow response can no longer freeze the keyboard.

## 1.1

New
- Live view syncing groundwork and the first Cmd+M handling.

Improved
- Onboarding and Accessibility permission flow refined.

Fixed
- Stability fixes ahead of wider release.

## 1.0

- First public release.
- Map any key or MIDI note or CC to any Ableton Live command, for Live 11 and Live 12.
- Chain several actions onto a single trigger, fired all at once or as a sequence.
- Remaps only fire while Ableton Live is in focus.
- Menu bar app with a clean reference of your mappings.
- Licensed through Lemon Squeezy.
