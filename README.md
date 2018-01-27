# push2-fifths-scale
A MIDI Remote Script enhancement which adds '5ths' to the list of scales for your Push2 for use with Ableton Live

## 5ths for Push2 (scripts for 9.6, 9.7.5 and 10)

This customized version of Ableton Live's `scales_component` Python module adds **5ths** to the list of available chromatic scales. This tuning is perfect if you are a string player used to mandolin, violin, Chapman Stick, or Robert Fripp's NST (New Standard Tuning) for guitar. It's also great for getting some very beautiful and wide chord voicings on synthesizers with limited polyphony, (Volca Keys, Minilogue, etc). 

Installation is pretty easy, and Ableton actually has a page to show you how to do this more generally at https://help.ableton.com/hc/en-us/articles/209072009-How-to-install-a-third-party-Remote-Script-

## How to install on Windows
Not yet written as I don't have a Windows box.

## How to install on OSX

1. **Make sure you are not running Live.**

2. Back up Ableton's MIDI Remote Scripts in `/Applications/Ableton Live 9 Suite.app/Contents/App-Resources/MIDI Remote Scripts/Push2`. From the terminal, you can find these files at `/Applications/Ableton Live 9 Suite.app/Contents/App-Resources/MIDI Remote Scripts/Push2`. To get there from the terminal, you can just copy and paste `cd /Applications/Ableton\ Live\ 9\ Suite.app/Contents/App-Resources/MIDI\ Remote\ Scripts/Push2/` into the Terminal app.

2. In the above-mentioned directory, delete `scales_component.pyc`. (If you're not a commandline kind of a person, you can type `open .` once you're in this directory and you can use the Finder)

3. Copy `scales_component.py` into the directory. Make sure to use the version of this file for your version of Ableton Live

Now when you push the `Scale` button on your Push2, you will have `5ths` as an available option.
