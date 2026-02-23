# microMid
microMid is a pretty scuffed way of playing MIDIs on a Micro:Bit. It supports pretty much any MIDI, has multitone playback, and it is as fast as I can make it, at the cost of not being able to play different instruments.
## How to use
1. Put your midi into https://rexrainbow.github.io/C2Demo/MIDI%20to%20CSV/ and put the output in a text file
2. Open the SB3 file (in the editor) found in the project using Turbowarp and press SPACE. Insert your text file and press the green flag. Wait for the song to finish and copy the last item in the 'result' list
3. Load this project into Micro:Bit Makecode and replace `let song = "[...]"` with `let song = "RESULT FROM STEP 2"`, and if you want, the `70` below with the song tempo.
4. Download the project to your Micro:Bit and enjoy!

(hope this made sense)

If you don't see the file, check later, it means that I am uploading them.
