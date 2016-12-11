# studioone-mpd218-integration

It provides AKAI MPD218 device settings for Presonus Studio One 3.

## Installation

### on Windows

1) Launch `Command Prompt` and input following command:

```
explorer "%APPDATA%\Presonus\Studio One 3"
```

2) Copy from subfolders in `User Devices\AKAI` to the corresponding folder.

### on Mac OS X

1) Launch `Terminal` and input following command:

```
open "~/Library/Application Support/PreSonus Software/Studio One 3"
```

2) Copy from subfolders in `User Devices\AKAI` to the corresponding folder.

## Devices

### MPD218

It enables pads and knobs integration.

- from : MPD218
- to : None
- filters : all off

*for Battery 4 Users* : "Learn MIDI CC" feature is not available; use host automation instead.

### MPD218 (External Clock)

It enables note repeat feature.

- from : None
- to : MPD218
- send MIDI clock : on
- send MIDI clock start : on
- send MIDI time code : off

Press NR CONFIG and see if the PAD 15 (EXT CLOCK) is on. If not, toggle PAD 15 to use external clock (DAW tempo sync).

*Important*: Note repeating is only enabled in recording state. Otherwise no sound triggered with pressing NOTE REPEAT button.

ckbx_cakebox
- Blog: http://cakebox-music.com/
- Twitter: https://twitter.com/ckbx_cakebox
