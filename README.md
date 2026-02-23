# microMid
microMid is a pretty scuffed way of playing MIDIs on a Micro:Bit. It supports pretty much any MIDI, has multitone playback, and it is as fast as I can make it, at the cost of not being able to play different instruments.
## How to use
1. Put your midi into https://rexrainbow.github.io/C2Demo/MIDI%20to%20CSV/ and put the output in a text file
2. Open the SB3 file (in the editor) found in the project using Turbowarp and press SPACE. Insert your text file and press the green flag. Wait for the song to finish and copy the last item in the 'result' list
3. Load this project into Micro:Bit Makecode using the attached HEX file and replace `let song = "[...]"` with `let song = "RESULT FROM STEP 2"`, and if you want, the `70` below with the song tempo.
4. Download the project to your Micro:Bit and enjoy!

(hope this made sense)

If you don't see the files, check later, it means that I am uploading them.


> Open this page at [https://b06danel.github.io/micromid/](https://b06danel.github.io/micromid/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/b06danel/micromid** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/b06danel/micromid** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
