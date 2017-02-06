# push2-fifths-scale
A MIDI Remote Script enhancement which adds '5ths' to the list of scales for your Push2 for use with Ableton Live

## 5ths for Push2

This customized version of Ableton Live's `scales_component` Python module adds **5ths** to the list of available chromatic scales. This tuning is perfect if you are a string player used to mandolin, violin, Chapman Stick, or Robert Fripp's NST (New Standard Tuning) for guitar. It's also great for getting some very beautiful and wide chord voicings on synthesizers with limited polyphony, (Volca Keys, Minilogue, etc). 

Installation is pretty easy.:

1. **Make sure you're not running Live.**

2. **Back up Ableton's MIDI Remote Scripts.** From the terminal, you can find these files at `/Applications/Ableton\ Live\ 9\ Suite.app/Contents/App-Resources/MIDI\ Remote\ Scripts/Push2/`

2. In the above-mentioned directory, delete `scales_component.pyc`

3. Copy `scales_component.py` (this file) to `/Applications/Ableton\ Live\ 9\ Suite.app/Contents/App-Resources/MIDI\ Remote\ Scripts/Push2/`

Now when you push the `Scale` button on your Push2, you will have `5ths` as an available option.
