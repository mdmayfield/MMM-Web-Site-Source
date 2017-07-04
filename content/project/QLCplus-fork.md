+++
# Date this page was created.
date = "2017-07-02"

# Project title.
title = "Customized Lighting Software"

# Project summary to display on homepage.
summary = "A fork of QLC+ lighting software for Mac, Linux, and Windows."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "lights.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["technology"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/lights2.jpg"
caption = ""

+++

This is a work in progress - a fork of open source [QLC+ lighting software](http://www.qlcplus.org) designed specifically to be controlled by a DAW / MIDI sequencer.

If you'd like to try it, source code is available on my [GitHub page](https://github.com/mdmayfield/qlcplus). Build instructions are available on the [wiki of the upstream project](https://github.com/mcallegari/qlcplus/wiki).

The primary differences from the original by Massimo Callegari are:

- Additional keyboard shortcuts
- Many existing keyboard shortcuts changed to avoid collisions with OS shortcuts
- Function Picker dialog box now defaults to Running Functions
- Add To Chaser button in the Scene Editor no longer makes a copy of the current Scene
- Ability to enter "i" for Infinity duration in Chasers & Sequences
- Ability to enter "d" for Default for fade in / fade out in Chasers & Sequences
- Virtual Console Cue List widget "Steps" mode has been altered:
  - Assign a MIDI CC to control the Cue List
  - Send a value from 1 - 127 on that CC through IAC to QLC+
  - The Cue List will jump directly to the step numbered the same as the CC value

The new keyboard shortcuts are:

|Global:||
|-----|----|
|Alt/Option-1|Fixtures|
|Alt/Option-2|Functions|
|Alt/Option-3|Shows|
|Alt/Option-4|Virtual Console|
|Alt/Option-5|Simple Desk|
|Alt/Option-6|Inputs/Outputs|
|Cmd/Ctrl-R|Stop All Functions|
|Cmd/Ctrl-T|Live/Edit Mode|
|Cmd/Ctrl-E|Virtual Console Live Edit|
|Cmd/Ctrl-L|Function Live Edit|
|Alt/Option-R|(Function picker) Running Functions|
|Alt/Option-A|(Function picker) All Functions|

|Virtual Console:||
|-----|----|
|Shift-Cmd/Ctrl-B|New Button|
|Shift-Cmd/Ctrl-M|New Button Matrix|
|Shift-Cmd/Ctrl-S|New Slider|
|Shift-Cmd/Ctrl-I|New Slider Matrix|
|Shift-Cmd/Ctrl-K|New Knob|
|Shift-Cmd/Ctrl-D|New Speed Dial|
|Shift-Cmd/Ctrl-X|New XY Pad|
|Shift-Cmd/Ctrl-C|New Cue List|
|Shift-Cmd/Ctrl-R|New Animation|
|Shift-Cmd/Ctrl-A|New Audio Triggers|
|Shift-Cmd/Ctrl-F|New Frame|
|Shift-Cmd/Ctrl-O|New Solo Frame|
|Shift-Cmd/Ctrl-L|New Label|
|Shift-Cmd/Ctrl-T|New Clock|

|Function Manager:||
|-----|----|
|Shift-Cmd/Ctrl-S|New Scene|
|Shift-Cmd/Ctrl-C|New Chaser|
|Shift-Cmd/Ctrl-E|New EFX|
|Shift-Cmd/Ctrl-O|New Collection|
|Shift-Cmd/Ctrl-R|New RGB Matrix|
|Shift-Cmd/Ctrl-T|New Script|
|Shift-Cmd/Ctrl-A|New Audio|
|Shift-Cmd/Ctrl-V|New Video|
|Shift-Cmd/Ctrl-N|New Folder|

|Scene Editor:||
|-----|----|
|Shift-Cmd/Ctrl-Right|Next Tab|
|Shift-Cmd/Ctrl-Left|Previous Tab|
|Shift-Cmd/Ctrl-Down|Switch between tab view and all channels view|
|Shift-Cmd/Ctrl-Up|Copy current values to all (selected) fixtures|
