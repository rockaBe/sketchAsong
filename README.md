# sketchAsong

## The idea

1. Record your song ideas and reassemble parts to a song sketch

2. Get suggestions on chord progression

3. Export a MIDI file to work in a SAW

## The approach

Eat your own dog food.

## Milestones (as for now ...)

1. Setup
    1. start with a basic react native app and learn about setup, cross compilation and some Pros & Cons
    1. make audio recording work
    1. playback the recored audio
    1. visualize the recorded audio

1. Analyze and enrich
    1. analyze the recorded audio and extract the chords used (e.g. via [sonic api](http://www.sonicapi.com/docs/api/analyze-chords)) and display response (e.g. `xml` to `json` conversion)
    1. enrich the recorded audio's visualization with chords

1. Edit "song"
    1. enable creating song parts (initially just splitting the file into pieces and store them separately as 'parts')

    2. make parts editable
        1. naming the parts
        2. change order
        3. copy & paste
